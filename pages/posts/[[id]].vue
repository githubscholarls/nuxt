<template>
    <div>
        <h2>post content</h2>
        <!-- <p>this.route.params.id  : {{ this.$route.params.id }}</p> -->
    </div>
</template>

<script setup lang="ts">
    const route=  useRoute()

    console.log('id',route.params.id)
</script>
