<template>
  <div class="content">
    <div class="left">
      <search-component />
      <list-component />
    </div>
    <div class="right">
      <content-component />
    </div>
  </div>
</template>
<script>
import SearchComponent from './components/SearchComponent.vue'
import ListComponent from './components/ListComponent.vue'
import ContentComponent from './components/ContentComponent.vue'

export default {
  components: {
    'search-component': SearchComponent,
    'list-component': ListComponent,
    'content-component': ContentComponent
  }
}
</script>
