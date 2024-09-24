<script setup>
import Card from "./Card.vue";
import KanbanBoard from "./components/KanbanBoard.vue";
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'

// initialize components based on data attribute selectors
onMounted(() => {
    initFlowbite();
})
</script>
<template>
 <KanbanBoard/>

</template>
