<template>
  <main>
    <h1>
      <span class="text-primary">Baba</span> is
      <span class="text-alt">Rock</span>
    </h1>
    <div class="baba-content">
      <img alt="Baba" src="@/assets/Rock.png" />
    </div>
  </main>
</template>

<style scoped lang="scss">
.text-alt {
  -webkit-text-stroke: $stroke-width $brown;
  color: $brown;
  text-transform: uppercase;
}
</style>
