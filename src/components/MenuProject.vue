<template>
<div class="menu">
    <ul>
    <li><img width="40" alt="Logo" src="./../assets/LOGO-WARREN.jpeg"></li>
    <li><a href>Menu 1</a></li>
    <li><a href>Menu 2</a></li>
    <li><a href>Menu 3</a></li>
    <li><a href>Menu 4</a></li>
    <li><a href>Menu 5</a></li>
    <li><input type="button" value="BUTTON"></li>
    </ul>
</div>
</template>

<script>
export default {
    name: 'MenuProject'
}
</script>

<style scoped>

.menu{
    /* position: left; */
    /* justify-content: space-between; */
    background-color: #dddddd;
    padding: 10px;
}
/* ul{
    margin-left: 0px;
    
} */

li{
    display: inline;
    padding: 30px;
    
    
}

li a{
    color: white;
    text-align: center;
    text-decoration: none;
    border-radius: 12px;
}

    

</style>