<script setup lang="ts">
    console.log("share button loaded")
</script>

<template>
    <div :style="{border: '1px solid pink', padding: '10px', display: 'inline-block'}">
        <slot></slot>
    </div>
</template>
