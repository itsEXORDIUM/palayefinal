<template>
    <header role="banner">
        <h1>Nuxt Base</h1>
        <uiNav/>
    </header>
</template>

<script>
import uiNav from '~/components/header_footer/uiNav'

export default {
  components: {
      uiNav
  }
}
</script>