<template>
  <div class="">
    <div class="row">
      <div class="col-md-5 col-12 first-col">
        <div class="container">
          <div class="pl-5 pr-5 mar">
            <h4 class="font-word">PEERCOVER</h4>
            <div class="mt-5">
              <h4 class="font-word">Car</h4>
              <h5 class="font-word">Insurance</h5>
            </div>
            <div class="mt-5">
              <h4 class="font-word">Prices from</h4>
              <h3 class="font-word">N10,000</h3>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-7 col-12 second-col">
        <div class="container">
          <div class="ml-5 mt-5 pt-4 second-second-col">
            <h4 class="font-word h1-second-col">WELCOME BACK</h4>
            <p class="p-font-word mt-4">Input your details to proceed</p>

            <div class="mt-4">
              <form>
                <div class="mb-5">
                  <input
                    type="email"
                    class="form-control"
                    id="exampleInputEmail1"
                    aria-describedby="emailHelp"
                    placeholder="Email Address"
                  />
                </div>
                <div class="mb-3">
                  <input
                    type="password"
                    class="form-control"
                    id="exampleInputPassword1"
                    placeholder="Password"
                  />
                </div>
                <p class="p-form mb-4">Forgot password ?</p>

                <button
                  type="button"
                  class="btn button-for-second-col btn-success"
                >
                  Log In
                </button>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
* {
  margin: 0px;
  padding: 0px;
  overflow: hidden;
}
.p-form {
  color: #00932b;
  text-align: right;
  font-weight: 300;
}
.first-col {
  background-color: #00932b;
  color: white;
  text-align: left;
  font-weight: bold !important;
  height: 100vh;
}
.mar {
  margin-top: 40% !important;
}
.font-word {
  font-weight: bold;
}
.p-font-word {
  text-align: left;
}
.h1-second-col {
  color: #00932b;
}
input {
  border: 1.4px solid black;
  padding-top: 15px !important;
  padding-bottom: 15px !important;
}
input:focus {
  border: 1.4px solid black;
}
::placeholder {
  color: black;

  font-weight: 500;
}
.button-for-second-col {
  width: 100%;
  padding-top: 1rem;
  padding-bottom: 1rem;
  font-weight: 750;
  font-size: large;
}
.second-second-col {
  margin-right: 25%;
}
@media (min-width: 320px) and (max-width: 768px) {
  .second-second-col {
    margin-right: 10%;
    margin-bottom: 10%;
  }
}
</style>