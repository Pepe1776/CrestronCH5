<script>
export default {};
</script>

<template>
  <div class="source">
    <div class="source-bar">
      <button class="source-bar-link">Watch</button>
      <button class="source-bar-link">Listen</button>
      <button class="source-bar-link">Lighting</button>
      <button class="source-bar-link">Scenes</button>
    </div>
  </div>
</template>

<style lang="scss">
@import "../Sass/abstracts.scss";

source {
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
