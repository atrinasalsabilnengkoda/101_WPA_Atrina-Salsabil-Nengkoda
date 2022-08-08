<template>
  <Banner />
  <Visimisi />
  <Service />
  <Ourwork />
  <Testimoni />
  <Joinus />
</template>

<script>
import Banner from '../components/Banner.vue';
import Visimisi from '../components/Visimisi.vue';
import Service from '../components/Service.vue';
import Ourwork from '../components/Ourwork.vue';
import Testimoni from '../components/Testimoni.vue';
import Joinus from '../components/Joinus.vue'
import Contact from '../components/Contact.vue'

export default{
  components: {
    Banner,
    Visimisi,
    Service,
    Ourwork,
    Joinus,
    Contact,
  },
}
</script>
