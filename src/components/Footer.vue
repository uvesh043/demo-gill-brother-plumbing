<template>
  <div class="footer">
    <div class="footer-one">
      <ul class="footer-one ul">
        <li class="main-li">HOME</li>
        <li>About</li>
        <li>Careers</li>
        <li>Testimonials</li>
        <li>Coupons</li>
        <li>Request a Quote</li>
      </ul>
    </div>
    <div class="footer-one">
      <ul class="footer-one ul">
        <li class="main-li">SERVICES</li>
        <li>Plumbing</li>
        <li>Faucet Repair</li>
        <li>Toilet Repair</li>
        <li>Frozen Pipes</li>
        <li>Water Heatinge</li>
      </ul>
    </div>
    <div class="footer-one">
      <ul class="footer-one ul">
        <li class="main-li">COMMERCIAL PLUMBER</li>
        <li>Hydrojet & Powerflushing</li>
        <li>Leading Mississauga Plumbing</li>
        <li>Contractors</li>
        <li>Markham</li>
        <li>Richmond Hill</li>
      </ul>
    </div>
    <div class="footer-one address">
      <h3>BROTHERS PLUMBING</h3>
      <div>
        130 Osler Street, Toronto, ON, M6N 2Y8.

        <h3>800-742-0018</h3>
        Email: info@brothersplumbing.ca
      </div>

      <div>
        <h3>SERVICE HOURS</h3>
        Monday – Sunday: 7:00 AM – 7:00 PM
        <br />
        24/7 Emergency Service Available
      </div>
    </div>
  </div>
</template>
<style >
.footer {
  background-color: #1e6fc5;
  color: white;
  display: flex;
  justify-content: space-around;
  height: 300px;
}
.footer-one {
  height: 100%;
  /* padding-top: 1rem; */
 }
 .main-li{
     padding-top: 1rem;
 }
.footer-one ul {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
.footer-one ul li:hover {
  cursor: pointer;
  transition: all;
  transition-delay: 0.1s;
  transition-duration: 0.8s;
  transition-timing-function: ease-in-out;
  color: tomato;
}
.footer ul {
  list-style: none;
}
.main-li {
  font-size: 1.1rem;
  font-weight: bolder;
}
.address {
  /* border: 4px solid red; */
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}
</style>
<script>
export default {
  name: "Footer",
};
</script>
