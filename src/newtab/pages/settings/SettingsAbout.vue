<template>
  <div class="max-w-lg">
    <div class="bg-box-transparent mb-2 inline-block rounded-full p-3">
      <img src="@/assets/svg/logo.svg" class="w-14" />
    </div>
    <p class="text-2xl font-semibold">Metis</p>
    <p class="mb-2 mt-1">Version: {{ extensionVersion }}</p>
    <p class="text-gray-600 dark:text-gray-200">
      Metis is an ultra-stealth browser automation and web workflow execution engine.
      Perform end-to-end task flows, DOM scraping, form orchestration, and automated pipelines directly in your browser.
    </p>
    <div class="mt-4 space-x-2">
      <a
        v-for="link in links"
        :key="link.name"
        v-tooltip.group="link.name"
        :href="link.url"
        target="_blank"
        class="hoverable inline-block rounded-lg p-2 transition"
      >
        <v-remixicon :name="link.icon" />
      </a>
    </div>
    <div class="my-8 border-b dark:border-gray-700"></div>
    <div class="p-4 rounded-xl border border-gray-200 dark:border-gray-700 bg-gray-50 dark:bg-gray-800">
      <h2 class="text-lg font-semibold text-gray-900 dark:text-white">Developer & Maintainer</h2>
      <p class="text-xl font-bold text-primary mt-1">Akash Jadon</p>
      <p class="text-sm text-gray-600 dark:text-gray-300 mt-1">
        Specializing in autonomous agent architecture, browser stealth automation, and high-throughput pipelines.
      </p>
      <a
        href="https://www.linkedin.com/in/akashjadon"
        target="_blank"
        rel="noopener noreferrer"
        class="inline-block mt-3 text-sm font-medium text-primary hover:underline"
      >
        View LinkedIn Profile &rarr;
      </a>
    </div>
  </div>
</template>
<script setup>
import { useGroupTooltip } from '@/composable/groupTooltip';
import browser from 'webextension-polyfill';

useGroupTooltip();

const extensionVersion = browser.runtime.getManifest().version;
const links = [
  {
    name: 'Developer Profile',
    icon: 'riLinkedinBoxFill',
    url: 'https://www.linkedin.com/in/akashjadon',
  },
  {
    name: 'GitHub',
    icon: 'riGithubFill',
    url: 'https://github.com/akashjadon04',
  },
];
</script>
