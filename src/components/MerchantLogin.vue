<template>

<div class="container">
  <form action="" method="post">
    <div class="row">
      <h1 class="main">MERCHANT LOGIN</h1>
        <a href="#" class="google btn">
          <i class="fa fa-google"></i> Login with Google+
        </a>
      </div>
          <h3> OR </h3>
       <div>
        <input type="text" name="username" placeholder="Username" required>
        <input type="password" name="password" placeholder="Password" required>
        <router-link to='/dashboard'><button class="submit">Login</button></router-link>
      </div>

 </form>
      <router-link to='/register'><button class="submit">Register</button></router-link>
      <footer id=footer>
        <p>2021 SpoLub. By <a href="#">team11.com</a> </p>
      </footer>

</div>
</template>

<script>
export default {
  name: 'MerchantLogin'
}
</script>
<style>
* {box-sizing: border-box}

.main{
    text-align: center;
    align-content: center;
}

.container {
  margin: 40px;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px 10px 30px 10px;
  justify-content: center;
}

input, .submit{
  width: 70%;
  padding: 12px;
  border: none;
  border-radius: 4px;
  margin: 5px 0;
  display: inline-block;
  font-size: 17px;
  line-height: 20px;
}
.submit {
  background-color: rgb(98, 203, 245);
  color: white;
  cursor: pointer;
  width: 35%;
}

.submit:hover {
  background-color: #0569c7;
}

#footer {
  height:41px;
  background:#f2f2f2;

  line-height:50px; padding:0 15px; color:#7b7b7b; margin-top:120px;}
#footer a{ color:#7b7b7b; ;}
#footer a:hover{ color:#000;}
</style>
