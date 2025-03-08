<template>
  <nav class="nav-wrapper">
    <h1 class="logo-item">FITFLOW</h1>
    <ul class="navlinks-wrapper">
      <li class="nav-item"><a href="#about">Sobre nós</a></li>
      <li class="nav-item"><a href="#feedback">Avaliações</a></li>
      <li class="nav-item"><a href="#">Planos</a></li>
    </ul>
  </nav>
</template>

<script setup>

</script>

<style scoped>
.nav-wrapper {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: var(--secondary);
  padding: .5em 2em;
}

.logo-item {
  color: var(--primary);
  font-size: 2.5em;
  font-weight: 800;
  user-select: none;
}

.navlinks-wrapper {
  display: flex;
  gap: 2em;
}

.nav-item {
  list-style-type: none;
  font-size: 1.2em;
  user-select: none;

  a {
    text-decoration: none;
    color: white;
    font-weight: 500;
    transition: all .1s ease-in-out;

    &:hover {
      color: var(--primary);
      border-bottom: 2px solid var(--primary)
    }
  }
}
</style>
