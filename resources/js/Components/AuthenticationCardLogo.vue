<script setup>
import { Link } from '@inertiajs/vue3';
import Logo from './Logo.vue'
</script>

<template>
    <a :href="'/login'">
      <Logo :width="250" :height="100"/>
    </a>
</template>