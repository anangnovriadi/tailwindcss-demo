<template>
  <div id="app" class="flex justify-center items-center w-full min-h-screen">
    <div class="login-container shadow-lg rounded-lg w-3/5">
      <div class="float-right">
        <font-awesome-icon size="3x" icon="times" class=" m-4"/>
      </div>
      <div class="login-curve rounded-lg bg-white h-full w-3/5">
        <div class="login-form">
            <h1 class="p-16 text-blue-darker text-4xl">Sign up</h1>
            <div class="login-form__input px-32 ">
              <form>
                <div class="mb-8">
                  <label class="mb-2 text-lg text-blue-darker">Name</label>
                  <input type="text" class="h-12 w-full bg-grey-lighter rounded-sm appearance-none focus:outline-none focus:shadow-outline"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-lg text-blue-darker">Email</label>
                  <input type="text" class="h-12 w-full bg-grey-lighter rounded-sm appearance-none focus:outline-none focus:shadow-outline"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-lg text-blue-darker">Username</label>
                  <input type="text" class="h-12 w-full bg-grey-lighter rounded-sm appearance-none focus:outline-none focus:shadow-outline"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-lg text-blue-darker">Password</label>
                  <input type="text" class="h-12 w-full bg-grey-lighter rounded-sm appearance-none focus:outline-none focus:shadow-outline"/>
                </div>
                <div>
                  <input type="checkbox"/>
                  <p class="ml-2 text-grey">I accept the terms and conditions</p>
                </div>
                <div>
                  <button class="w-full rounded-lg mt-4 bg-blue-dark h-10 text-white hover:bg-blue-light hover:text-grey-light hover:border-blue-dark transition transition-slow transition-property-all transition-timing-linear">Signup</button>
                </div>
              </form>
              
            </div>
        </div>
      </div>
      
      
    </div>
  </div>
</template>

<script>

export default {
}
</script>

<style>
html { height: 100% }
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #ff9999;
}
input[type="text"], label {
    display:block;
}
input[type="checkbox"], p {
    display:inline-block;
}
.login-container{
  height: 750px;
  background-color: #ff8080 ;
}

</style>
