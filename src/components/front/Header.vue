<template>
  <header class="navbar navbar-expand-xl bg-secondary py-6 py-md-7">
    <div class="container">
      <router-link to="/">
        <img src="@/assets/image/DOYOGA-logo.png" class="h-30p" alt="logo" />
      </router-link>
      <button
        class="navbar-toggler p-0"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarContent"
        aria-controls="navbarContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="material-icons text-primary-dark fs-2">
          menu
        </span>
      </button>
      <div class="collapse navbar-collapse" id="navbarContent">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item">
            <router-link class="nav-link fw-light" to="/">
              課程介紹
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link fw-light" to="/">
              瑜珈空間
            </router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link fw-light" to="/">
              當月課表
            </router-link>
          </li>
        </ul>
        <form class="d-flex">
          <router-link class="btn btn-outline-primary-dark rounded-3 me-4" to="/">
            立即預約
          </router-link>
          <router-link class="btn btn-outline-primary-dark rounded-3" to="/">
            聯絡我們
          </router-link>
        </form>
      </div>
    </div>
  </header>
</template>
