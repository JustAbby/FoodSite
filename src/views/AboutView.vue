<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>

  
    <div class="container">
      <div class="main ">
        <h2>Welcome To 11:45 Bar and Restaurant</h2>
        <form id="form_id" method="post" name="myform" class="form-input">
          <label>User Name :</label>
          <input type="text" name="username" id="username" />
          <label>Password :</label>
          <input type="password" name="password" id="password" />
          <input type="button" value="Login" id="submit" onclick="validate()" />
        </form>
        <span><b class="text-danger">Note : </b>For this demo use following username and password. <br /><b class="text-success">User
            Name : Abby<br />Password : foodie</b></span>
      </div>
    </div>

</template>
