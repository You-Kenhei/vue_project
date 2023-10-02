<template>
  <div>
    <!-- <h1>{{ message }}</h1> -->
    <!-- <element-view></element-view> -->

    <emp-view></emp-view>
  </div>
</template>

<script>
import EmpView from './views/tlias/EmpView.vue';
// import ElementView from './views/element/ElementView.vue';

export default {
  components: { /* ElementView, */EmpView },
  data () {
    return {
      message:"Hello Vue"
    }
  },
  methods: {

  }
};
</script>

<style>
</style>
