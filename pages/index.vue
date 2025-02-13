<script setup lang="ts">
const items = [1, 2, 3, 4, 5];
</script>

<template>
    <div class="p-4">
        <div class="grid grid-cols-4 gap-4">
            <MenuCard v-for="item in items" />
        </div>
    </div>
</template>
