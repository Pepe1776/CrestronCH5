<script>
import SourceBar from "../components/SouceBar.vue";
export default {
  components: { SourceBar },
};
</script>

<template>
  <h1>Living Room</h1>
  <router-view />
  <SourceBar />
</template>

<style lang="scss">
@import "../Sass/abstracts.scss";
.source {
  position: relative;
  transition: background 0.6s ease-in-out;
}

.source-bar {
  position: absolute;
  bottom: -68rem;
  align-items: center;
  display: flex;
  transition: background 0.6s ease-in-out;
}

.source-bar-link {
  display: inline-block;
  font-size: 4rem;
  justify-content: space-evenly;
  margin-left: 9rem;
  border-radius: 2rem;
}
.source-bar-link:hover {
  color: $primary;
  border: 3px solid black;
  // background-color: $darkest;
  transform: scale(1.1);
}
.watch-bar-buttons {
  width: 100%;
  height: 10%;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
</style>
