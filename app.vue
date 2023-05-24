<template>
  <n-config-provider :theme-overrides="themeOverrides">
    <NuxtPage />
  </n-config-provider>
</template>
<script setup>
import { NConfigProvider } from "naive-ui";
import { themeOverrides } from "./themeOverrides.ts";
</script>
