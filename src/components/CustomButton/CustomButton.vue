<template>
  <button class="button">{{ text }}</button>
</template>

<script>
import "./CustomButton.css";
export default {
  name: "MainQuestion",
  props: ["text"],
};
</script>
