<template>
    <p >
        <slot>
            {{ message }}
        </slot>
    </p>
</template>
<script setup lang="ts">
defineProps<{
    message?: string;
}>();
</script>
