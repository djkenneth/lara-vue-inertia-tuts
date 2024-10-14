<template>
    <div>
        <header class="tw-bg-green-700 tw-text-white">
            <nav class="tw-flex tw-items-center tw-justify-between tw-p-4">
                <div class="tw-space-x-6">
                    <a href="/">Home</a>
                    <a href="/about">About</a>
                </div>
            </nav>
        </header>

        <main class="tw-p-4">
            <slot />
        </main>
    </div>
</template>