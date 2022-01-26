<template>
  <div class="about-card">
    <div class="card-title">
      <img src="../assets/logo-2.jpg" alt="avatar" class="avatar" />
      <div class="title-text-content">
        <p>About Me</p>
        <h2>Lotfy Mohamed</h2>
      </div>
    </div>
    <div class="card-content">
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis inventore
        blanditiis quos ipsam a, ratione odio harum velit sunt est aperiam eum
        odit amet voluptatibus minus voluptatum expedita iusto consequatur?
      </p>
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>PhotoShop , Figma, Canva, Adobe XD</td>
        </tr>
        <tr>
          <td>Front-End</td>
          <td>Vue.js , Reacr.js , Nuxt.js , HTML , CSS ,JS</td>
        </tr>
        <tr>
          <td>Bcak-End</td>
          <td>Node.js , Express.js , Mongo , Python</td>
        </tr>
        <tr>
          <td>ML</td>
          <td>ML5, TensorFlow, Algoriyhm Design</td>
        </tr>
        <tr>
          <td>Shop</td>
          <td>Stripe, PayFast, E-commerce, CMS</td>
        </tr>
      </table>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis inventore
        blanditiis quos ipsam a, ratione odio harum velit sunt est aperiam eum
        odit amet voluptatibus minus voluptatum expedita iusto consequatur?
      </p>

      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quis inventore
        blanditiis quos ipsam a, ratione odio harum velit sunt est aperiam eum
        odit amet voluptatibus minus voluptatum expedita iusto consequatur?
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about-card {
  height: 97vh;
  margin-right: 25px;
  background: #333;
  padding: 3em;
  border-radius: 10px;
  color: white;
  margin-left: 120px;
  .card-title {
    display: flex;
    align-items: center;
    background: #222;
    border-radius: 10px;
    img {
      width: 80px;
      height: 80px;
    }
    .avatar {
      border: 1px solid rgba(255, 255, 255, 0.4);
      border-radius: 50%;
      margin: 15px;
      // margin: 0 30px;
    }
    .title-text-content {
      p {
        margin-bottom: 0;
        color: rgb(210, 210, 210);
      }
      h2 {
        margin-top: 0;
      }
    }
  }
  .card-content {
    p {
      line-height: 1.5;
      margin: 30px auto;
    }
    table {
      border-spacing: 0px;
      margin: 50px auto;
      tr th,
      tr td {
        border: 1px solid white;
        border-top: none;
        padding: 10px;
        text-align: center;
        &:first-of-type {
          border-left: none;
        }
        &:nth-of-type(2) {
          border-right: none;
        }
      }
    }
  }
}

@media screen and (max-width: 1096px) {
  .about-card {
    margin-left: 0;
    height: 100%;
    margin-right: 0;
  }
}
</style>
