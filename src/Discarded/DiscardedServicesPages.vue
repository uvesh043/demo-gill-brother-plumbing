<template>
  <div class="services-main">
    <div class="section-title">
      <span class="border-top"></span>
      <h1 class="main-title">SERVICES</h1>
      <span class="border-top right"></span>
    </div>
    <div class="section-content">
      <div class="section-content-img">
        <img src="../assets/plumbing-services1.png" />
      </div>
      <div class="content-text">
        <p class="content-text-one">
          lgoson Software is a software service provider company which is using
          the best-in-class process to deliver robust software applications.
          <br /><br /><br />
          We are a team of experienced software professionals and consultants
          with a variety of latest skill sets. We are bestowing our clients with
          the best possible technical solutions. Our engineering team holds
          sound logical skills and it is prominent for its quick response to
          clients.
          <br /><br />
          We are a process oriented company and we work in agility mode. We
          believe in defining accurate delivery lines and implementing
          transparent communication channels. We focus on the
          international-standard quality of software and client satisfaction.
        </p>
      </div>
    </div>
  </div>
</template>
<style >
.services-main {
  padding: 3rem;
  border: 2px solid green;
}
.section-title {
  display: flex;
  justify-content: center;
}
.border-top {
  width: 150px;
  height: 2px;
  margin-top: 1px;
  position: relative;
  top: 0.9rem;
  right: 3rem;
  border-top: 2px solid #095bb4;
  background-color: #095bb4;
}
.right {
  width: 150px;
  height: 2px;
  margin-top: 1px;
  position: relative;
  top: 0.9rem;
  left: 3rem;
  border-top: 2px solid #095bb4;
  background-color: #095bb4;
}
.section-content {
  display: flex;
  justify-content: space-between;
}
.content-text {
  padding-top: 1.5rem;
  text-align: center;
}
.section-content-img {
  width: 50vw;
  height: 80%;
  position: relative;
  top: 4rem;
}
.content-text-one {
  padding-bottom: 2rem;
  padding-top: 1rem;
  position: relative;
  bottom: 1rem;
}
</style>
<script>
export default {
  name: "Services.vue",
};
</script>


