<template>
    <MajContainer class="home" centerX centerY>
        <!-- <img class="home__header-image" src="../assets/images/image23.png" />  -->
        <div class="home__header">
            <!-- <div class="home__header-rectangle"></div> -->
        </div>
    </MajContainer>
</template>

<script>

export default {
  name: "HomeView",
}
</script>

<style lang="scss">
.home {
  width: 100vw;
  height: 2572.6px;
  flex-grow: 1;
  position: relative;
  &__header {
    position: absolute;
    aspect-ratio: 1900/572.95;
    left: 0;
    top: 0;
    background: url("./image23.png");
  }
  &__header-image {
    width: 100vw;
  }
  &__header-rectangle {
    // margin: 116px 51.11px 0;
    aspect-ratio: 1797.66/370;
    width: calc(100vw - 102.22px);
    position: absolute;
    left: 51.11px;
    top: 116px;
    background: #182222;
  }
}
</style>
