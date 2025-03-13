<template>
    <div class="container">
    <div class="d-flex border  justify-content-between align-items-center nav-side">
      <h1 class="text-warning">PETPET</h1>
      <div class="d-flex justify-content-center align-items-center gap-8">
        <a href="#" class="text-danger">預約服務</a>
        <a href="#" class="text-danger">成為寵物保姆</a>
        <a href="#" class="text-danger">登入</a>
      </div>
    </div>
  </div>
  <div class="container">
      <div class="container d-flex align-items-center">
        <div class="row w-100">
          <div class="col-md-6">
            <img src="https://github.com/kawa3310/2025-PetServices/blob/main/png/pnpm-lock/%E5%88%87%E7%89%88%E7%9B%B4%E6%92%AD%E7%8F%AD-W8-%E6%8F%92%E5%9C%96_%E5%B7%A5%E4%BD%9C%E5%8D%80%E5%9F%9F%201@2x.png?raw=true" class="img-fluid bg-warning" alt="示例圖片">
          </div>
          <div class="col-md-6 d-flex align-items-center position-relative">
            <div>
              <div class="text-danger">
                <h4 class="pb-3">寵物服務，盡在 PETPET</h4>
                <p>當您的毛孩有需要時，幫您找到最合適的服務者！</p>
              </div>
              <div class="col">
                <form class="d-flex justify-content-center">
                  <input type="number" class="ps-3" placeholder="品種">
                  <input type="number" class="ps-3" placeholder="服務">
                  <input type="number" class="ps-3" placeholder="地區">
                  <button type="button" class="btn btn-primary select-btn">搜尋</button>
                </form>
              </div>
            </div>
            <a href="#" class="push-down position-absolute">
              <i class="bi bi-caret-down-fill"></i>
            </a>
          </div>
        </div>
      </div>
  </div>
</template>


<style>
  .nav-side {
    padding: 0px 85px 0px 85px;
  }
  a {
    text-decoration: none;
  }
  input {
    width: 120px;
    border: 1px solid #CED4DA;
  }
  .select-btn {
    width: 95px;
    border: 1px solid #CED4DA;
    border-radius: 0 5px 5px 0px;
    font-size: 20px;
    padding: 9px 0;
  }
  .push-down {
    background-color: #D54100;
    border-radius: 60px;
    color: white;
    padding: 10px;
    bottom: 5%;
    left: 69%;
  }
  .bi-caret-down{
    color: #ff6600;
  }
</style>
