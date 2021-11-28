<template>
  <div class="hello">
    <h1>Model S</h1>
    <p>Order Online for <span>Touchless Delivery</span></p>
    <img src="https://tesla-cdn.thron.com/delivery/public/image/tesla/676da95d-942e-414c-8534-f1832f0d4ced/bvlatuR/std/3296x1798/ms-homepage-desktop" alt="Red Model S" id="model__s"/>
    <button id="button__1">Custom Order</button>
    <button id="button__2">Existing Inventory</button>
  </div>
</template>

<style scoped>
.hello{
position: relative;
display: flex;
justify-content: center;
}

#model__s{
  height: 650px !important;
}

.hello button{
  position: absolute;
  height: 30px;
  border-radius: 30px;
  border: none;
  width:250px;
  height: 40px;
}

#button__1{
top: 80%;
left: 28%;
background-color: rgb(75, 74, 74);
color: white;
}

#button__2{
top: 80%;
right: 28%;
}


.hello h1, .hello p{
  position: absolute;
  justify-content: center !important;
  text-align: center !important;
}

.hello h1{
  position: absolute;
}

.hello p{
  position: absolute;
  top: 50px;
}

.hello span{
  text-decoration: underline;
}

img{
  margin-top: -60px;
  width: 100%;
  height: 800px;
  object-fit: cover;
}
</style>
