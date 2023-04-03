<template>
  <v-container>
    TEST {{ test }}
    <v-btn @click="add">ADD</v-btn>
  </v-container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data() {
    return {
      test: 1
    }
  },
  methods: {
    add() {
      this.test += 1;
    }
  }
})
</script>
