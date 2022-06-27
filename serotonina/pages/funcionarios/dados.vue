<template>
    <div class="container">
        <h1>Dados do funcionário</h1>
        <h4>Nome: {{ funcionario.nome }}</h4>
        <h4>Email: {{ funcionario.email }}</h4>
    </div>
</template>

<script>
export default {
    asyncData({ params }){
        const funcionario = {
            nome: params.funcionarios,
            email: params.dados
        };
        console.log(funcionario);
        return{ funcionario };
    },
}
</script>

<style scoped>
    .container{
        margin: 20px;
    }
</style>