<template>
  <main>
    <h1>
      <span class="text-primary">Baba</span> is
      <span class="text-alt">Bedrock</span>
    </h1>
    <div class="baba-content">
      <img alt="Baba" src="@/assets/Bedrock.png" />
    </div>
  </main>
</template>

<style scoped lang="scss">
.text-alt {
  -webkit-text-stroke: $stroke-width $gray;
  color: $gray;
  text-transform: uppercase;
}
</style>
