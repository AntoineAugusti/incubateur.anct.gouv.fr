<template>
  <Layout>
    <div class="offres">
      <div class="splash">
        <h1>Offres</h1>
      </div>

      <div class="content">
        <h2>Nos offres aux collectivités territoriales</h2>
        <p></p>

        <h2>Nos offres aux startups de territoires</h2>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Offres'
  }
}
</script>

<style lang="scss">
.offres {
  .splash {
    @apply py-8 mb-12 font-marianne text-white bg-navy;

    h1 {
      @apply text-5xl font-black mx-auto max-w-screen-md;
    }
  }

  .content {
    @apply mx-auto max-w-screen-md;

    h1,
    h2,
    h3,
    h4 {
      @apply font-marianne font-black;  
    }

    h1 { @apply text-5xl mb-12; }
    h2 { @apply text-3xl mb-8; }

    p { @apply mb-4 }
  }
}
</style>
