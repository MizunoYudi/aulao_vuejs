<template>
    <div class="componente">
        <h1>Componente com Dados Reativos</h1>
        <p>Nome: {{ nome }} | idade {{ idade }}</p>
        <button @click="fazerAniversario()">Fazer aniversário!</button>
        <button @click="mudarNome()">Mudar Nome</button>
    </div>
</template>

<script setup>
import { ref } from 'vue';

    const nome = ref("Pauo");
    const idade = ref(14);

    function fazerAniversario(){
        idade.value += 1;
    }

    function mudarNome(){
        nome.value = "Shrek"
    }
</script>