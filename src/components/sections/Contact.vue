<template>
  <section class="contact-wrap">
    <div class="contact-wrap__text">
      <h2 class="section-header">
        <span>Questions? </span>
        <span>Explanations?</span>
        <br />
        <span>The Business?</span>
        <br />
        <span>Feel free to contact me!</span>
      </h2>
      <button
        type="button"
        class="cta-header"
        id="contactCta"
        @click.prevent="toggleModal"
      >
        Contact me!
      </button>
    </div>

    <Modal v-if="isVisibility" />
  </section>
</template>

<script>
import Modal from '../modals/Modal.vue'
export default {
  components: {
    Modal
  },
  data () {
    return {
      isVisibility: false
    }
  },
  methods: {
    toggleModal () {
      this.isVisibility = !this.isVisibility
    }
  }
}
</script>

<style scoped lang="scss">
.contact-wrap {
  background-image: linear-gradient(
      to bottom,
      rgba(0, 0, 0, 0.25),
      rgba(0, 0, 0, 0.2)
    ),
    url(../../images/contactpic.jpg);
  background-position: center;
  background-size: cover;
  position: relative;
  min-height: 60vh;
  z-index: 2;
  &__text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
.section-header {
  color: #fff;
  font-size: 25px;
  font-weight: 300;
  text-align: center;
  text-transform: uppercase;
  letter-spacing: 10px;
}
.cta-header {
  background: none;
  border: 2px solid #fff;
  border-radius: 50px;
  color: #fff;
  cursor: pointer;
  font-size: 15px;
  font-weight: bold;
  padding: 9px 35px;
  letter-spacing: 2px;
}
a {
  color: #fff;
}
span {
  font-weight: bold;
}
</style>
