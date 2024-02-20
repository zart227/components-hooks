<template>
  <div class="card">
    <img class="card__preview" src="../../assets/images/image01.png" alt="">
    <h2 class="card__name">{{ title }}</h2>
    <p class="card__description">
      Описание товара
    </p>
   <span class="card__price">1900 р</span>
   <button class="card__button">купить</button>
  </div>
</template>

<script>
// import { ref } from 'vue'

export default {
  name: 'CardElement',
  components: {
  },
  props: {
    title: {
      type: String,
      default: 'Имя товара'
    }
  },
  setup () {
  }
}
</script>

<style lang="scss" scoped>
.card {
  width: 350px;
  display: flex;
  flex-direction: column;
  align-items: center;
  border: 1px solid green;
  padding: 15px 20px;
}

</style>
