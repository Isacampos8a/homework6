<script setup>
import useScore from '@/composables/useScore';
const { score } = useScore()
    
</script>

<template>
    <span class="">Main score: {{ score }}</span>
</template>