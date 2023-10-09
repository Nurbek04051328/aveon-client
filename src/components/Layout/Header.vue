<template>
  <header class="header">
    <div class="header-top">
      <div class="header-top-search">
        <img src="../../assets/svg/header_search.svg" alt="search">
      </div>
      <a href="#" class="header-logo">Avion</a>
      <div class="header-top-right">
        <div class="header-top-right_cart">
          <a href="#">
            <img src="../../assets/svg/header_cart.svg" alt="cart">
          </a>
        </div>
        <div class="header-top-right_user">
          <a href="#">
            <img src="../../assets/svg/header_user.svg" alt="user">
          </a>
        </div>
      </div>
    </div>
  </header>
</template>


<style lang="scss" scoped>
.header {
  height: 132px;
  background: #fff;
  &-top {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    height: 70px;
    align-items: center;
    &-right {
      display: flex;
      align-items: center;
      &_cart {
        margin-right: 16px;
      }
    }
  }
  &-logo {
    font-family: 'Putumayo', sans-serif;
    color: #22202E;
    font-size: 24px;
    text-decoration: none;
    &:hover {
      text-decoration: underline;
    }
  }
  
}
</style>