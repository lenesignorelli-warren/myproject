<template>
    <div class="destaques">
      <!-- <div class="container-img"> -->
        <img width="400" height="500" alt="destaque1" src="./../assets/img-premios.png" />
      <!-- </div> -->
      <div class="container-text">
        <div class="texto1">
          <h1 class="text-h1">Finanças Femininas</h1>
          <p>Um guia completo para mulheres realizarem seus sonhos: aprenda a só gastar com o que te faz feliz,
          guardar dinheiro todos os meses e multiplicar o que foi poupado com os melhores investimentos!</p>
          <p>Um guia completo para mulheres realizarem seus sonhos: aprenda a só gastar com o que te faz feliz,
          guardar dinheiro todos os meses e multiplicar o que foi poupado com os melhores investimentos!</p>
        </div>
        <div>
          <button class="btn">Confirmar</button>
        </div>
      </div>
<!--          
    <div class="texto2">
      <h1>Aprenda a Investir</h1>
      <p>Pare de frustrar seu “eu do futuro”: conheça um novo jeito de investir!</p>
      <div>
        <img width="500" alt="destaque2" src="./../assets/capa 2.png" />
      </div>
    </div> -->
    </div>
</template>

<script>
export default {
  name: "DestaquesProject",
};
</script>

<style scoped>
.destaques {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: space-evenly;
  height: 790px;
  max-width: 1200px;
  width: 100%;
  margin: 100px auto 0 auto;
}

.container-img{
  background-color: gray;
  width: 400px;
  height: 500px;
  border-radius: 10px;
}

.container-text{
  border: 1px red;
  width: 400px;
}

.text-h1{
  margin-bottom: 100px;
}

p{
   font-weight: bold;
}

.btn {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
  margin-top: 20px;
}

</style>