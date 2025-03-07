<template>
    <h1>Meu nome é: {{ nome }}</h1>
</template>

<script>
export default {
    name:'LifeCycle',
    data() {
        return {
            nome: 'teste'
        }
    },
    created(){
        setTimeout(() => {
            this.nome = 'Bruno Desquexele'
        }, 1000);
       
    },
    mounted(){
        setTimeout(() => {
            this.nome = 'Bruno Xesquedele'
        }, 2000);
       
    }

}
</script>
