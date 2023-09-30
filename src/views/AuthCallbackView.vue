<script setup lang="ts">
import router from '@/router';
import { onMounted } from 'vue'
import type { User } from 'oidc-client-ts';
import AuthService from '@/services/AuthService';

onMounted(() => {
    AuthService.userManager.signinRedirectCallback().then(
        async (user: User) => {
            console.info("User ::", user);
            router.push({ path: 'home' })
        },
        (error) => {
            console.error("Error ::", error);
        }
    );
})
</script>

<template>
    <p>Please wait...</p>
</template>
