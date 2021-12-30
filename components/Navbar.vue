<template>
  <!-- Navbar Section Start Here -->
  <section class="top-area">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <div class="container">
            <!-- navbar start here -->
            <nav
              class="navbar navbar-expand-lg navbar-light justify-content-end"
            >
              <div class="container-fluid">
                <a class="navbar-brand" href="#">
                  <img
                    src="/favicon.ico"
                    alt=""
                    width="30"
                    height="24"
                    class="d-inline-block align-text-top"
                  />
                  Doctor's Appointment
                </a>
                <button
                  class="navbar-toggler"
                  type="button"
                  data-bs-toggle="collapse"
                  data-bs-target="#navbarSupportedContent"
                  aria-controls="navbarSupportedContent"
                  aria-expanded="false"
                  aria-label="Toggle navigation"
                >
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div
                  class="collapse navbar-collapse me-2 justify-content-end"
                  id="navbarSupportedContent"
                >
                  <ul class="navbar-nav mb-2 mb-lg-0">
                    <li class="nav-item">
                      <nuxt-link class="nav-link" aria-current="page" to="/"
                        >Home</nuxt-link
                      >
                    </li>
                    <li class="nav-item">
                      <nuxt-link
                        class="nav-link"
                        aria-current="page"
                        to="doctor"
                        >Doctor</nuxt-link
                      >
                    </li>
                    <li class="nav-item">
                      <a
                        class="nav-link"
                        aria-current="page"
                        href="assistantarea"
                        >Assistant</a
                      >
                    </li>
                    <li class="nav-item">
                      <nuxt-link class="nav-link" aria-current="page" to="about"
                        >About</nuxt-link
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" aria-current="page" href="contact"
                        >Contact</a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" aria-current="page" href="login"
                        >Login</a
                      >
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" aria-current="page" href="register"
                        >Register</a
                      >
                    </li>
                    <button
                      class="btn mx-2 btn-outline-info btn-sm btn-appointment"
                      type="button"
                      onclick="window.open('makeanappointment','_self')"
                    >
                      Make an Appointment
                    </button>
                  </ul>
                </div>
              </div>
            </nav>
            <!-- navbar end here -->
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Navbar Section End Here -->
</template>
