<template>
  <section class="nav">
    <div class="nav-logo">
      <img src="../assets/image.jpg" alt="logo" />
    </div>
    <div class="nav-menu">
      <ul class="nav-menu-list">
        <li class="nav-menu-item">Home</li>
        <li class="nav-menu-item">About</li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.nav {
  position: fixed;
  left: 0;
  top: 0;
  bottom: 0;
  background-color: #333;
  flex-direction: column;
  align-items: center;
  // width: 9vw;
  .nav-logo {
    margin: 100px auto;
    padding: 0 10px;
    img {
      border-radius: 50%;
      width: 90px;
    }
  }
  .nav-menu {
    color: white;
    padding: 0 10px;
    .nav-menu-list {
      list-style: none;
      padding: 0;
      .nav-menu-item {
        background-color: #222;
        padding: 10px 20px;
        text-align: center;
        margin: 10px auto;
        cursor: pointer;
        &:hover {
          width: 100px;
        }
      }
    }
  }
}

@media screen and (max-width: 1096px) {
  #desktop {
    display: none;
  }
}
</style>
