<template>
    <div>
        <div v-for="persona of personas" :key="persona">
            {{persona.nombre}}
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            personas :[

                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
                {nombre : 'aleatorio'},
            ]
        }
    },
    methods: {
        getPersonas (){

    
        }
    },
}
</script>