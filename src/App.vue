<template>
  <div id="app">
    <!-- <task-list /> -->
    <InboxScreen/>
  </div>
</template>

<script>
  //import TaskList from './components/TaskList.vue';
  import InboxScreen from './components/InboxScreen.vue'
  export default {
    name: 'app',
    components: {
      //TaskList,
      InboxScreen
    },
  };
</script>
<style>
  @import './index.css';
</style>