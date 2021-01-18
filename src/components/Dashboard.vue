<template>
    <div class="container">
        <div>
            <h1> ADD PRODUCT</h1>
            <div class="dropdown">
              <button class="dropbtn">CATEGORY</button>
                <div class="dropdown-content">
                    <a href="#">Cricket</a>
                    <a href="#">Football</a>
                    <a href="#">Badminton</a>
                    <a href="#">Table tennis</a>
                    <a href="#">Carom</a>
                </div>
            </div>

      </div>
      <input type="text" name="product-name" placeholder="product name">
      <input type="number" name="quantity" placeholder="Quantity">
      <input type="text" name="Price" placeholder="price">
      <input type="file" class= "picture" name="picture" placeholder="upload">
      <p><router-link to="/thankyou"><button class="submitbtn" type="submit" placeholder="Submit">Submit</button></router-link></p>

      <h1>OR</h1>
      <h1>EDIT DETAILS</h1>
      <router-link to="/edit"><button class="editbtn">Edit</button></router-link>
    </div>

</template>
<script>

export default {
  name: 'Dashboard'
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
.picture{
    background-color: white;
}
.dropbtn {
 background-color: #54adf5;
 color: black;
 padding: 16px;
 font-size: 11.5px;
 border: none;
 margin-bottom: 15px;
 border-radius: 5px;
}
.submitbtn, .editbtn{
 background-color: #54adf5;
 color: black;
 font-size: 18px;
 border: none;
 padding: 16px;
 border-radius: 5px;
}
.submitbtn:hover, .editbtn:hover{
    background-color: rgb(114, 210, 248);
}

.dropdown {
 position: relative;
 display: inline-block;
}

.dropdown-content {
 display: none;
 position: absolute;
 background-color: #f1f1f1;
 min-width: 160px;
 box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
 z-index: 1;
}

.dropdown-content a {
 color: rgb(103, 170, 214);
 padding: 12px 16px;
 text-decoration: none;
 display: block;
}

.dropdown-content a:hover {
    background-color: #ddd;
    }

.dropdown:hover .dropdown-content {display: block;}

.dropdown:hover .dropbtn {background-color: #d2e7f5; transform: scale(1.2);}
</style>
