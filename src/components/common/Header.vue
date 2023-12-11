<template>
  <nav
    class="navbar navbar-expand-lg navbar-dark bg-dark px-5 d-flex justify-content-between">
    <div>
      <a
        class="navbar-brand"
        href="#"
        >BookStore</a
      >
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span
          class="navbar-toggler-icon"></span>
      </button>
    </div>

    <div
      class="collapse navbar-collapse float-end"
      id="navbarSupportedContent">
      <ul
        class="navbar-nav mr-auto">
        <li
          class="nav-item active">
          <RouterLink
            class="nav-link active"
            to="/"
            >Home</RouterLink
          >
        </li>
        <li
          class="nav-item">
          <RouterLink
            class="nav-link active"
            to="/about"
            >About</RouterLink
          >
        </li>
        <li
          class="nav-item">
          <RouterLink
            class="nav-link active"
            to="/Cart"
            >Cart</RouterLink
          >
        </li>
        <li
          class="nav-item">
          <RouterLink
            class="nav-link active"
            to="/signIn"
            >sign
            in</RouterLink
          >
        </li>
        <!-- <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            Dropdown
          </a>
        
          
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#">Disabled</a>
        </li> -->
      </ul>
      <!-- <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form> -->
    </div>
  </nav>
</template>
<script>
import {
  RouterLink,
  RouterView,
} from "vue-router";
export default {
  name: "Header",
  components:
    {},
  data() {
    return {};
  },
  methods() {},
  beforeMount() {},
};
</script>
