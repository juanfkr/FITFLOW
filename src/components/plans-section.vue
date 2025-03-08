<template>
  <section class="plans-wrapper">
    <div class="plan-item">
      <div class="header-plan">
        <h3>Básico</h3>
        <img src="../assets/icons/plan-icon.png" alt="">
        <h3>
          <span>R$</span>49,90<span>/mês</span>
        </h3>
      </div>
      <ul class="befenits-wrapper">
        <li>3 treinos personalizados por semana</li>
        <li>1 plano alimentar por mês</li>
        <li>Aulas pré-gravadas</li>
        <li>Suporte especializado</li>
        <li>Acesso a comunidade</li>
      </ul>
      <button class="button">Adquirir</button>
    </div>

    <div class="plan-item">
      <div class="header-plan">
        <h3>Intermediário</h3>
        <img src="../assets/icons/plan-icon.png" alt="">
        <h3>
          <span>R$</span>49,90<span>/mês</span>
        </h3>
      </div>
      <ul class="befenits-wrapper">
        <li>3 treinos personalizados por semana</li>
        <li>1 plano alimentar por mês</li>
        <li>Aulas pré-gravadas</li>
        <li>Suporte especializado</li>
        <li>Acesso a comunidade</li>
      </ul>
      <button class="button">Adquirir</button>
    </div>

    <div class="plan-item">
      <div class="header-plan">
        <h3>Avançado</h3>
        <img src="../assets/icons/plan-icon.png" alt="">
        <h3>
          <span>R$</span>49,90<span>/mês</span>
        </h3>
      </div>
      <ul class="befenits-wrapper">
        <li>3 treinos personalizados por semana</li>
        <li>1 plano alimentar por mês</li>
        <li>Aulas pré-gravadas</li>
        <li>Suporte especializado</li>
        <li>Acesso a comunidade</li>
      </ul>
      <button class="button">Adquirir</button>
    </div>
  </section>
</template>

<script setup>

</script>

<style scoped>
.plans-wrapper {
  color: white;
  width: 100%;
  justify-content: center;
  gap: 2em;
  display: flex;
  flex-wrap: wrap;
  margin: 4em 0;
}

.plan-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  background: var(--secondary);
  border-radius: 1em;
  padding: 1em;
  width: 320px;
  height: 430px;
  transition: all .1s ease-in-out;

  &:hover {
    outline: 2px solid var(--primary);
  }

  h2 {
    font-size: 2em;
  }

  h3 {
    font-size: 2em;
    font-weight: 800;
    color: var(--primary);

    span {
      font-size: .5em;
      color: white;
      font-weight: 500;
    }
  }

  .header-plan {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  ul {
    display: flex;
    width: 100%;
    flex-direction: column;
    gap: .5em;
    padding: 0 2em;
    user-select: none;
  }
}


.button {
  width: 100%;
  padding: .5em;
  font-size: 1.2em;
  border-radius: .5em;
  border: none;
  background: var(--primary);
  font-weight: 600;
  transition: all .1s ease-in-out;

  &:hover {
    scale: 1.05;
  }
}
</style>
