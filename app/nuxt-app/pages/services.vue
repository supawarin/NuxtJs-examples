<template>
      <div>
            <div class="py-4 bg-info">
                  <div class="container">
                        <h1 class="about-text">Our Services</h1>
                  </div>
            </div>
            <OurServices />
      </div>
</template>

<script>
import OurServices from '~/components/OurServices.vue';
export default {
      name: 'services',
      components: { OurServices },
      head() {
            return {
                  title: 'Our Services',
                  meta: [
                        {
                              hid: 'description',
                              name: 'description',
                              content: 'NUXTJS Website Design - Services'
                        },
                        {
                              hid: 'keywords',
                              name: 'keywords',
                              content: 'Vue, nuxt, javascript - Services'
                        }
                  ]
            }
      }
}

</script>

<style lang="scss" scoped>

</style>