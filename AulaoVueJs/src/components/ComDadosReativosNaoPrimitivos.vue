<template>
    <div class="componente">
        <h1>Componente com Dados Reativos</h1>
        <p>Nome: {{ pessoa.nome }} | idade {{ pessoa.idade }}</p>
        <button @click="fazerAniversario()">Fazer aniversário!</button>
        <button @click="mudarNome()">Mudar Nome</button>
    </div>
</template>

<!--  Metodo utilizando  a compostion api
<script setup>
import { reactive } from 'vue';

    const pessoa = reactive({nome: "Ana",  idade: 14})

    function fazerAniversario(){
        pessoa.idade += 1;
    }

    function mudarNome(){
        pessoa.nome = "Shrek"
    }
</script> -->

<script>
// Utilizando a options api
    export default{
        data:function(){
            return  {
                pessoa:{
                    nome: "Pedro",
                    idade: 12
                }
            }
        },
        methods:{
            fazerAniversario:function(){
                this.pessoa.idade += 1;
            },
            mudarNome:function(){
                this.pessoa.nome = "Eevee"
            }
        }
    }
</script>