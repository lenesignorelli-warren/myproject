<template>
<div>
  <div class="principal">
    <h1>Lorem ipsum dolor<br/> sit, consectetur<br /> adipiscing elit.<br /></h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    <button>BUTTON</button>
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
  padding: 70px;
}

h1 {
  font-size: 64px;
  margin-left: 5%;
  font-family: Arial, sans-serif;
}

p {
  font-size: 30px;
  margin-left: 5%;
  margin-top: 30px;
  font-family: Arial, sans-serif;
}

button {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
  margin-left: 5%;
  margin-top: 20px;
  font-family: Arial, sans-serif;
}
</style>