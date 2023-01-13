<template>
    <footer class="footer">
        <div class="footer__margin"></div>
        <div class="footer__content"></div>
    </footer>
</template>

<script>
// import BotLeftSvg from "./BgSvgs/BotLeftSvg.vue";

export default {
  name: "SiteFooter",
}
</script>

<style lang="scss">
.footer {
  width: 100vw;
  height: calc(462.05px + 124px);
  background: #1B2626;
  &__margin {
    width: 100%;
    height: 124px;
    background: $bg;
  }
}
</style>