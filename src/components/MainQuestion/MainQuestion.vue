<template>
  <section class="main-question">
    <span class="main-question__prediction">Точность прогноза: 97%</span>
    <div class="main-question__image-container">
      <img src="#" alt="Изображение молящейся женщины" />
    </div>
    <h2 class="mein-question__title">
      Вас беспокоит вопрос о том, когда Вы покинете этот Мир и при каких обстоятельствах?
    </h2>
    <div class="main-question__buttons">
      <CustomButton text="Да" />
      <CustomButton text="Нет" />
    </div>
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
