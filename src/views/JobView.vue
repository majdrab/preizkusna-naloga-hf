<template>
    <MajContainer class="job" centerX centerY>
        <MajTitle is="h1">WIP</MajTitle>
    </MajContainer>
</template>

<script>
export default {
  name: "JobView",
}
</script>

<style lang="scss">
.job {
  width: 100vw;
  padding: 50px 0 30px;
  flex-grow: 1;
  background: $lPrimary;
  .maj-title {
    color: $light;
  }
}
</style>
