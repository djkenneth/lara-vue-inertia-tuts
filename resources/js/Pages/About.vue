<script setup>
    import NoLayout from '@/Layouts/NoLayout.vue';

    defineOptions({ layout: NoLayout })

    defineProps({
        description: String
    })
</script>

<template>
    <div>
        <h2 class="">About Us Page</h2>
        <p>{{ description }}</p>
    </div>
</template>