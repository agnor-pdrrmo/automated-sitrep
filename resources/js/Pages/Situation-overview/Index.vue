<script setup>
import BreezeAuthenticatedLayout from '@/Layouts/Authenticated.vue';
import { Head } from '@inertiajs/inertia-vue3';
</script>

<template>
  <Head title="Situational Overview" />
  <BreezeAuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Situational Overview
            </h2>
        </template>

        <p>This is situation overview</p>
    </BreezeAuthenticatedLayout>
</template>
