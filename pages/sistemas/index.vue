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
                    <router-link to="/"  class="btn" >OK</router-link>
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
                    <router-link to="/"  class="btn">OK</router-link>
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
    background-color: #E8E6E6;
}

.cards {
    padding: 20px;
    width: auto;
    
    #card {
      height: 369px;
      width: 300px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background-color: #F4F4F4;

      img{
          height: 250px;
          width: 300px;
      }
    }

    .card-body {
      margin-top: 20px;
      text-align: center;
    }

    .btn-sistemas{
        height: 40px;
        width: 250px;
        background-color: #EC1C24;
        position: relative;
        margin-left: auto;
        margin-right: auto;
        margin-top: 15px;
        margin-bottom: 15px;
        align-items: center !important;

        .btn{
            background-color: #EC1C24;
            color: white;
            text-decoration: none;
            font-size: 18px;

        }
    }
}
</style>