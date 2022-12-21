<template>
      <div>
         <div class="py-4 bg-success">
            <div class="container">
                  <h1 class="about-text">About Us</h1>
            </div>
         </div>
         <Aboutus />
         <div class="py-5 bg-gray">
            <div class="container">
                  <div class="row">
                        <div class="col-md-6">
                              <img src="/images/iStock-2.jpg" class="w-100" alt="Web Designing">
                        </div>
                        <div class="col-md-6">
                              <p><b><i>Where does it come from?</i></b><br />
                              Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature
                              from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia,
                              looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of
                              the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33
                              of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise
                              on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit
                              amet..", comes from a line in section 1.10.32.
                              
                              The standard chunk of Lorem Ipsum used since the 1500s is reproduced below for those interested. Sections 1.10.32 and
                              1.10.33 from "de Finibus Bonorum et Malorum" by Cicero are also reproduced in their exact original form, accompanied by
                              English versions from the 1914 translation by H. Rackham.</p>
                        </div>
                  </div>
            </div>
         </div>

        
      </div>
</template>

<script>
import Aboutus from '~/components/Aboutus.vue';
export default {
      name: 'about',
      components: { Aboutus },
      head() {
            return {
                  title: 'About Us',
                  meta: [
                        {
                              hid: 'description',
                              name: 'description',
                              content: 'NUXTJS Website Design - About Us'
                        },
                        {
                              hid: 'keywords',
                              name: 'keywords',
                              content: 'Vue, nuxt, javascript - About Us'
                        }
                  ]
            }
      }
}

</script>

<style>
.about-text {
      color: #fff;
}
</style>