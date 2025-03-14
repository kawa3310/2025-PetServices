<template>
  <div class="container">
    <nav class="d-flex justify-content-center border  justify-content-between align-items-center nav-side">
      <h1 class="text-warning">PETPET</h1>
      <div class="d-flex justify-content-center justify-content-center align-items-center gap-8">
        <a href="#" class="text-danger">預約服務</a>
        <a href="#" class="text-danger">成為寵物保姆</a>
        <a href="#" class="text-danger">登入</a>
      </div>
  </nav>
  </div>
  <header class="container">
    <div class="d-flex align-items-center">
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
  </header>
  <main class="main container mt-9">
    <div class="text-danger">
      <h1>本月熱門保姆</h1>
      <span class="fs-7">即時瞭解您的需求，安排最適合毛孩的寵物保姆！</span>
    </div>
    <div class="mt-2">
      <ul class="p-0 d-flex">
        <li class="col">
          <div class="card p-1 shadow-sm
          position-relative" style="width: 18rem;">
            <div class="pet-img">
              <img src="/png/krista-mangulsone-9gz3wfHr65U-unsplash.jpg" class="card-img-top rounded-0" alt="pet-img">
            </div>
            <div class="d-flex justify-content-center align-items-center">
            <div class="user-img position-absolute">
              <img src="/png/Ellipse 2.png" alt="login" style="width:100px;">
            </div>
            </div>
            <div class="card-body text-danger mt-5">
              <div class="d-flex flex-column
              justify-content-center text-center">
                <p class="card-text fs-7 mb-0">Jamie</p>
                <span>寄宿、美容、寵物行為訓練</span>
              <div class="pt-2">
              <button type="button" class="reserve-btn btn btn-primary">預約</button>
              </div>
              <div class="row d-flex justify-content-center align-items-center mt-4">
                <div class="col">
                  <span>獲得評價</span>
                  <div class="d-flex justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">580</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
                <div class="col">
                  <span>已完成訂單</span>
                  <div class="d-flex
                  justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">580</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
              </div>
              </div>
            </div>
          </div>
        </li>
        <li class="col">
          <div class="card p-1 shadow-sm
          position-relative" style="width: 18rem;">
            <div class="pet-img">
              <img src="/png/daniel-cano-dpb-qhtcA0A-unsplash.jpg" class="card-img-top rounded-0" alt="pet-img">
            </div>
            <div class="d-flex justify-content-center align-items-center">
            <div class="user-img position-absolute">
              <img src="/png/Ellipse 2拷貝.png" alt="login" style="width:100px;">
            </div>
            </div>
            <div class="card-body text-danger mt-5">
              <div class="d-flex flex-column
              justify-content-center text-center">
                <p class="card-text fs-7 mb-0">Eric</p>
                <span>寄宿、美容</span>
              <div class="pt-2">
              <button type="button" class="reserve-btn btn btn-primary">預約</button>
              </div>
              <div class="row d-flex justify-content-center align-items-center mt-4">
                <div class="col">
                  <span>獲得評價</span>
                  <div class="d-flex justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">76</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
                <div class="col">
                  <span>已完成訂單</span>
                  <div class="d-flex
                  justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">208</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
              </div>
              </div>
            </div>
          </div>
        </li>
        <li class="col">
          <div class="card p-1 shadow-sm
          position-relative" style="width: 18rem;">
            <div class="pet-img">
              <img src="/png/chewy-NVIyVF2Ecp0-unsplash.jpg" class="card-img-top rounded-0" alt="pet-img">
            </div>
            <div class="d-flex justify-content-center align-items-center">
            <div class="user-img position-absolute">
              <img src="/png/Ellipse 2拷貝2.png" alt="login" style="width:100px;">
            </div>
            </div>
            <div class="card-body text-danger mt-5">
              <div class="d-flex flex-column
              justify-content-center text-center">
                <p class="card-text fs-7 mb-0">Yvonne</p>
                <span>美容、寵物行為訓練</span>
              <div class="pt-2">
              <button type="button" class="reserve-btn btn btn-primary">預約</button>
              </div>
              <div class="row d-flex justify-content-center align-items-center mt-4">
                <div class="col">
                  <span>獲得評價</span>
                  <div class="d-flex justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">52</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
                <div class="col">
                  <span>已完成訂單</span>
                  <div class="d-flex
                  justify-content-center align-items-center mt-2">
                    <p class="fs-8 mb-0 fw-bold pe-1">196</p>
                    <span class="text-small">件</span>
                  </div>
                </div>
              </div>
              </div>
            </div>
          </div>
        </li>
      </ul>
    </div>
  </main>
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
  .main {
    padding: 0 85px;
  }
  .reserve-btn {
    width: 160px;
    border: #D5411A;
    padding: 12px 0;
  }
  .pet-img {
    height: 120px;
    img {
      height: 100%;
    }
  }
  .user-img {
    width: 100px;
    top: 20%;
    img{
      width: 100%;
    }
  }
  .text-small {
    font-size: 14px;
  }
</style>
