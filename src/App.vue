<template>
  <div id="app">
    <div>
   
    <b-container fluid class="bv-example-row">
  <b-row>
     <b-col>

  <div class="container">
    <label for="uname"><b>Username</b></label>
    <input type="text" 
           placeholder="Enter Username" 
           name="uname" 
           required>

    <label for="psw"><b>Password</b></label>
    <input type="password" 
           placeholder="Enter Password" 
           name="psw" 
           required>

    <button type="submit">Login</button>
    <label>
      <input type="checkbox" 
             checked="checked" 
             name="remember"> Remember me
    </label>
  </div>

  <div class="container" style="background-color:#f1f1f1">
    <button type="button" class="cancelbtn">Cancel</button>
    <span class="psw">Forgot <a href="#">password?</a></span>
  </div>
    </b-col>

    <b-col>
      <img src="./assets/image/work-background.jpg" 
           alt="Image Background">
    </b-col>

  </b-row>
</b-container> 
  </div>
  </div>
</template>


<style>

body, html {
  margin: 0;
  padding: 0;
}

#app {
  background: rgba(98, 164, 250, 0.644);

}
</style>
