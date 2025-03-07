<template>
    <div>
        <h1>Primeiro Componente</h1>
        <p>Olá, meu nome e {{ nome }} e trabalho como {{ profissao }}</p>
    </div>
</template>

<script>
    export default {
        name: 'PrimeiroComponente',
        data() {
            return {
                nome: "Bruno",
                profissao: "Desenvolvedor Front-end Jr I"
            }
        }	
    }
</script>