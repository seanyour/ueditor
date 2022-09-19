<template>
  <vue-ueditor-wrap v-model="data" :config="editorConfig"></vue-ueditor-wrap>
</template>

<script setup lang="ts">
import {ref} from "vue";

const data = ref('');
const editorConfig = ref({
  UEDITOR_HOME_URL: './public/UEditor/',
  serverUrl: '',
  theme: 'gray',
  initialFrameHeight: 450,
  initialFrameWidth: 900,
});
</script>