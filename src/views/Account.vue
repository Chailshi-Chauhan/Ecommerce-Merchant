<template>
<div>
    <h2 style="text-align:center">Merchant Profile Card</h2>
<div class="card">
  <img src="../assets/profile3.jpeg" alt="name" style="width:100%">
  <p class="title">NAME: </p>
  <p class="title">EMAIL: </p>
  <p class="title">CONTACT NUMBER: </p>
  <router-link to='/dashboard'><input type="submit" value="DASHBOARD"></router-link>
</div>
</div>
</template>
<style>
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.title {
  color: grey;
  font-size: 18px;
}

button:hover, a:hover {
  opacity: 0.7;
}
input[type=submit] {
  background-color: rgb(98, 203, 245);
  color: white;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #0569c7;
}
</style>
