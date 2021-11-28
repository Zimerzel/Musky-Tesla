<template>
    <div class="model__s">
        <img src="https://tesla-cdn.thron.com/delivery/public/image/tesla/32e5e0f3-5c04-42ef-8f8f-c6b1c26f8a9e/bvlatuR/std/2880x1800/ms-main-hero-desktop" srcset="https://tesla-cdn.thron.com/delivery/public/image/tesla/32e5e0f3-5c04-42ef-8f8f-c6b1c26f8a9e/bvlatuR/std/2880x1800/ms-main-hero-desktop" alt="Red Model S" id="model__s"/>
        <div id="header">
            <h1>Model S</h1>
            <p>Plaid</p>
        </div>
        <div class="stats">
            <div id="range">
                <h2>396 mi</h2>
                <p>Range (EPA est.)</p>
            </div>
            <div id="speed">
                <h2>1.99s</h2>
                <p>0-60 mph*</p>
            </div>
            <div id="top__speed">
                <h2>200 mph</h2>
                <p>Top Speed*</p>
            </div>
            <div id="power">
                <h2>1,020 hp</h2>
                <p>Peak Power</p>
            </div>
            <button id="button__order">
                Order Now
            </button>
        </div>
        <div class="interior">
            <img src="https://tesla-cdn.thron.com/delivery/public/image/tesla/177c0faf-b852-47ea-a218-394368e15a20/bvlatuR/std/2880x1800/MS-Interior-Hero-Desktop" alt="interior View" id="inside">
            <h1>All-New Interior</h1>
        </div>
    </div>
</template>
<style scoped>
.model__s{
    position: relative;
}

.model__s p{

}

#model__s{
  height: 1000px !important;
  margin-top: -70px !important;
  width:100%;
  object-fit: cover;
  z-index: 2;
}

#header{
    position: relative;
    display: flex;
    justify-content: center;
    margin-top: 20px;
}

#header h1{
    position: absolute;
    top: -850px;
    color: black;
    font-size: 55px;
    font-weight: 600;
}

#header p{
    position: absolute;
    top: -790px;
    font-size: 20px;
}

.stats{
     margin-top: -25px;
     display: flex;
     flex-flow: row;
     justify-content: center;
     text-align: center;
     z-index: 1;
}

.stats h2{
    font-weight: 500 !important;
    font-size: 40px;
}

.stats div{
     margin: 40px;
     margin-top: -105px;
     color: rgb(255, 255, 255);
}

#button__order{
    margin-top: -90px;
    height: 50px;
    width: 220px;
    border-radius: 20px;
    border: rgb(255, 255, 255) 3px solid;
}

.interior{
    position: relative;
}

.interior h1{
    position: absolute;
    color: white;
    z-index: 1;
    top: 20px;
    left: 50px;
    right: 50px;
    display: flex;
    justify-content: center;
}

#inside{

    width:100%;
    object-fit: cover;
    margin-top: -28px;
}
</style>