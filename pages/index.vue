<template>
  <q-page class="q-pl-lg">
    <p class="text-h6 q-pt-md">
      Plugin Showcase
    </p>
    <q-list>
      <q-item
        v-for="(button, idx) in buttons"
        :key="idx"
      >
        <q-btn
          v-bind="button"
        />
      </q-item>
    </q-list>
    <p class="text-h6 q-pt-md">
      Directive Showcase
    </p>
    <example-list />
    <p class="text-h6 q-pt-md">
      Quasar Default Prop Values
    </p>
    <prop-defaults />
  </q-page>
</template>

<script setup lang="ts">
</script>

