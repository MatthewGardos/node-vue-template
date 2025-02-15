<script setup>
import { RouterLink } from 'vue-router';
import UiBtn from "../components/ui/btn.vue";
</script>
<template>
    <div>
        <h1>Homepage</h1>
        <RouterLink to="/about">
            <UiBtn>
                About Page
            </UiBtn>
        </RouterLink>
    </div>
</template>