<template>
  <div id="app" class="flex justify-center items-center">
    <div class="login-container shadow-lg">
      <div class="float-right">
        <font-awesome-icon size="3x" icon="times" class=" m-4"/>
        <div class="">
          <input type="checkbox" class=""/>
        </div>
      </div>
      <div class="login-curve">
        <div class="login-form">
            <h1 class="login-form__header text-blue-darker text-4xl">Sign up</h1>
            <div class="login-form__input px-24">
              <form>
                <div class="mb-8">
                  <label class="mb-2 text-xl text-blue-darker">First and last name</label>
                  <input type="text" class="h-12 w-3/4"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-xl text-blue-darker">Email</label>
                  <input type="text" class="h-12 w-3/4"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-xl text-blue-darker">Username</label>
                  <input type="text" class="h-12 w-3/4"/>
                </div>
                <div class="mb-8">
                  <label class="mb-2 text-xl text-blue-darker">Password</label>
                  <input type="text" class="h-12 w-3/4"/>
                </div>
              </form>
              <p class="text-blue-dark">Minimum 8 letter, at least one letter and one special symbol</p>
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
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #ff9999;
  height: 100vh;
  width: 100%;
}
input, label {
    display:block;
}
.login-container{
  height: 750px;
  width: 60%;
  background-color: #ff8080 ;
}
.login-curve{
  height: 100%;
  width: 65%;
  background-color: #f2f2f2;

}
.login-form__header{
  padding: 60px;
}
</style>
