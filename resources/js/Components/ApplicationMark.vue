<template>
    <Logo :width="width" :height="height"/>
</template>

<script setup>
import Logo from "./Logo.vue";

const props = defineProps({
    width: {
        type: Number,
        default: 900,
    },
    height: {
        type: Number,
        default: 720,
    }
});
</script>
