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

    <div class="rec-main-in-course">

      <a href="./in-course">
        <h1 class="about">
          About
        </h1>
      </a>

      <h1 class="class">
        Class
      </h1>

      <a href="./in-course-grade">
        <h1 class="grade">
          Grade
        </h1>
      </a>

      <div class="rec-topic">
        <img src="@/img/course/main-topic-1.jpg" width="1540px" height="247px">
        <h1 class="text-topic-course">05506221 Mixed Reality</h1>
        <h1 class="text-time">Friday 09:00 AM - 12:00 AM</h1>
      </div>
    </div>

    <div class="rec-in-course-class rec-topic-in-course-class">
      <h1 class="text-topic-in-course-class text-topic-in-course-class-1">
        All Topics
      </h1>
      <h1 class="text-topic-in-course-class text-topic-in-course-class-2">
        Document
      </h1>
      <h1 class="text-topic-in-course-class text-topic-in-course-class-3">
        Video Teaching
      </h1>
      <h1 class="text-topic-in-course-class text-topic-in-course-class-4">
        Announment
      </h1>
      <h1 class="text-topic-in-course-class text-topic-in-course-class-5">
        Assignment
      </h1>
    </div>

    <div class="rec-in-course-class rec-post">
      <input class="rec-in-post" input type="text" >
      <img src="@/img/in-course-class/attachment.svg" class="icon-attachment">
      <img src="@/img/in-course-class/photo.svg" class="icon-photo">
      <img src="@/img/in-course-class/link.svg" class="icon-link">
      <h1 class="text-cancel">Cancel</h1>
      <div class="button-post">
        <h1 class="text-button-post">
          Post
        </h1>
      </div>

    </div>


    <div class="rec-in-course-class rec-post-2">
      <div class="ellipse-post">
        <img src="@/img/course/aj-mo.jpg" class="aj-post">
      </div>

      <h1 class="text-name-aj-post">
        Witchaya Towongpaichayont
      </h1>
      <h1 class="text-time-post">
        May 15, 2019
      </h1>
      <img src="@/img/in-course-class/more-vert.svg" class="icon-more-vert">
      <h1 class="text-detail-post">
        Quest board of 7/4/2018
      </h1>
      <div class="rec-detail-post">
        <img src="@/img/in-course-class/insert-file.svg" class="icon-insert-file ">
        <h1 class="detail-file-post">
          Mixed Reality 2-62 Game...
        </h1>
        <h1 class="type-file-post">
          Google Sheet
        </h1>
      </div>
    </div>




        <!-- footer -->

          <footer class="footer-in-course bg-white">

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
  import "@/css/custom-course.css";
  import "@/css/custom-in-course.css";
  import "@/css/custom-in-course-class.css";
  export default{
    css: 'custom'
  }
</script>
