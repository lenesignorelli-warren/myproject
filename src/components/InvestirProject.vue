<template>
  <div>
    <div class="investir">
      <h2>Investir é sobre você</h2>
      <p>COMECE A INVESTIR EM POUCOS MINUTOS. DESCOMPLIQUE.</p>
      <button>BUTTON</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "InvestirProject",
};
</script>

<style scoped>
.investir {
  background-color: #dddddd;
  height: 200px;
  width: 100%;
  text-align: left;
  color: white;
  padding: 20px;
}

h2 {
  font-size: 64px;
  font-family: Arial, sans-serif;
  margin-left: 5%;
  margin-top: 3%;
}

 p {
  font-size: 30;
  margin-left: 5%;
  font-family: Arial, sans-serif;
}

button {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
}
</style>