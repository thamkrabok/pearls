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
        <!-- account -->
        <a href="./profile">
          <div class="rec-menu-list rec-menu-account">
            <img src="@/img/icon-account.svg" class="icon-account">
            <h1 class="name-menu-list account">Piyawat Sawong</h1>
          </div>
        </a>


        <a href="#">
          <div class="rec-menu-list rec-menu-main">
            <div class="rec-menu-home">
            <li>
              <img src="@/img/icon-home.svg" class="icon-home">
              <h1 class="name-menu-list text-1 hover">Home</h1>
            </li>
            </div>
            <div class="rec-menu-calendar">
              <li>
                <img src="@/img/icon-calendar.svg" class="icon-calendar">
                <h1 class="name-menu-list text-2">Calendar</h1>
              </li>
            </div>
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
    <div class="wrapper">
      <a class="rec-home"><img src="@/img/sensei.png" class="sensei-home"></a>
      <a class="rec-main-home"></a>
      <div class="rec-course-categories">
        <h1 class="course-categories-topic">Course Categories</h1>
        <input type="text" placeholder="Search Course" class="search-course-categories">
        <a class="rec-icon-search"><img src="@/img/search-solid.svg" class="icon-search"></a>
        <div class="rec-course-categories-list rec-course-1">
          <a class="img-course"></a>
          <h1 class="name-course-categories-list name-course-categories-1">
            SOFTWARE DESIGN
          </h1>
          <h1 class="detail-course-categories-list detail-course-categories-list-1">
            Goals of software design, the Unified Modeling Language, design principles, design patterns...
          </h1>
          <div class="button-access-course">
            <h1 class="name-button-access-course">
              Get Access
            </h1>
          </div>
        </div>

        <div class="rec-course-categories-list rec-course-2">
          <a class="img-course"></a>
          <h1 class="name-course-categories-list name-course-categories-2">
            SYSTEM SECURITY
          </h1>
          <h1 class="detail-course-categories-list detail-course-categories-list-2">
            Introduction to fundamental computer security technologies, user authentication : password-based.....
          </h1>
          <div class="button-access-course">
            <h1 class="name-button-access-course">
              Get Access
            </h1>
          </div>
        </div>

        <div class="rec-course-categories-list rec-course-3">
          <a class="img-course"></a>
          <h1 class="name-course-categories-list name-course-categories-3">
            MIXED REALITY
          </h1>
          <h1 class="detail-course-categories-list detail-course-categories-list-3">
            Introduction to e-business strategies and the development, architecture of e- business solutions and their components...
          </h1>
          <div class="button-access-course">
            <a href="./course">
            <h1 class="name-button-access-course">
              Get Access
            </h1>
          </a>
          </div>
        </div>
      </div>

      <div class="rec-month-calendar-home "></div>
      <div class="rec-date-calendar-home "></div>
      <div class="rec-upcoming-home">
        <h1 class="text-upcoming-home">Upcoming</h1>
        <a class="rec-upcoming-list-home"></a>
      </div>

      <!-- help section -->
      <div class="section-help">
        <img src="@/img/feedback.svg" class="icon-feedback">
        <h1 class="text-feedback">Feedback</h1>
        <ul class="feedback-description">
          <li>Report complaints / suggestions</li>
          <li>System usage questionnaire</li>
              for the academic Year 2019
        </ul>

        <a class="line-section-help line-section-help-1"></a>
        <img src="@/img/nevigation.png" class="icon-navigation">
        <h1 class="text-navigation">Navigation</h1>
        <ul class="navigation-description">
          <li>Enrollment Code</li>
          <li>All courses</li>
          <li>Request a course</li>
          <li>Learning Portal</li>
          <li>User Manual</li>
        </ul>

        <a class="line-section-help line-section-help-2"></a>
        <img src="@/img/help.png" class="icon-help">
        <h1 class="text-help">Help & Support</h1>
        <p class='help-description'>interested staff opening<br>
        courses online,<br>
        <a href="url" style="color:#F8941E;">click here</a> or contact <a href="url" style="color:#F8941E;"> cs@kmitl.ac.th</a></p>
      </div>
    </div>

      <!-- footer -->
      <footer class="footer-home bg-white">

        <img src="@/img/com_logo.png" class="cs-logo-footer">

        <h1 class="contact-text-footer">
          CONTACT US
        </h1>
        <h1 class="address-text-footer">
          Department of Computer Science, Faculty of Science, King Mongkut’s Institute of Technology Ladkrabang Chalongkrung Rd. Ladkrabang District Bangkok 10520
        </h1>

        <img src="@/img/phone.png" class="icon-phone-footer">
        <h1 class="phone-number-text">
          Phone : 02-329-8400
        </h1>

        <img src="@/img/email.svg" class="icon-email-footer">
        <h1 class="email-text-footer">
          E-mail : cs@kmitl.ac.th
        </h1>

        <h1 class="get-social-text-footer">
          GET SOCIAL
        </h1>
        <img src="@/img/facebook.png" class="icon-facebook-footer">
        <img src="@/img/twitter.png" class="icon-twitter-footer" id="rec-twitter-footer">
        <img src="@/img/ig.png" class="icon-ig-footer">
        <img src="@/img/youtube.png" class="icon-youtube-footer">

        </footer>
    </body>
</template>

<script>
  import "@/css/custom-home.css";
  export default{
    css: 'custom'
  }
</script>
