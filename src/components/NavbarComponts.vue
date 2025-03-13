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
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
