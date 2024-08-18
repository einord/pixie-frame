<script setup lang="ts">

</script>

<template>
<div class="frame">
    <img src="https://picsum.photos/1000/700" />
</div>
</template>

<style scoped>
.frame {
    width: 100%;
    height: 100%;
    background-color: pink;

    > img {
        width: 100%;
        height: 100%;
        object-fit: cover;        
    }
}
</style>