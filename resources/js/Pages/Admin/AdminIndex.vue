<script setup>
import { Head } from '@inertiajs/vue3';
import AdminLayout from "@/Layouts/AdminLayout.vue";
</script>

<template>
    <Head title="Admin" />

    <AdminLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">Admin</h2>
        </template>

        <div class="py-4">
            <h1>Welcome Admin</h1>
        </div>
    </AdminLayout>
</template>
