<template>
  <section id="about" class="about-wrapper">
    <div class="img-wrapper">
      <img src="../assets/images/about-us_img.png" alt="">
    </div>
    <div class="about-section">
      <div>
        <h2>Quem somos</h2>
        <h3>Entenda nossa missão com você</h3>
      </div>
      <p>
        <span>
          Propomos um caminho simples: treinos personalizados que você pode fazer onde e quando quiser, planos
          alimentares adaptados ao seu dia a dia e práticas de mindfulness para aliviar o estresse.</span>
        <span>
          Com suporte de especialistas e um app intuitivo, nossa missão é entregar bem-estar que funciona para você –
          real, acessível e sem complicações.
        </span>

      </p>
    </div>
  </section>
</template>

<script setup>

</script>

<style scoped>
.about-wrapper {
  display: flex;
  gap: 2em;
}

.img-wrapper {
  width: 900px;
  height: 300px;
  border-radius: 1em;

  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: inherit;
  }
}

.about-section {
  background: var(--secondary);
  padding: 1em;
  border-radius: 1em;
  color: white;
  display: flex;
  flex-direction: column;
  gap: 2em;
  user-select: none;

  h2 {
    font-size: 2em;
  }

  h3 {
    font-weight: 200;
  }

  p {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    height: 100%;
    font-size: 1.2em;
    font-weight: 300;
  }
}
</style>
