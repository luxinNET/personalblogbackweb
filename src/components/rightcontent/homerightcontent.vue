<template>
      <li>{{msg}}</li>
</template>

<script>
export default {
  name: 'msg',
  props: {
    icon: {
      type: Object,
      required: false
    }
  }
}
</script>

<style>
 li {
  background-color: red;
  margin-top: 20px;
}
</style>
