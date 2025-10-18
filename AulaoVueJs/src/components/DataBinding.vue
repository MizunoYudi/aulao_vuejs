<template>
    <div class="componente">
        <h1>Componente com Data DataBinding</h1>
        <p>{{ valor }}</p>
        <!-- <input type="text" :value="valor"> Binding simples, unidirecional -->

        <!-- <input type="text" :value="valor" v-on:input="(e)=>valor =  e.target.value"> TwoWayBinding manual -->

        <input type="text" v-model="valor"><!-- TwoWayBinding-->
    </div>
</template>

<script setup>
    import { ref } from "vue"

    const valor = ref("Um valor ai");
</script>