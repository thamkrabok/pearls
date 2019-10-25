<template>
  <body>
    <!-- nav -->
    <nav class="navbar navbar-expand-lg navbar-light">

        <a class="nav-link dropdown-toggle dropdow-language" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          English (EN)
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>


      <img src="@/img/email.svg" class="icon-email">
      <h1 class="help">
        Need help! 
      </h1>
      <h1 class="cskmitl">
        CS@kmitl.ac.th
      </h1>
      <h1 class="youare">
        You are not logged in. (Log in)
      </h1>
    </nav>

    <!-- main -->
    <div class="wrapper">
    <img src="@/img/CEO_5035.jpg" class="CEO-5035" >
    <a id="rec"></a>
    <h1 class="let">Let's get started NOW ! </h1>

    <a class="rec-login"></a>
    <a class="eclipse"></a>
    <img src="@/img/cs-logo.png" class="cs-logo ">
    <a href="./home"><img src="@/img/google-authen.png" class="google-authen"></a>
    <div class="line-left"></div>
    <h1 class="or" >or</h1>
    <div class="line-right"></div>

    <form action="./#">
      <input type="text" class="username-box" placeholder="Username">
      <br>
      <input type="password" class="password-box" placeholder="Password">
      <label>
        <input type="checkbox" checked="checked" name="remember" class="check-remember"><h1 class="remember"> Remember username</h1>
        <button type="submit" class="submit">Sign in</button>
        <h1 class="forget">Forget Password ?</h1>
      </label>
    </form>
  </div>

    <!-- footer -->
  <footer class="footer bg-white">

    <img src="@/img/com_logo.png" class="com-logo-footer">

    <h1 class="contact">
      CONTACT US
    </h1>
    <h1 class="department">
      Department of Computer Science, Faculty of Science, King Mongkut’s Institute of Technology Ladkrabang Chalongkrung Rd. Ladkrabang District Bangkok 10520
    </h1>

    <img src="@/img/phone.png" class="icon-phone">
    <h1 class="phone">
      Phone : 02-329-8400
    </h1>

    <img src="@/img/email.svg" class="icon-email-footer">
    <h1 class="email-footer">
      E-mail : cs@kmitl.ac.th
    </h1>

    <h1 class="get-social">
      GET SOCIAL
    </h1>
    <img src="@/img/facebook.png" class="icon-face">
    <img src="@/img/twitter.png" class="icon-twitter" id="rec-twitter">
    <img src="@/img/ig.png" class="icon-ig">
    <img src="@/img/youtube.png" class="icon-youtube">

  </footer>


  </body>
</template>

<script>
  export default{
    css: 'custom'
  }
</script>
