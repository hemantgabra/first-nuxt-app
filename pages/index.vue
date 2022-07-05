<template>
  <div class="container">
    <div class="row">
      <div class="col-6"><h1>This is the Home Page</h1></div>
      <div class="col-6 mt-3"><Header></Header></div>
    </div>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
export default {
  components: Header,
}
</script>

<style>
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
ul.topNav {
  list-style: none;
  display: flex;
}
ul.topNav li {
  padding: 0 20px;
}
</style>
