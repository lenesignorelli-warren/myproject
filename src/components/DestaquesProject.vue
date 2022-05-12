<template>
  <div>
    <div class="container">
      <img width=400 alt="destaque1" src="./../assets/img-premios.png">
      <h1>Finanças Femininas</h1>
      <h3>Um guia completo para mulheres <br>realizarem seus sonhos: 
        <br>aprenda a só gastar com o que te faz feliz, 
        <br>guardar dinheiro todos os meses e multiplicar 
        <br>o que foi poupado com os melhores investimentos!</h3>
        <button>BUTTON</button>
      <h1><br>Aprenda a Investir
      <br>
        <br>Pare de frustrar
        <br>o seu “eu do futuro”:
        <br>conheça um novo jeito
        <br>de investir!</h1>
      <img width=450 alt="destaque2" src="./../assets/capa 2.png">
    </div>
  </div>
</template>

<script>
export default {
    name: 'DestaquesProject'
}
</script>

<style scoped>
.container{
  display: inline-flex;
  flex-direction: row;
  flex-wrap: wrap;
  align-content: space-around;
  justify-content: space-between;
  align-items: center;
  font-family: Arial, Helvetica;
} 

.button{
  border-radius: 50px;
   color: white;
   background: black;
   padding: 10px ;
   font-weight: bold;
   margin-left: 5%;
}
</style>