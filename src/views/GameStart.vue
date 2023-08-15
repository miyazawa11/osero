<script setup>
import {routerLink} from "vue-router"
</script>

<template>
    <h1>オセロゲーム</h1>
    <button><router-link to="{/game}">開始</router-link></button>
</template>