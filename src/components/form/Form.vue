<template>
  <div class="form-wrapper">
    <form class="form__contact">
      <label class="form__label" for="order-name">Наименование товара</label>
      <svg
        width="4"
        height="8"
        viewBox="0 2 4 4"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect width="4" height="4" rx="2" fill="#FF8484" />
      </svg>
      <input
        class="form__input"
        id="order-name"
        type="text"
        value="Введите наименование товара"
      />

      <label class="form__label" for="order-name">Описание товара </label>
      <textarea class="form__textarea"> Введите описание товара</textarea>
      <label class="form__label" for="link-order"
        >Ссылка на изображение товара</label
      >
      <svg
        width="4"
        height="8"
        viewBox="0 2 4 4"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect width="4" height="4" rx="2" fill="#FF8484" />
      </svg>
      <input
        class="form__input"
        type="text"
        id="link-order"
        value="Введите ссылку"
      />
      <label class="form__label" for="order-price">Цена товара</label>
      <svg
        width="4"
        height="8"
        viewBox="0 2 4 4"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <rect width="4" height="4" rx="2" fill="#FF8484" />
      </svg>
      <input
        class="form__input"
        type="text"
        id="order-price"
        value="Введите цену"
      />
      <button type="submit" class="form__submit">Добавить товар</button>
    </form>
  </div>
</template>
<script>
export default {
  name: "Form",
};
</script>

<style scoped lang = "scss" >
@import "./Form.scss";
</style>