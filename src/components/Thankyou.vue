<template>
    <div class="container">
      <img src="../assets/thanks.png">
       <h1>FOR YOUR VALUEABLE PRODUCT!!</h1>
       <router-link to='/'><button name="logout" class="logout">LOGOUT</button></router-link>
    </div>
</template>
<script>
export default {
}
</script>
<style >

.container {
  margin: 40px;
  position: relative;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px 10px 30px 10px;
  justify-content: center;
}
.logout{
  padding: 12px;
  border: none;
  border-radius: 4px;
  margin: 5px 0;
  opacity: 0.85;
  display: inline-block;
  font-size: 17px;
  line-height: 20px;
  background-color: rgb(98, 203, 245);
  color: white;
  cursor: pointer;
  width: 40%;
}
.logout:hover{
  background-color: #0569c7;
}

</style>
