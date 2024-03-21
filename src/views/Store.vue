<template>
    <div class="struct">
    <div class="card" v-for="item in $store.state.products" :key="item" style="width: 18rem;">
        <img :src="item.image" alt="" height="40%" width="50%">
            <div class="card-body">
              <h5 class="card-title">{{item.name}}</h5>
              <p class="card-text">{{item.description}}</p>
              <h6>R{{item.price}}.00</h6>
              <a href="#" class="btn btn-primary"><button>Add to cart</button></a>
            </div>
    </div>
</div>
</template>
<script>
// import Spinner from '@/components/Spinner.vue',

export default {
    data() {
      return {
        products:null,
      };
    },
    methods: {
    
    },
    computed: {
      async getProducts(){
         await this.$store.dispatch('getProducts')
        },
     async getproduct() {
      await this.store.dispatch('getProduct')
    },
    async deleteProduct() {
        await this.$store.dispatch('')
    }
      },
    mounted() {
      this.getProducts
      this.getProduct
      this.deleteProduct
    }
  };
</script>
<style>

.card {

  box-shadow: 1px 1px 5px rgb(255, 255, 255);
  transition: transform .9s;
flex-wrap: nowrap;
/* padding: 20px; */
height : 70vh;

border:1px solid black;
}

.card:hover {
  transform: scale(1.2);
}
    .struct  {
        justify-content:center;
        display: flex;
        flex-wrap:nowrap;
        padding:20px;
    }


</style>