<template>
  <main class="columns is-gapless is-multline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarter">
      <FormularioTarefa />
      <div class="lista">
        <TarefaCard />
        <TarefaCard />
        <TarefaCard />
        <TarefaCard />
      </div>
    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import BarraLateral from './components/BarraLateral.vue'
import FormularioTarefa from './components/FormularioTarefa.vue'
import TarefaCard from './components/TarefaCard.vue'

export default defineComponent({
  name: 'App',
  components: {
    BarraLateral,
    FormularioTarefa,
    TarefaCard
  }
});
</script>

<style>

</style>
