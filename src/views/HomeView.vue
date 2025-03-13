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
            <img src="/png/pnpm-lock/切版直播班-W8-插圖_工作區域 1@2x.png" class="img-fluid bg-warning" alt="示例圖片">
          </div>
          <div class="col-md-6 d-flex align-items-center">
            <div>
              <div class="text-danger">
                <h4 class="pb-3">寵物服務，盡在 PETPET</h4>
                <p>當您的毛孩有需要時，幫您找到最合適的服務者！</p>
              </div>
              <div class="col-">
                <form action="/test.aspx" method="post">
                  <input type="number" value="50" min="10" max="100" step="10">
                  <input type="number" value="50" min="10" max="100" step="10">
                  <input type="number" value="50" min="10" max="100" step="10">
                  <button type="button" class="btn btn-danger rounded-0">搜尋</button>
                </form>
              </div>
            </div>
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
</style>
