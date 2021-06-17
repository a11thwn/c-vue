<template>
  <h3>{{ name }}</h3>
</template>

<script>
export default {
  data() {
    return {
      name: '宁皓网',
      menuItems: ['首页', '热门', '发布'],
      currentItem: 0,
    };
  },
};
</script>

<style>
@import './styles/app.css';
</style>
