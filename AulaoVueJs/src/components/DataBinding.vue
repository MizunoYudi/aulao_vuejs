<template>
    <div class="componente">
        <h1>Componente com Data DataBinding</h1>
        <input type="text" :value="valor">
    </div>
</template>

<script setup>
    import { ref } from "vue"

    const valor = ref("Um valor ai");
</script>