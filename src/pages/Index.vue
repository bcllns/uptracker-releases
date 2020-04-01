<template>
  <Layout>
    <h1>
      Uptracker Updates
    </h1>
     Some content.
  </Layout>
</template>

<script>
</script>


<style lang="scss" scoped>
/deep/ > p {
  opacity: .8;
}

/deep/ > h2 {
  padding-top: 100px;
  margin-top: -80px;

  @include respond-above(md) {
    font-size: 2rem;
  }
}

/deep/ > p > img {
    max-width: 100%;
  }

.markdown {
  padding-bottom: 50vh;
}
</style>
