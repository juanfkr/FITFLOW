<template>
  <section id="feedback">
    <ul class="feedback-wrapper">
      <li class="feedback-item">
        <img src="../assets/icons/user-icon.png" alt="">
        <div>
          <p>Mary Hamsworth</p>
          <p>"Lorem, ipsum dolor sit natus in expedita numquam.""</p>
        </div>
      </li>
      <li class="feedback-item">
        <img src="../assets/icons/user-icon.png" alt="">
        <div>
          <p>Mary Hamsworth</p>
          <p>"Lorem, ipsum dolor sit natus in expedita numquam.""</p>
        </div>
      </li>
      <li class="feedback-item">
        <img src="../assets/icons/user-icon.png" alt="">
        <div>
          <p>Mary Hamsworth</p>
          <p>"Lorem, ipsum dolor sit natus in expedita numquam.""</p>
        </div>
      </li>
      <li class="feedback-item">
        <img src="../assets/icons/user-icon.png" alt="">
        <div>
          <p>Mary Hamsworth</p>
          <p>"Lorem, ipsum dolor sit natus in expedita numquam.""</p>
        </div>
      </li>
    </ul>
  </section>
</template>

<script setup>

</script>

<style scoped>
.feedback-wrapper {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;

  @media (max-width: 1464px) {
    justify-content: center;
    gap: 1em;
  }
}

.feedback-item {
  display: flex;
  gap: .5em;
  color: white;
  width: 350px;
  background: var(--secondary);
  padding: .5em;
  border-radius: .5em;
  outline: 2px solid var(--primary);

}
</style>
