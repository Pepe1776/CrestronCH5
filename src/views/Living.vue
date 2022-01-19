<script>
export default {};
</script>

<template>
  <div class="Container">
    <div class="source">
      <div class="source-bar center">
        <router-link to="watch1" class="source-bar-link">Watch</router-link>
        <router-link to="listen1" class="source-bar-link">Listen</router-link>
        <router-link to="lighting1" class="source-bar-link"
          >Lighting</router-link
        >
        <router-link to="scenes1" class="source-bar-link">Scenes</router-link>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
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
</style>
