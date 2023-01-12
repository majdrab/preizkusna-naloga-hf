<template>
    <header class="header">
        <div class="header__gradient-1"></div>
        <img class="header__image-1" src="../assets/images/image23.png" /> 
        <div class="header__gradient-2"></div>
        <div class="header__gradient-3"></div>
        <HFLogo class="header__logo"/>
        <div class="header__rectangle"></div>
        <img class="header__image-2" src="../assets/images/group81.png" />
        
    </header>
</template>

<script>
import HFLogo from "./headerComponents/HFLogo.vue";

export default {
  name: "SiteHeader",
  components: { HFLogo }
}
</script>

<style lang="scss">
.header {
  position: relative;
  width: 100%;
  left: 0;
  top: 0;

  &__image-1 {
    position: absolute;
    aspect-ratio: 1900/572.95;
    width: 100%;
    // height: 100%;
    left: 0;
    top: 0;
  }
  &__gradient-1 {
    position: absolute;
    aspect-ratio: 1900/512.34;
    width: 100%;
    left: 0px;
    top: 0px;
    background: linear-gradient(85.11deg, #1B1C27 24.58%, #161826 71.42%, #34EAC9 130.24%);
  }
  &__gradient-2 {
    position: absolute;
    margin-top: 15%;
    aspect-ratio: 1900/311.03;
    width: 100%;
    left: 0px;
    top: 0;
    background: linear-gradient(180deg, rgba(16, 20, 20, 0) 0%, #101414 100%);
  }
  &__gradient-3 {
    position: absolute;
    aspect-ratio: 1900/686;
    width: 100%;
    left: 0px;
    top: 0;
    background: linear-gradient(180deg, rgba(16, 20, 20, 0) 0%, #101414 100%);
  }
  &__rectangle {
    position: absolute;
    margin: 6.2% 2.7%;
    aspect-ratio: 1797.66/370;
    width: calc(100% - 5.4%);
    left: 0;
    top: 0;
    background: #182222;
    opacity: 0.8;
    // z-index: 1;
  }
  &__image-2 {
    position: absolute;
    margin: -3.8% 47.5% 0;
    aspect-ratio: 739/759.72;
    width: 40%;
    // height: 100%;
    left: 0;
    top: 0;
    // left: 901.87px;
    // top: -69.75px;
  }
  &__logo {
    position: absolute;
    margin: 2% 2.8%;
    aspect-ratio: 221.79/45;
    width: 11.7%;
    // min-width: 100px;
  }
}
</style>