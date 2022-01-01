<template>
  <div id="index">
    <Header/>

    <main role="main">
      <latestSong :songTitle="songTitle"/>
    </main>

    <Footer/>
  </div>
  
</template>

<script>
import Header from '~/components/header_footer/Header'
import Footer from '~/components/header_footer/Footer'
import latestSong from '~/components/home_modules/latestSong'

export default {
  name: 'Index',
  components: {
      latestSong, Header, Footer
  },
  data() {
    return {
      homeData: [],
      songTitle: 'poisson'
    }
  },
  methods: {
    apparitions: function() {
    }
  }
}
</script>