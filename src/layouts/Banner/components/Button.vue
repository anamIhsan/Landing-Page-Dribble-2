<script setup>
    const props = defineProps ({
        title: String,
        bg: Boolean,
    })
</script>

<template>
    <button 
        class="text-white text-sm font-medium px-8 py-2"
        :class="
            bg
            ? 'bg-gray-800'
            : 'border border-white'
        "
    >
        {{ title }}
    </button>
</template>