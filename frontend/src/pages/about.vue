<script setup>
import { RouterLink } from 'vue-router';
import UiBtn from "../components/ui/btn.vue";
</script>
<template>
    <div>
        <h1>About</h1>
        <RouterLink to="/">
            <UiBtn>
                Homepage
            </UiBtn>
        </RouterLink>
    </div>
</template>