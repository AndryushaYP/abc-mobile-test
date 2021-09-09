<template>
  <section class="main-question">
    <span class="main-question__prediction">Точность прогноза: 97%</span>
    <div class="main-question__image-container">
      <img src="../../assets/girl.png" alt="" class="main-question__image" />
    </div>
    <h2 class="main-question__title">
      Вас беспокоит вопрос о том,<br />
      <strong class="main-question__title main-question__title_strong">
        когда Вы покинете этот Мир и при<br />
        каких обстоятельствах?
      </strong>
    </h2>
    <div class="main-question__buttons">
      <CustomButton text="Да" />
      <CustomButton text="Нет" />
    </div>
    <span class="main-question__span">Онлайн предсказание</span>
  </section>
</template>

<script>
import CustomButton from "@/components/CustomButton/CustomButton.vue";

import "./MainQuestion.css";
export default {
  name: "MainQuestion",
  components: { CustomButton },
};
</script>
