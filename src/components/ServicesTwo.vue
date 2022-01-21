<template>
 <div class="sercvices">
     <!-- <h1 class="services-title">SERVICES</h1> -->
     <div class="section-title">
 <span class="border-top"></span>
     <h1 class="main-title">SERVICES</h1>
     <span class="border-top right"></span>
    
 </div>

    <div class="services-main-one">
         <div class="services-main-div">
            <div>
                 <img src="../assets/shower-icon.png"/>
            </div>
             <div>
                   <h3>Showers and Bathtubs</h3>
             <h4>New shower faucets, bathtub installation and repair, power shower installation.</h4>
             </div>
             </div>
           
     <div class="services-main-div">
          <div>
                 <img src="../assets/toilet-icon.png"/>
            </div>
             <div>
                   <h3>Faucet Installation / Repairs</h3>
             <h4>Faucet repairs and new installations of all brands - including European faucets.</h4>
             </div>
     </div>
     <div class="services-main-div">
          <div>
                 <img src="../assets/water-heating.png"/>
            </div>
             <div>
                   <h3>No Heat Emergency</h3>
             <h4>Faulty thermostats, temporary heaters, gas burners or controls.</h4>
             </div>
     </div>
    </div>

   <div class="services-main-two">
         <div class="services-main-div">
              <div>
                 <img src="../assets/24-hour-service.png"/>
            </div>
             <div>
                   <h3>24-hour Plumbing Services</h3>
             <h4>With professional and courteous service, our licensed technicians will help get you out of trouble. And we offer warranty protection.</h4>
             </div>
         </div>
     <div class="services-main-div">
          <div>
                 <img src="../assets/plumbing-icon.png"/>
            </div>
             <div>
                   <h3>Plumbing Maintenance</h3>
             <h4>Fix high water bills with regular maintenance - we inspect toilets and faucets for running water, and test hose faucets and sump pumps.</h4>
             </div>
     </div>
     <div class="services-main-div">
          <div>
                 <img src="../assets/icons8-repair.png"/>
            </div>
             <div>
                   <h3>Toilet Repair and Replacements</h3>
             <h4>New toilet installation and toilet repairs, including blockage, leaks and slow moving water.</h4>
             </div>
     </div>
   </div>
     </div>   
</template>
<style>
.services-title{
    text-align: center;
}
.sercvices{
    /* border: 2px solid rgb(0, 255, 21); */
    height: 78vh;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}
.services-main{
    border: 2px solid violet;
    height: 48vh;
    display: flex;
    justify-content: space-around;
}
.services-main-div{
  /* background-color: #095bb4; */
  display: flex;
  justify-content: space-around;
  flex-direction: column;
  padding: 1rem;
  width: 20%;
    /* border: 2px solid blue; */
    height: 25vh;
}
.services-main-one{
    display: flex;
    justify-content: space-around;
}
.services-main-two{
    display: flex;
    justify-content: space-around;
}
h4{
    background-color: transparent;
    color: black;
}
</style>
<script>
export default {
  name: "ServicesTwo.vue",
};

</script>
