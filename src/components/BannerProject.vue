<template>
  <div>
    <div class="principal">
      <div>
        <h1>
          Lorem ipsum dolor sit amet,<br />
          consectetur adipiscing elit.br <br />
          consectetur adipiscing elit.
        </h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <br />
        <button>BUTTON</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BannerProject",
};
</script>

<style scoped>
.principal {
  background-color: #e02b57;
  height: 470px;
  width: 100%;
  text-align: left;
  color: white;
}

h1 {
  font-size: 64px;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  margin-left: 5%;
  margin-top: 3%;
}

p {
  font-size: 30px;
  margin-left: 5%;
}

button {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
  margin-left: 5%;
}
</style>