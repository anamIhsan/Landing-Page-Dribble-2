<script setup>
    import Grid from './sections/Grid.vue'
</script>

<template>
    <section class="grid grid-cols-12 mt-20">
        <div class="col-span-6">
            <h1 class="font-bold text-4xl w-72 leading-tight">
            What we are
            offering
            </h1>
            <h2 class="font-normal text-2xl text-gray-900 py-5">
            Property facilities
            </h2>
            <p class="w-72 text-gray-500">
            We have 5000+ Reviews and our
            Customers trust on our Quality product
            and trust own our product.
            </p>
        </div>

        <Grid title="Gym" bg>
            <i class="text-gray-700 fas fa-dumbbell"></i>
        </Grid>

        <Grid title="Parking">
            <i class="text-gray-700 fas fa-parking"></i>
        </Grid>

        <div class="col-span-3 p-20 flex items-center">
            <div class="bg-gray-700 m-auto rounded-full w-14 h-14 text-white flex items-center justify-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7l5 5m0 0l-5 5m5-5H6" />
                </svg>
            </div>
        </div>

        <Grid title="Fireplace" bg>
            <i class="text-gray-700 fas fa-utensils"></i>
        </Grid>

        <Grid title="Swimming pool" text>
            <i class="text-gray-700 fas fa-swimmer"></i>
        </Grid>

        <Grid title="Internet" bg>
            <i class="text-gray-700 fas fa-wifi"></i>
        </Grid>
    </section>
</template>