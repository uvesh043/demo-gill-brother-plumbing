<template>
  <div class="form-section">
    <div class="form-img-div">
      <img class="form-img" src="../assets/form-illustration.png" />
    </div>
    <div class="form-content">
      <h1 class="form-title">REQUEST A QUOTE</h1>
      <div class="form-input-div">
        <input class="form-input" placeholder="Name*" />
      </div>
      <div class="form-input-div">
        <input class="form-input" placeholder="Email*" />
      </div>
      <div class="form-input-div">
        <input class="form-input" placeholder="Phone*" />
      </div>
      <div class="form-input-div">
        <input class="form-input" placeholder="City*" />
      </div>
      <div class="form-input-div">
        <input class="form-input" placeholder="Comment*" />
      </div>
      <div class="form-input-div btnDIv">
        <div class="form-input-div btn">
          <button class="submit-Btn">Submit</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Formsection",
};
</script>

<style>
.form-section {
  padding-top: 3rem;
}
.form-section {
  display: flex;
  padding-top: 3rem;
  /* justify-content:center; */

  /* margin-top: 5rem; */
  height: 500px;
  position: relative;
   width: 99%;
 }
.form-img-div {
  width: 50%;
}
.form-title {
  color: #095bb4;
}
.form-img {
  width: 70%;
}
.form-content {
  width: 50%;
  height: 80%;

  display: flex;
  flex-direction: column;
  justify-content: space-around;
  /* align-content: space-around; */
}
.form-input {
  padding: 1rem;
  width: 70%;
  border-radius: 10px;
  border: 2px solid #940202;
  outline: none;
}
.form-input-div {
  margin-top: 1rem;
}
.btnDIv {
  display: flex;
  justify-content: center;
}
.btn {
  width: 75%;
  display: flex;
  justify-content: end;
}
.submit-Btn {
  padding: 0.7rem;
  padding-left: 1rem;
  padding-right: 1rem;
  background-color: #095bb4;
  border-radius: 0.2rem;
  color: white;
  font-size: 1rem;
}
.submit-Btn:hover {
  background-color: #940202;
  cursor: pointer;
  transition: all;
  transition-delay: 0.1s;

  transition-duration: 0.2s;
  transition-timing-function: ease-in-out;
}
</style>