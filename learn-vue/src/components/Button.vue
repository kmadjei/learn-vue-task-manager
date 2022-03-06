<template>
    <button 
        class="btn"
        :style="{ background: color}"
        @click="onClick()"
    >
        Add Task
    </button>
</template>

<script>
    export default {
        name: 'Button',
        props: {
            text: String,
            color: String
        },
    }
</script>