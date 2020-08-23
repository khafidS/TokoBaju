<template>
  <section class="ShoppingCart">
    <HeaderMastore />
    <!-- Breadcrumb Section Begin -->
    <div class="breacrumb-section text-left">
        <div class="container">
            <div class="row">
                <div class="col-lg-12">
                    <div class="breadcrumb-text product-more">
                        <router-link to="/"><i class="fa fa-home"></i> Home</router-link>
                        <span>Shopping Cart</span>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Breadcrumb Section Begin -->
    <ShoppingCartComp/>
    <FooterMastore />
  </section>
</template>

<script>
import HeaderMastore from '@/components/HeaderMastore.vue'
import FooterMastore from '@/components/FooterMastore.vue'
import ShoppingCartComp from '@/components/ShoppingCartComp.vue'

export default {
  name:"ShoppingCart",
  components: {
    HeaderMastore,
    FooterMastore,
    ShoppingCartComp
  }
  
}
</script>