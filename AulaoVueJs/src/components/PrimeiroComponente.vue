<template>
    <div>
        <h1>Primeiro Componente</h1>
    </div>
</template>

<style scoped> /* Esse Scoped fará com que o estilo seja aplicado apenas a esse componente*/
    h1 {
        font-family: sans-serif;
        color: #fff;
    }
    
    div {
        background-color: violet;
        padding: 10px;
        margin: 30px;
        border-radius: 20px;
        box-shadow: 0 5px 5px #666;
        text-align: center;
        transition-duration: 1000ms;
    }

    div:hover {
        background-color: rgb(238, 64, 238);
        transition-duration: 1000ms;
    }
</style>