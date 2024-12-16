<script>
import Input from './components/icons/input.vue';
import Selector from './components/selector.vue'
export default{
  components:{ Input,Selector }
}

</script>

<template>
<h1>CRYPTO</h1>

<Input />
<div className="Selectors">
  <Selector />
  <Selector />
</div>
</template>

<style scoped>
.Selectors{
  display: flex;
  justify-content: space-around;
  width: 700px;
  margin: 0 auto;
}
</style>
