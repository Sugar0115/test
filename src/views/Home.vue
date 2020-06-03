<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <tinymce :height='500'  ref='Tinymce'/>
  </div>
</template>

<script>
// @ is an alias to /src
import tinymce from '@/components/Tinymce'

export default {
  name: 'Home',
  components: {
    tinymce
  }
}
</script>
