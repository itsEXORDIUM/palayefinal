<template>
    <div id="latest_song">
        <h3>Listen to or buy {{songTitle}}</h3>
        <a href="deezer" :title="`Listen to ${songTitle} on Deezer (New Window)`" target="_blank"><span>Deezer</span></a>
    </div>
</template>

<script>
import axios from 'axios'

export default {
  components: {
  },
  props: {
    songTitle : String
  }
}
</script>