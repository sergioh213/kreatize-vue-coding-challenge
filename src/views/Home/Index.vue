<!-- eslint-disable -->
<template>
  <!-- <v-layout> -->
    <v-card>
        <div slot="body" class="shadow">
            <div class="header">Shopping Basket</div>
            <div class="content_box">
                <div class="row">
                    <div class="grid_top">
                        <div class="grid_div">#</div>
                        <div class="grid_div">Name</div>
                        <div class="grid_div">Comments</div>
                        <div class="grid_div">Price</div>
                        <div class="grid_div">Tax</div>
                        <div class="grid_div">Total Item</div>
                    </div>
                </div>
                <div class="row">
                    <div class="grid_body">
                        <div class="grid_div">1</div>
                        <div class="grid_div">Product1</div>
                        <div class="grid_comment">Add a comment</div>
                        <div class="grid_div">0 €</div>
                        <div class="grid_div">19%</div>
                        <div class="grid_div">0 €</div>
                    </div>
                </div>
                <div class="cross_wrapper">
                    <i class="fas fa-times"></i>
                </div>
                <div class="row">
                    <div class="grid_body">
                        <div class="grid_div">2</div>
                        <div class="grid_div">Product2</div>
                        <div class="grid_comment">Add a comment</div>
                        <div class="grid_div">0 €</div>
                        <div class="grid_div">7%</div>
                        <div class="grid_div">0 €</div>
                    </div>
                </div>
                <div class="cross_wrapper">
                    <i class="fas fa-times"></i>
                </div>
                <div class="row">
                    <div class="grid_body">
                        <div class="grid_div">3</div>
                        <div class="grid_div">Product3</div>
                        <div class="grid_comment">Add a comment</div>
                        <div class="grid_div">0 €</div>
                        <div class="grid_div">19%</div>
                        <div class="grid_div">0 €</div>
                    </div>
                </div>
                <div class="cross_wrapper">
                    <i class="fas fa-times"></i>
                </div>
                <div id="btn_wrapper">
                    <div class="add_product scale">Add New Product</div>
                </div>
                <div id="total_wrapper">
                    <div id="total_grid">
                        <div class="total_grid_top">
                            <div class="grid_div">Total Brutto</div>
                            <div class="grid_num">0 €</div>
                        </div>
                        <div class="total_grid_body">
                            <div class="grid_div">Tax 19%</div>
                            <div class="grid_num">0 €</div>
                        </div>
                        <div class="total_grid_body">
                            <div class="grid_div">Tax 7%</div>
                            <div class="grid_num">0 €</div>
                        </div>
                        <div class="total_grid_body">
                            <div class="grid_div">Total Netto</div>
                            <div class="grid_num">0 €</div>
                        </div>
                    </div>
                </div>
                <div class="btn_order_wrapper">
                    <button class="order_button">Order</button>
                </div>
            </div>
        </div>
        <v-products>moreeee??</v-products>
    </v-card>
  <!-- </v-layout> -->
</template>

<script>
/* eslint-disable */
/* ============
 * Home Index Page
 * ============
 *
 * The home index page.
 */

import VLayout from '@/layouts/Default.vue';
import VCard from '@/components/Card.vue';
import VProducts from '@/components/Products.vue';
import styles from './index.css'; // //// styling //////

export default {
  /**
   * The name of the page.
   */
  name: 'HomeIndex',

  /**
   * The components that the page can use.
   */
  components: {
    // VLayout,
    VCard,
    VProducts
  },
};
</script>
