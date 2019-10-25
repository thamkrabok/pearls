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

        <div class="rec-profile">
          <div class="ellipse-profile">
            <img src="@/img/profile/profile.jpg" class="img-profile">
          </div>
          <div class="box box-edit">
            <h4 class="text-edit">Edit</h4>
            <img src="@/img/profile/edit.svg" class="img-edit">
          </div>
          <h1 class="text-profile-1 text-name-profile">Mr. Piyawat Sawong</h1>
          <h3 class="text-profile-3 text-id-profile">Student ID  600502xx</h3>
          <h3 class="text-profile-3 text-date-ad">Date of Admission : 2016</h3>
          <h3 class="text-profile-3 text-date-grad">Date of Graduation : N/A (Status : Study)</h3>
        </div>

        <div class="box box-skill">
          <h2 class="text-profile-2 topic-skill">SKILLS</h2>
          <a class="line line-skill"></a>
          <ul class="text-detail-all ">
            <li class="text-profile-3 color-gray">Node Js</li>
            <li class="text-profile-3 color-gray">Java</li>
            <li class="text-profile-3 color-gray">ICPC 0 Point</li>
          </ul>
        </div>

        <div class="box box-cer">
          <h2 class="text-profile-2 topic-cer">CERTIFICATE</h2>
          <a class="line line-cer"></a>
          <ul class="text-detail-all">
            <li class="text-profile-3 color-gray">ICPC</li>
          </ul>
        </div>

        <div class="box box-track">
          <h2 class="text-profile-2 topic-track">TRACK RECORD</h2>
          <a class="line line-track"></a>
          <ul class="text-detail-all ">
            <li class="text-profile-3 color-gray">แมงกุดจี่</li>
            <li class="text-profile-3 color-gray">ICPC problem solving</li>
            <li class="text-profile-3 color-gray">How to boiled water</li>
          </ul>
        </div>

      </div>

      <!-- footer -->

        <footer class="footer-profile bg-white">

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
  import "@/css/custom-profile.css";
  export default{
    css: 'custom'
  }
</script>
