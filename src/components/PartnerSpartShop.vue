<template>
  <!-- Partner Logo Section Begin -->
  <div class="partner-logo">
      <div class="container-md">
          <carousel
            class="logo-carousel"
            :loop="true"
            :autoplay="true"
            :items="5"
            :dots="false"
            :nav="false" >
				<div class="logo-item ">
					<div class="tablecell-inner ">
						<img src="img/logo-carousel/deore.png"  class="text-center" alt />
					</div>
				</div>
				<div class="logo-item ">
					<div class="tablecell-inner">
						<img src="img/logo-carousel/polygon.png" class="text-center" alt />
					</div>
				</div>
					
				<div class="logo-item">
					<div class="tablecell-inner">
						<img src="img/logo-carousel/sram.png" class="text-center" alt="" />
					</div>
				</div>
					
				<div class="logo-item">
					<div class="tablecell-inner">
						<img src="img/logo-carousel/vortex.png" class="text-center" alt />
					</div>
				</div>
					
				<div class="logo-item">
					<div class="tablecell-inner">
						<img src="img/logo-carousel/shimano.png" class="text-center" alt />
					</div>
				</div>
				
          </carousel>
      </div>
  </div>
  <!-- Partner Logo Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";
export default {
  name: "PartnerSpartShop",
  components: {
    carousel,
  },
};
</script>