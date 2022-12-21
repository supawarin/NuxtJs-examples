<template>
  
  <div>
    <Slider />
    
    <Aboutus />
    
    <OurServices />

    <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">If you have any queries ?</h1>
            <h4>Please Reach out us at contact@example.com</h4>
    
          </div>
          <div class="col-md-4 text-center my-auto">
            <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary">Contact Us</NuxtLink>
          </div>



        </div>
      </div>
    </div>

    

  </div>
  
</template>

<script>

import Slider from '~/components/Slider.vue';
import Aboutus from '~/components/Aboutus.vue';
import OurServices from '~/components/OurServices.vue';
export default {
  name: 'IndexPage',
  components: { Slider, Aboutus, OurServices },
  head() {
    return {
      title: 'Home Page',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'NUXTJS Website Design - HomePage'
        },
        {
          hid: 'keywords',
          name: 'keywords',
          content: 'Vue, nuxt, javascript - HomePage'
        }
      ]
    }
  }
}
</script>
