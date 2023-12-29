<template>
    <div class="key">
        {{keyName}}
    </div>
</template>
<script lang="ts">
export default {
    name: "KeyWorld",
}
</script>
<script setup lang="ts">
defineProps({
    keyName: String,
    keyOrigin: String,
})
</script>

<style scoped>
.key {
    width: 50px;
    height: 50px;
    border: #000 1px solid;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: 700;
}
</style>