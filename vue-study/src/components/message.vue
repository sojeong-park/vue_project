<template>
  <div>
    <input type="text" v-model="message" />
    <div>{{ message }}</div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Message extends Vue {
  private message: string = '메시지를 입력해라';
}
</script>
