<script setup>
    import { Link } from '@inertiajs/vue3';
</script>

<template>
    <div>
        <header class="tw-bg-red-700 tw-text-white">
            <nav class="tw-flex tw-items-center tw-justify-between tw-p-4">
                <div class="tw-space-x-6">
                    <Link href="/">Home</Link>
                    <Link href="/about">About</Link>
                </div>
            </nav>
        </header>

        <main class="tw-p-4">
            <slot></slot>
        </main>
    </div>
</template>