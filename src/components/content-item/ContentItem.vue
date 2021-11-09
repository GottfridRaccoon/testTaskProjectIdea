<template>
  <div class="content-item-wrapper">
    <img src="../../img/photo.png" class="content-item__img" />
    <h3 class="content-item__h3">{{ title }}</h3>
    <p class="content-item__p">{{ description }}</p>
    <h2 class="content-item__h2">{{ price }}</h2>
  </div>
</template>

<script>
export default {
  name: "ContentItem",
  props: {
    price: String,
    title: String,
    description: String,
  },
};
</script>

<style lang="scss" scoped>
@import "./ContentItem.scss";
</style>