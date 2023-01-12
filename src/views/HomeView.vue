<template>
    <MajContainer vertical class="home" centerX>
        <section class="home__job-overview">
            <MajTitle is="h3">WordPress developer</MajTitle>
        </section>
        <section class="home__job-overview">
            <MajTitle is="h3">WordPress developer</MajTitle>
        </section>
        <section class="home__job-overview">
            <MajTitle is="h3">WordPress developer</MajTitle>
        </section>
        <!-- <MajDivider /> -->
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
  height: 572.6px;
  margin-top: 29%;
  flex-grow: 1;
  position: relative;

  &__job-overview {
    width: 1032.68px;
    padding: 18.39px 0;
    max-width: calc(100% - 5.4%);
    border-top: 1px solid #707070;
    &:last-of-type {
      border-bottom: 1px solid #707070;
    }
    h3.maj-title {
      display: inline;
      padding: 2px 0;
      border-bottom: 1px dashed #FFFFFF;
    }
  }
} 
</style>
