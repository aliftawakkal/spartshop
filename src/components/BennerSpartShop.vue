<template>
  <!-- Women Banner Section Begin -->
  <section class="women-banner spad">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-12 mt-5">
          <carousel class="product-slider" :items="3" :dots="false" :nav="false" :autoplay="true">
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mtb/bracket/sdeore/PistonResinpad.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <router-link to="/product">+ Review Barang</router-link>
                  </li>
                </ul>
              </div>
                <div class="pi-text">
                    <div class="catagory-name">Coat</div>
                    <router-link to="/product">
                        <a href="#">
                            <h5>Bracket</h5>
                        </a>
                    </router-link>
                    <div class="product-price">
                        $14.00
                        <span>$35.00</span>
                    </div>
                </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mtb/cable/shifting/shifting_cable_1.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Shoes</div>
                <a href="#">
                  <h5>Shifting Deore</h5>
                </a>
                <div class="product-price">$13.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mtb/crankset/crank_1.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Cransek SLX</div>
                <a href="#">
                  <h5>Crankset SLX</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mtb/freehub/black.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                  <!-- <li class="w-icon">
                    <a href="#">
                      <i class="fa fa-random"></i>
                    </a>
                  </li> -->
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Free Hub</div>
                <a href="#">
                  <h5>Free Hub Shimano</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
            <div class="product-item">
              <div class="pi-pic">
                <img src="img/mtb/groupset/deore_1.jpeg" alt />
                <ul>
                  <li class="w-icon active">
                    <a href="#">
                      <i class="icon_bag_alt"></i>
                    </a>
                  </li>
                  <li class="quick-view">
                    <a href="#">+ Quick View</a>
                  </li>
                  <!-- <li class="w-icon">
                    <a href="#">
                      <i class="fa fa-random"></i>
                    </a>
                  </li> -->
                </ul>
              </div>
              <div class="pi-text">
                <div class="catagory-name">Groupset</div>
                <a href="#">
                  <h5>Sunrace</h5>
                </a>
                <div class="product-price">$34.00</div>
              </div>
            </div>
          </carousel>
        </div>
      </div>
    </div>
  </section>
  <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "BennerSpartShop",
  components: {
    carousel,
  },
};
</script>

<style scoped>
.product-item {
  margin-right: 25px;
}
</style>