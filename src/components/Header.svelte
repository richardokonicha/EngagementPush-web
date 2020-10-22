<script>
  let logo = "./asset/logo.png";
</script>

<style>
  .custom-navbar {
    background-color: hsl(0, 0%, 93%);

    box-shadow: 0 2px 4px 0 rgba(0, 0, 0, 0.09);
    height: 70px;
    max-height: 70px;
  }

  .navbar-toggler {
    font-size: 38px;
    background-color: transparent;
  }

  .navbar-toggler:focus {
    text-decoration: none;
    outline: none;
  }
  .navbar-collapse {
    background-color: hsl(0, 0%, 93%);
  }

  .nav-custom-link {
    font-size: 12px;
    font-weight: 400;
    letter-spacing: 0.05em;
    margin-top: 5px;
  }

  .navbar a {
    color: #53627c !important;
  }

  .nav-right {
    float: right;
  }

  @media (max-width: 991px) {
    .nav-right {
      float: left;
    }
    .nav-custom-link {
      border-bottom: 1px solid #eee;
    }
    .navbar-nav {
      width: 100%;
    }
    .navbar-nav .nav-link {
      padding: 20px 0;
      text-align: left;
    }

    .btn-demo-small {
      background-color: #ffffff;
      border: 0px;
      padding: 0px;
      box-shadow: none;
    }
    .btn-demo-small:hover {
      background-color: #ffffff;
      border: 0px;
      padding: 0px;
      box-shadow: none;
    }
    .btn-demo-small a {
      color: #53627c !important;
    }
    .nav-custom-link {
      font-size: 13px;
    }

    .icon-mobile {
      font-size: 18px;
      float: right;
    }

    .navbar-collapse {
      border-bottom: 1px solid #efefef;
    }

    .nav-logo-mobile {
      margin: auto;
      padding-right: 50px;
    }

    .nav-logo-desktop {
      display: none;
    }
  }

  /* Large devices (desktops, 992px and up) */
  @media (min-width: 992px) {
    .icon-mobile {
      display: none;
    }
    .nav-logo-mobile {
      display: none;
    }
  }

  .logo {
    max-width: 36px;
    margin-bottom: 14px;
  }
  .custom-navbar {
    background-color: hsl(0, 0%, 93%) !important;
  }
  .logo-title {
    display: inline;
    font-size: 30px;
    font-weight: 600;
    font-weight: 300;
    line-height: 40px;
    padding: 20px;
    padding-bottom: 0;
  }
  .btn {
    font-size: 14px;
    font-weight: 400;
    border-radius: 3px !important;
    box-shadow: 0 2px 3px 0 rgba(0, 0, 0, 0.05), 0 1px 2px 0 rgba(0, 0, 0, 0.08);
  }

  .btn:hover {
    text-decoration: none;
  }

  .btn-demo-small {
    font-size: 12px;
    background-color: hsl(0, 87%, 9%);
    padding: 1px 4px;
  }
  .btn a {
    color: white !important;
  }
</style>

<nav class="navbar navbar-default navbar-expand-lg fixed-top custom-navbar">
  <button
    class="navbar-toggler"
    type="button"
    data-toggle="collapse"
    data-target="#navbarNavDropdown"
    aria-controls="navbarNavDropdown"
    aria-expanded="false"
    aria-label="Toggle navigation">
    <span class="icon ion-md-menu" />
  </button>
  <img src={logo} class="img-fluid nav-logo-mobile logo" alt="Company Logo" />
  <div class="collapse navbar-collapse" id="navbarNavDropdown">
    <div class="container">
      <img
        src={logo}
        class="img-fluid nav-logo-desktop logo"
        alt="Company Logo" />
      <h2 class="logo-title">Engagement bot</h2>
      <ul
        class="navbar-nav ml-auto nav-right"
        data-easing="easeInOutExpo"
        data-speed="1250"
        data-offset="65">
        <li class="nav-item nav-custom-link">
          <a class="nav-link" href="index.html">Home
            <i class="icon ion-ios-arrow-forward icon-mobile" /></a>
        </li>
        <!-- <li class="nav-item nav-custom-link">
          <a class="nav-link" href="#marketing">Features
            <i class="icon ion-ios-arrow-forward icon-mobile" /></a>
        </li>
        <li class="nav-item nav-custom-link">
          <a class="nav-link" href="#testimonials">Testimonials
            <i class="icon ion-ios-arrow-forward icon-mobile" /></a>
        </li> -->
        <li class="nav-item nav-custom-link">
          <a class="nav-link" href="#pricing">Pricing
            <i class="icon ion-ios-arrow-forward icon-mobile" /></a>
        </li>
        <li class="nav-item nav-custom-link btn btn-demo-small">
          <a class="nav-link" href="#pricing">Buy now<i
              class="icon ion-ios-arrow-forward icon-mobile" /></a>
        </li>
      </ul>
    </div>
  </div>
</nav>
<!-- E N D  N A V B A R -->
