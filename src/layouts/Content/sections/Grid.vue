<script setup>
    const props = defineProps ({
        title: String,
        text: Boolean,
        bg: Boolean,
    })
</script>

<template>
    <div 
        class="col-span-3 p-20"
        :class="bg
            ? 'bg-[#e7ecf8]'
            : 'shadow-lg'
        "
    >
        <span class="text-[80px] flex flex-col items-center space-y-8">

            <!-- Text & Icon -->
            <slot />
            <p 
                class="font-bold text-lg"
                :class="text 
                ? 'w-48 text-center'
                : ''
            "
            
            >
                {{ title }}
            </p> 
            <!-- End Text & Icon -->
        </span>
    </div>
</template>