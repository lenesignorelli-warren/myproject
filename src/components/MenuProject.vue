<template>
  <nav class="nav-container">
    <ul>
      <li><img width="80" alt="Logo" src="./../assets/logo2.png" /></li>
      <li><a href>Menu1</a></li>
      <li><a href>Menu2</a></li>
      <li><a href>SubMenu1</a></li>
      <li><a href>Menu3</a></li>
      <li><a href>Menu4</a></li>
      <li><a href>Menu5</a></li>
      <li><button>BUTTON</button></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "MenuProject",
};
</script>

<style scoped>
.nav-container {
  background-color: #dddddd;
  font-family: Arial, sans-serif;
  font-weight: bold;
  text-align: center;
  width: 100%;
  padding: 10px;
}

li {
  display: inline;
  margin: 0 30px;
}

li a {
  color: white;
  text-align: center;
  text-decoration: none;
}

button {
  border-radius: 50px;
  color: white;
  background: black;
  padding: 10px;
  font-weight: bold;
}

.dropdown-content {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  background-color: #f1f1f1;
  display: none;
  text-align: left;
}
</style>