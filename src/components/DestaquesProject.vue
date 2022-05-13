<template>
  <main>
    <div class="center">
      <div>
        <img
          width="400"
          height="500"
          alt="destaque1"
          src="./../assets/img-premios.png"
        />
      </div>
      <div class="containert-text">
        <h1>Finanças Femininas</h1>
        <h4>Um guia completo para mulheres</h4>
        <h4>realizarem seus sonhos:</h4>
        <h4>aprenda a só gastar com o que te faz feliz,</h4>
        <h4>guardar dinheiro todos os meses e multiplicar</h4>
        <h4>o que foi poupado com os melhores investimentos!</h4>
        <input type="button" value="BUTTON" />
      </div>
    </div>

    <div class="containert-text">
      <h1>Aprenda a Investir</h1>
      <h4>Pare de frustrar</h4>
      <h4>seu “eu do futuro”:</h4>
      <h4>conheça um novo jeito</h4>
      <h4>de investir!</h4>
      <div>
        <div class="center">
          <img width="500" alt="destaque2" src="./../assets/capa 2.png" />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "DestaquesProject",
};
</script>

<style scoped>
.container {
  display: flex;
  flex-flow: row wrap;
  align-content: space-between;
  justify-content: space-between;
  align-items: center;
  font-family: Arial, Helvetica;
  max-width: 300px;
  height: 300px;
}

.input {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
}

main {
  display: flex;
  align-items: center;
  /* max-width: 300px;
  height: 300px; */
}

.center {
  margin: 0px auto;
  display: flex;
  justify-content: space-between;
  flex-flow: row wrap;
}
</style>