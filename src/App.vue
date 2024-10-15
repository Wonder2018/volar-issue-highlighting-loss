<template>
    <comp-a v-for="(cell, ind) in new Array()" :key="ind"></comp-a>
    <comp-a></comp-a>
    <comp-a></comp-a>
    <comp-b></comp-b>
    <comp-b></comp-b>
    <comp-b></comp-b>
    <comp-b>
        <div>ccc</div>
    </comp-b>
    <div class="xxx">ddd</div>
</template>

<script setup lang="ts">
import CompA from "./CompA.vue";
import CompB from "./CompB.vue";
</script>
