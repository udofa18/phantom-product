<template>
  <!-- <HelloWorld/> -->
  <nav class="navbar navbar-expand-lg fixed-top navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand m-2 h1" href="#">Phantom</a>
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
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul
          class="navbar-nav me-auto mb-2 mb-lg-0 nav-pills mobile-li"
          style="margin-left: 10rem; font-size: 0.9rem !important"
        >
          <router-link to="/">
            <li class="nav-item hvr-bounce-in">
              <a class="nav-link">Home</a>
            </li>
          </router-link>
          <router-link to="/about">
            <li class="nav-item hvr-bounce-in">
              <a class="nav-link">About</a>
            </li>
          </router-link>
          <li class="nav-item dropdown hvr-bounce-in">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Products
            </a>
            <ul class="dropdown-menu p-2" style="width: 300px !important">
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Product 1</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >product 2</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >product 3</a
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown hvr-bounce-in">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Features
            </a>
            <ul
              class="dropdown-menu dropdown-menu p-2"
              style="width: 300px !important"
              aria-labelledby="navbarDropdownMenuLink"
            >
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Asset Management
                </a>
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Data HUb</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >File Management</a
                >
              </li>
            </ul>
          </li>
          <li class="nav-item dropdown hvr-bounce-in">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Partners
            </a>
            <ul
              class="dropdown-menu dropdown-menu p-2"
              style="width: 300px !important"
              aria-labelledby="navbarDropdownMenuLink"
            >
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Binance</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Apple</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Amazon</a
                >
              </li>
              <li>
                <a class="dropdown-item hvr-bubble-float-left my-2" href="#"
                  >Facebook</a
                >
              </li>
            </ul>
          </li>
        </ul>
        <form class="d-flex m-0" style="margin-left: 9rem">
          <input
            class="form-control me-1"
            style="background-color: transparent !important; color: orange"
            type="search"
            placeholder="Search"
            aria-label="Search"
          />
          <button
            class="btn hvr-sweep-to-right"
            style="color: white"
            type="submit"
          >
            Search
          </button>
        </form>
        <br />
        <button
          class="btn btn-outline hvr-sweep-to-right w-auto text-light"
          type="button"
          style="margin-left: 7rem"
        >
          Book Demo
        </button>
        <div class="d-flex align-content-center" style="margin-left: 5rem">
          <router-link to="/login"
            ><button class="btn btn-outline-primary m-1" type="button">
              Login
            </button></router-link
          >
          <router-link to="/"
            ><button class="btn btn-outline-primary m-1" type="button">
              Signup
            </button></router-link
          >
        </div>
      </div>
    </div>
  </nav>

  <router-view />
  <div class="navbar-expand-lg bg-dark">
    <footer class="p-5">
      <div class="row">
        <div class="col-6 col-md-2 mb-3">
          <h5>Socials</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Home</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Features</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Pricing</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">FAQs</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">About</a>
            </li>
          </ul>
        </div>

        <div class="col-6 col-md-2 mb-3">
          <h5>Partners</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Home</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Features</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Pricing</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">FAQs</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">About</a>
            </li>
          </ul>
        </div>

        <div class="col-6 col-md-2 mb-3">
          <h5>Pricing</h5>
          <ul class="nav flex-column">
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Home</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Features</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">Pricing</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">FAQs</a>
            </li>
            <li class="nav-item mb-2">
              <a href="#" class="nav-link p-0 text-muted">About</a>
            </li>
          </ul>
        </div>

        <div class="col-md-5 offset-md-1 mb-3">
          <form>
            <h5>Subscribe to our newsletter</h5>
            <p>Monthly digest of what's new and exciting from us.</p>
            <div class="d-flex flex-column flex-sm-row w-100 gap-2">
              <label for="newsletter1" class="visually-hidden"
                >Email address</label
              >
              <input
                id="newsletter1"
                type="text"
                class="form-control"
                placeholder="Email address"
              />
              <button class="btn btn-primary" type="button">Subscribe</button>
            </div>
          </form>
        </div>
      </div>

      <div
        class="d-flex flex-column flex-sm-row justify-content-between py-4 my-4 border-top"
      >
        <p>&copy; 2023 Company, Inc. All rights reserved.</p>
        <ul class="list-unstyled d-flex">
          <li class="ms-3">
            <a class="link-dark" href="#"
              ><svg class="bi" width="24" height="24">
                <use xlink:href="#twitter" />
              </svg>
            </a>
          </li>
          <li class="ms-3">
            <a class="link-dark" href="#"
              ><svg class="bi" width="24" height="24">
                <use xlink:href="#instagram" />
              </svg>
            </a>
          </li>
          <li class="ms-3">
            <a class="link-dark" href="#"
              ><svg class="bi" width="24" height="24">
                <use xlink:href="#facebook" />
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </footer>
  </div>
</template>

<style scoped lang="scss">
@import url("~/node_modules/hover.css/css/hover-min.css");

@import url("https://fonts.googleapis.com/css2?family=Maven+Pro&family=Poppins:wght@200&family=Qwitcher+Grypen:wght@700&display=swap");
#app {
  font-family: "Maven Pro", sans-serif;
  font-family: "Poppins", sans-serif;
  font-family: "Qwitcher Grypen", cursive;
}

h1 {
  color: #caa77f !important;
}

.bg-dark {
  background-color: black !important;
}

nav a.router-link-exact-active {
  border-bottom: 2px solid rgb(255, 149, 0);
  padding: 1px;
  color: white;
}

.dropdown-item:hover {
  background-color: black !important;
  color: orange;
}
@media (min-width: 350px) and (max-width: 950px) {
  .mobile-li {
    text-align: center;
    margin-left: 0 !important;
  }
}
</style>
