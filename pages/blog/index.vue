<template>
    <div>
        <h1>hello from the blog</h1>
    </div>
</template>

<script setup>
    const result = await queryContent('/').find()

    console.log(result)
</script>

<style lang="scss" scoped>

</style>