<script setup lang="ts">
import { NCard, NForm, NFormItem, NInput, NIcon } from 'naive-ui'
import { DocumentText } from '@vicons/ionicons5'
const textInput = ref('')
</script>

<template>
  <div>
    <h1 text-red-600>
      Hola
    </h1>
    <n-icon>
      <document-text />
    </n-icon>
    <n-card embedded>
      <n-form>
        <n-form-item label="Introduce the travel information">
          <n-input v-model:value="textInput" type="text" placeholder="Basic Input" />
        </n-form-item>
      </n-form>
    </n-card>
  </div>
</template>
