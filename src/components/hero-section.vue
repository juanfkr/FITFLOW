<template>
  <div class="hero-wrapper">
    <img class="img-item" src="../assets/images/hero-img.jpg" alt="">
    <div class="cta-item">
      <p class="paragraph">
        <span>Mudança é</span> <br> <b>o primeiro</b> <br> <span>movimento</span>
      </p>
      <button class="button">Mudar agora</button>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
.hero-wrapper {
  width: 100%;
  height: 500px;
  position: relative;

  @media (max-width: 553px) {
    height: 300px;
  }
}

.img-item {
  width: 100%;
  height: 100%;
  object-fit: cover;
  position: absolute;
  z-index: -10;
  border-radius: 1em;
}

.cta-item {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  z-index: 999;

  @media (max-width: 553px) {
    font-size: .8em;

    button {
      font-size: 1.5em;
    }
  }
}

.paragraph {
  color: white;
  font-size: 4em;
  text-transform: uppercase;
  font-weight: 700;
  user-select: none;
  text-align: center;

  span {
    color: var(--primary);
    font-weight: 900;
  }

  &:hover {
    b {
      transition: all .1s ease-in-out;
      opacity: 0;
    }
  }
}

.button {
  padding: 1em 2em;
  font-size: 1.2em;
  border: none;
  outline: none;
  border-radius: .5em;
  background: var(--primary);
  font-weight: 600;
  transition: all .1s ease-in-out;

  &:hover {
    background: var(--secondary);
    color: var(--primary);
    outline: 2px solid var(--primary);
    cursor: pointer;
  }
}
</style>
