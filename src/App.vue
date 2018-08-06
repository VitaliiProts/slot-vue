<template>
  <div id="app">
    <hello>
      Hello World alalalal
    </hello>
  </div>
</template>

<script>
import Hello from './components//Hello.vue';

export default {
  name: 'app',
  data () {
    return {
      message: 'From parent'
    }
  },
  components: { Hello }
}
</script>

<style></style>
