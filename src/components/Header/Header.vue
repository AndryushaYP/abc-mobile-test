<template>
  <header class="header">
    <h1 class="header__title">Лучшие астрологи и экстрасенсы Румынии</h1>
  </header>
</template>

<script>
import "./Header.css";
export default {
  name: "Header",
  data() {
    return {
      message: this.$store.state.questions[this.$store.state.currentQuestion].text,
    };
  },
  methods: {
    handleClick() {
      this.$store.commit("currentQuestionIncrement");
      this.message = this.$store.state.questions[this.$store.state.currentQuestion].text;
    },
  },
};
</script>
