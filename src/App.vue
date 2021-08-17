<template>
  <div id="app-body" class="container mt-3">
    <div class="row primary-view">
      <div class="col">
        <InputList />
      </div>
      <div class="col">
        <ParserConfig />
      </div>
    </div>
  </div>
</template>

<script>
import 'bootstrap'
import 'bootstrap/dist/css/bootstrap.min.css';
import InputList from './components/InputList.vue'
import ParserConfig from './components/ParserConfig.vue'

export default {
  name: 'App',
  components: {
    InputList,
    ParserConfig
  }
}
</script>

<style>

</style>
