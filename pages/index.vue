<template>
  <h1>My App</h1>

  <n-space>
    <n-button>Default</n-button>
    <n-button type="tertiary"> Tertiary </n-button>
    <n-button type="primary"> Primary </n-button>
    <n-button type="info"> Info </n-button>
    <n-button type="success"> Success </n-button>
    <n-button type="warning"> Warning </n-button>
    <n-button type="error"> Error </n-button>
  </n-space>
  <h1>
    This Project is built with:
    <li>Naive UI</li>
    <li>Nuxt</li>
    <li>Vite</li>
    <li>TypeScript</li>
    <li>Also Customized Original Naive UI Theme</li>
  </h1>
</template>

<script setup>
import { CashOutline as CashIcon } from "@vicons/ionicons5";
import { FlashOutline } from "@vicons/ionicons5";
import { NButton, NSpace, NInput, NSwitch, NIcon } from "naive-ui";
const hello = "world";
</script>
