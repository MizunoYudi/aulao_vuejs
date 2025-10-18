<script setup>
  import ComDados from "./components/ComDados.vue";
import ComDadosReativosNaoPrimitivos from "./components/ComDadosReativosNaoPrimitivos.vue";
import ComDadosReativosPrimitivos from "./components/ComDadosReativosPrimitivos.vue";
import ComProps from "./components/ComProps.vue";
import DataBinding from "./components/DataBinding.vue";
import PrimeiroComponente from "./components/PrimeiroComponente.vue"
</script>

<template>
  <header>Vue</header>
  <ComDadosReativosPrimitivos></ComDadosReativosPrimitivos>
  <ComDadosReativosNaoPrimitivos></ComDadosReativosNaoPrimitivos>
  <PrimeiroComponente></PrimeiroComponente>
  <DataBinding></DataBinding>
  <ComDados></ComDados>
  <ComProps item="Cachorro" :preco=2></ComProps>
  <ComProps item="Cachor" :preco=10></ComProps>
  <ComProps item="Cacho" :preco=23432432423></ComProps>
</template>

<style scoped></style>
