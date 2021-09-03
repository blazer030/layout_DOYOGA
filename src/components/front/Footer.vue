<template>
  <footer class="bg-primary-dark text-white">
    <section class="border-bottom border-white py-8">
      <div class="container">
        <div class="row">
          <div class="col-12 col-xl-6 mb-2 mb-xl-0 d-flex align-items-center">
            <h4 class="fw-medium fs-md-3">現在訂閱，獲得課程優惠碼！</h4>
          </div>
          <div class="col-12 col-md-6 col-xl-4 offset-xl-2">
            <div class="input-group">
              <input type="text" class="form-control fs-5" placeholder="輸入您的電子信箱" />
              <button class="btn btn-primary text-white fs-5" type="button">訂閱</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="py-8">
      <div class="container position-relative">
        <div class="d-flex justify-content-between">
          <ul class="list-unstyled">
            <li class="mb-2">
              <img src="@/assets/image/DOYOGA.png" class="h-30p img-cover" alt="logo" />
            </li>
            <li class="mb-2">
              <router-link class="text-white fw-light" to="/">課程介紹</router-link>
            </li>
            <li class="mb-2">
              <router-link class="text-white fw-light" to="/">瑜珈空間</router-link>
            </li>
            <li>
              <router-link class="text-white fw-light" to="/">當月課表</router-link>
            </li>
          </ul>
          <ul class="list-unstyled d-flex">
            <li class="me-2">
              <a href="javascript:void(0);" class="text-white">
                <i class="fab fa-facebook fs-4"></i>
              </a>
            </li>
            <li class="me-2">
              <a href="javascript:void(0);" class="text-white">
                <i class="fab fa-instagram fs-4"></i>
              </a>
            </li>
            <li>
              <a href="javascript:void(0);" class="text-white">
                <i class="fab fa-line fs-4"></i>
              </a>
            </li>
          </ul>
        </div>
        <p class="mb-0 position-md-absolute bottom-0 start-50 translate-middle-md-x mt-2">
          © 2021. All Rights Reserved.
        </p>
      </div>
    </section>
  </footer>
</template>
