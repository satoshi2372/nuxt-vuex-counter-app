<template>
  <div class="container">
    <div>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
      <Counter></Counter>
      <hr>
    </div>
  </div>
</template>

<script>
// nuxtでコンポーネント使用の際の記述方法
import Counter from '~/components/Counter.vue'
export default {
  components: {
    Counter
  }
}
</script>
