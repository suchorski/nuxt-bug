<template>
  <main>
    <header>Example of Header</header>
    <slot />
    <footer>Example of Footer</footer>
  </main>
</template>

<style lang="postcss" scoped>
main {
  color: white;
  display: grid;
  gap: 1rem;
}

header {
  background-color: darkblue;
  padding: 1rem;
}

footer {
  background-color: darkgreen;
  padding: 1rem;
}
</style>
