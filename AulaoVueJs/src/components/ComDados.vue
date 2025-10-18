<template>
    <div class="componente">
        <h1>Componente com dados</h1>
        <p>Nome: {{ nomeProduto }} - {{ codigo }}</p>
    </div>
</template>

<script setup>
    const nomeProduto = "Lápis";
    const codigo = "789"

</script>

<!-- <script>
// Usando components API
// export default {
//     data: function(){
//         return {
//             nomeProduto: "Caderno",
//             codigo: "#321"
//         };
//     }
// }

// Usando composition API
// Método "Incomum"
// export default{
//     setup:function(){
//         const nomeProduto = "Lápis";
//         const codigo = "789"
//         return {nomeProduto, codigo};
//     }
// }

</script> -->