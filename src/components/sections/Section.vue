<template>
  <section class="autob-wrap">
    <h3 class="generic-header">"This is me ↓"</h3>
    <p class="autob-wrap__text">
      I am a Junior Front-End developer who has a lot of ambition for work. I
      have been in these rivers for 2 years, during that period I learned a lot
      about this business. I am ready to sit for the junior position, but also
      to move away from it to a higher position very quickly by progressing,
      learning, practicing.
    </p>
    <h3 class="autob-wrap__exp__decsr">EXPERIENCED WITH</h3>
    <div class="autob-wrap__exp">
      <div class="autob-wrap__exp__block">
        <h4>HTML →</h4>
        <span> Writing clean code</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>CSS →</h4>
        <span>Writing clean and straightforward code</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>SASS / SCSS →</h4>
        <span>Very clean code, and perfect flow</span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>JavaScript →</h4>
        <span>Clear and clean code, with clear functions </span>
      </div>
      <div class="autob-wrap__exp__block">
        <h4>VueJS →</h4>
        <span
          >The whole flow of Vue.js is also perfectly planned and
          functional</span
        >
      </div>
    </div>
  </section>
</template>

<script></script>

<style scoped lang="scss">
.autob-wrap {
  text-align: center;
  min-height: 50vh;
  margin: 0 50px;
  margin-top: 70px;
  margin-bottom: 50px;
  &__text {
    display: flex;
    font-size: 18px;
    word-spacing: 2px;
    text-align: center;
  }
  &__exp {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    text-align: center;
    &__block {
      display: flex;
      align-items: center;
      margin: 0 50px;
    }
    &__decsr {
      font-size: 20px;
      margin-top: 50px;
      text-transform: uppercase;
      letter-spacing: 5px;
    }
  }
}
.generic-header {
  font-size: 25px;
  text-transform: uppercase;
  letter-spacing: 5px;
  text-align: center;
}
h4 {
  font-size: 22px;
  margin-right: 20px;
  color: rgba(148, 86, 35, 0.89);
}
h3 {
  color: rgba(148, 86, 35, 0.89);
}
span {
  font-size: 20px;
}
</style>
