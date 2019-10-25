<template>
  <body>
    <!-- nav -->
    <nav class="navbar navbar-expand-lg navbar-light">

      <div id="menuToggle">
        <!--
        A fake / hidden checkbox is used as click reciever,
        so you can use the :checked selector on it.
        -->
        <input type="checkbox" />

        <!--
        Some spans to act as a hamburger.
        They are acting like a real hamburger,
        not that McDonalds stuff.
        -->
        <span></span>
        <span></span>
        <span></span>

        <!--
        Too bad the menu has to be inside of the button
        but hey, it's pure CSS magic.
        -->
        <ul id="menu">
          <a href="./profile">
            <div class="rec-menu-list rec-menu-account">
              <img src="@/img/icon-account.svg" class="icon-account">
              <h1 class="name-menu-list account">Piyawat Sawong</h1>
            </div>
          </a>

          <a href="#">
            <div class="rec-menu-list rec-menu-main">
              <li>
                <a href="./home">
                  <img src="@/img/icon-home.svg" class="icon-home">
                  <h1 class="name-menu-list text-1">Home</h1>
                </a>
              </li>
              <li>
                <img src="@/img/icon-calendar.svg" class="icon-calendar">
                <h1 class="name-menu-list text-2">Calendar</h1>
              </li>
            </div>
          </a>

          <a href="./todo-list">
            <div class="rec-menu-list rec-menu-course">
              <li>
                <img src="@/img/icon-todolist.svg" class="icon-todolist">
                <h1 class="name-menu-list text-1">To-do list</h1>
              </li>
              <li>
                <a class="ellipse">
                  <h1 class="text-in-ellipse">
                    W
                  </h1>
                </a>
                <h1 class="name-menu-list text-2">Web Mining</h1>
              </li>
            </div>
          </a>

          <a href="#">
            <div class="rec-menu-list rec-menu-option">
              <li>
                <img src="@/img/icon-setting.svg" class="icon-setting">
                <h1 class="name-menu-list text-1">Setting</h1>
              </li>
              <li>
                <img src="@/img/icon-logout.png" class="icon-logout">
                <h1 class="name-menu-list text-2">
                  Logout
                </h1>
              </li>
            </div>
          </a>
          <a href="https://erikterwan.com/" target="_blank"><li>Show me more</li></a>
        </ul>
      </div>


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

        <img src="@/img/noti.svg" class="noti">
      </nav>

      <!-- main -->
      <div class="rec-main">

        <div class="rec-main-topic">
        <a href="./todo-list"><h1 class="text-todo-1 text-main-todo">To-do</h1></a>
        <a href="./done"><h1 class="text-todo-1 text-main-done">Done</h1></a>
        </div>

        <div class="box box-main">

          <a class="box box-all-class dropdown-toggle dropdow-language" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            All classes
          </a>

          <div class="box box-todo">
            <h1 class="text-todo-1 text-topic-todo">Architecture style</h1>
            <h3 class="text-todo-3 text-detail">Software design</h3>
            <h3 class="text-todo-3 text-detail-date">- Due Aug 16, 2018, 11:59 PM</h3>
          </div>

        </div>

      </div>

      <!-- footer -->

        <footer class="footer-todo bg-white">

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
  import "@/css/custom-home.css";
  import "@/css/custom-todo-list.css";
  export default{
    css: 'custom'
  }
</script>
