<template>
    <div class="container">
  <form action="/action_page.php" method="post">
    <div class="row">
      <h1 class="main">MERCHANT REGISTRATION</h1>
              <a href="#" class="google btn">
          <i class="fa fa-google"></i> Login with Google+
        </a>
      </div>
          <h3> OR </h3>
       <div>
        <input type="text" name="username" placeholder="Username" required>
        <input type="password" name="password" placeholder="Password" required>
        <input type="email" name="email" placeholder="Email" required>
        <input type="tel" name="description" placeholder="Description">
        <router-link to='/'><input type="submit" value="Register"></router-link>
      </div>

 </form>
</div>
</template>
<script>
export default {
  name: 'Register'
}
</script>
<style>
* {box-sizing: border-box}
h1 {
  text-shadow: 2px 2px #00b7ff;
}
.main{
    text-align: center;
    align-content: center;
}

.container {
  margin: 40px;
  position: relative;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px 10px 30px 10px;
  justify-content: center;
}

input,
.btn {
  width: 70%;
  padding: 12px;
  border: none;
  border-radius: 4px;
  margin: 5px 0;
  opacity: 0.85;
  display: inline-block;
  font-size: 17px;
  line-height: 20px;
}

.btn {
  color: rgb(228, 176, 176);
}
.btn:hover {
  opacity: 1;
   background-color: #f38c7e;
}

input[type=submit] {
  background-color: rgb(98, 203, 245);
  color: white;
  cursor: pointer;
  width: 40%;
}

input[type=submit]:hover {
  background-color: #4392db;
}
</style>
