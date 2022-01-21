<template>
  <div class="header">
    <div class="logo-section"><img class="logo-img" src="../assets/Symbol.jpg"/></div>
    <ul class="headerSub">
            <li class="active"><a>HOME</a></li>
      <li><a href="#AboutUS">ABOUT US</a></li>
      <li><a>OUR SERVICES</a></li>
      <li><a>TECHNOLOGIES</a></li>
      <li><a>CONTACT US </a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>
<style >
.a{
  text-decoration: none;
  color: aliceblue;
}
.header {
  /* border: 1px solid red; */
  list-style: none;
  display: flex;
  font-size: 1.2rem;
  opacity: 0.9;
  justify-content: center;
  background-color: #095bb4;
  color: white;
  cursor: pointer;
  padding: 1.5rem;
}
.logo-section{
  /* border: 2px solid red; */
  /* width: 50%; */
  width: 150px;
  border-radius: 1rem;
}
.logo-img{
  width: 80px;
  height: 50px;
object-fit: contain;
}
.headerSub {
  /* border: 1px solid rgb(0, 255, 128); */
  padding: 1rem;
  width: 40vw;
  list-style: none;
  display: flex;
  justify-content: space-between;
  background-color: #095bb4;
}

.active {
  color: #940202;
}
@media only screen and (min-width: 320px) and (max-width: 1079px) {
  .header {
    height: 400px;
  }
  .headerSub {
    display: flex;
    flex-direction: column;
    justify-content:space-around;
    /* border: 10px solid red; */
    height: 300px;
  }
}
.headerSub a:hover {
  color: #940202;
 transition: all 0.1s linear 0.1s;
}
.img {
  width: 20px;
  height: 20px;
  /* border: 1px solid red; */
}
</style>
