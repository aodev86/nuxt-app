<script setup>
const route = useRoute()
</script>

<template>
    {{ route.params.id }}番目の投稿だよ
</template>

