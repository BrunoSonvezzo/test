<template>
    <div>
        <h2>Esta e a descricao da pessoa: {{ nome }}</h2>
        <info/>
        <Form/>
    </div>
</template>
<script>
import Form from './Form.vue';
import info from './info.vue'
    export default {
        name: 'Pessoa',
        components:{
           info,
           Form
        },
        data(){
            return{
                nome: 'Raphaela'
            }
        }
    }
</script>