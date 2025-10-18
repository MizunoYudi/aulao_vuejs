<script setup>
  import ComDados from "./components/ComDados.vue";
import ComDadosReativosNaoPrimitivos from "./components/ComDadosReativosNaoPrimitivos.vue";
import ComDadosReativosPrimitivos from "./components/ComDadosReativosPrimitivos.vue";
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
</template>

<style scoped></style>
