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
  background-color: #333;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  .nav-logo {
    margin: 20px;
    img {
      border-radius: 45px;
      width: 135px;
    }
  }
  .nav-menu {
    width: 100%;
    .nav-menu-list {
      list-style: none;
      padding: 0;
      display: flex;
      margin: 0;
      color: white;
      li {
        width: 50%;
        text-align: center;
        background-color: #555;
        padding: 10px 0;
        cursor: pointer;
        transition: background 300ms ease-in-out;
        &:hover {
          background-color: #333;
        }
        &:first-of-type {
          border-bottom: 5px solid #222;
        }
      }
    }
  }
}
</style>
