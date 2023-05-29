<template>
    <div class="index">
      <section>
        <HeroIndex></HeroIndex>
      </section>
      <section>
        <ProductIndex></ProductIndex>
      </section>
      <section>
        <BestProductIndex></BestProductIndex>
      </section>
    </div>
</template>

<!-- <script>
import axios from 'axios'
export default{
  async asyncData(){
    const { data } = await axios.get('https://dummyjson.com/products')
    return {
      products: data
    }
  }
}
</script> -->