<template>
    <div class="container">
        <div class="cards">
            <div class="card-body" id="card">
                <h1 class="card-img">
                    <img src="@/static/ps.png">
                </h1>
                <p class="card-text">
                    Sistema de pesquisa de satisfação dos alunos e professores sobre o senai
                </p>
                <div class="btn-sistemas">
                    <router-link to="/">OK</router-link>
                </div>
            </div>

            <div class="card-body" id="card">
                <h1 class="card-img">
                    <img src="@/static/fiap.png">
                </h1>
                <p class="card-text">
                    Formulario FIAP para declarar alunos com baixo desempenho
                </p>
                <div class="btn-sistemas">
                    <router-link to="/">OK</router-link>
                </div>
            </div>
        </div>
    </div>

</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.body {
    padding: 60px 80px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.container{
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
}

.cards {
    padding: 20px;
    width: auto;

    #card {
      height: 250px;
      width: 250px;
      border: 1px solid;
      border-radius: 25px;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .card-body {
      margin-top: 20px;
      text-align: center;
    }
}
</style>