<template>
    <div class="box has-text-weight-bold">
        <div class="columns">
            <div class="column is-7">descrição Da Tarefa</div>
            <div class="column">
                <CronometroFormulario tempoEmSegundos="15" />
            </div>
        </div>
    </div>
</template>

<script lang="ts">

    import { defineComponent, DefineComponent } from 'vue';
    import CronometroFormulario from './CronometroFormulario.vue';

    export default defineComponent({
        name: 'TarefaCard',
        components: {
            CronometroFormulario
        }
    })

</script>