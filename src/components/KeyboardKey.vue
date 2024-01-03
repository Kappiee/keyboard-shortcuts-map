<template>
    <div class="key" style="width: {keyWidth};">
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
    keyWidth: Number,
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