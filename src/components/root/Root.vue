<template>
  <div class="root">
    <Header></Header>
    <div class="root-content">
      <Form></Form>
    <Content></Content>
    </div>
    
  </div>
</template>

<script>
import Header from "@/components/header/Header.vue";
import Form from "@/components/form/Form.vue";
import Content from "@/components/content/Content.vue";

export default {
  name: "Root",
  components: {
    Header,
    Form,
    Content,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "./Root.scss";
</style>
