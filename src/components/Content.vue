<template>
<div >
<div class="imgDiv">
   <img class="img"  src="../assets/gill-Brother-plumbing.jpg"/>
</div>
<div class="img-text">
  <h1>OVER 50 YEARS OF EXPERIENCE <br>
IN PLUMBING AND DRAINS
</h1>



<div class="wrap" >
    <button class="button">REQUEST INFO</button>
<button class="button">REQUEST QUOTE</button>

</div>
</div>
</div>
</template>
<script>


export default {
  name: "Content",
}
</script>j

<style >
.imgDiv{
  height: 500px;
  display: flex;
  justify-content: center;
  

}
.img{
  height: 500px;
  width: 100%;
  object-fit: cover;
}
.img-text{
  color: white;
  position: relative;
  /* background-color: black; */
  /* opacity: 0.2; */
  font-size: 1em;
  /* right: 150px; */
  bottom: 400px;
  letter-spacing: 8px;
  width: 80%;
}
.img-text h1,h4{
  background-color: black;
  opacity: 0.5;
  font-weight: bolder;
  
}
.btn-section{
  position: relative;
  left: 200px;
  display: flex;
  justify-content: space-between;
  width: 20vw;
  /* border: 1px solid red; */
  top: 1rem;
}
.btn-section button{
  padding: 1rem;
  margin: 1rem;
  
}
.btn-section button:hover{
transition: all;
transition-delay: 0.2s;
transition-duration: 1s;
transition-timing-function: ease-in-out;
  box-shadow: 5px 5px #095bb4 ;
}
.btn-section-btn{
  background-color:#095bb4;
  margin: 10px;
}


.wrap {
  height: 100%;
  display: flex;
  width: 30%;
  top: 2rem;
 display: flex;
  position: relative;
  left: 14rem;
  align-items: center;
  justify-content: center;
  justify-content: space-between;
}

.button {
  width: 140px;
  height: 45px;
  font-size: 1.3rem;
  font-family: 'Roboto', sans-serif;
  font-size: 11px;
  text-transform: uppercase;
  letter-spacing: 2.5px;
  font-weight: 500;
  color: #000;
  background-color: #095bb4;
  border: none;
  margin: 10px;
  border-radius: 35px;
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease 0s;
  cursor: pointer;
  outline: none;
  }

.button:hover {
  background-color: #095bb4;
  box-shadow: 0px 15px 20px #095bb4;
  color: #fff;
  transform: translateY(-7px);
}
</style>