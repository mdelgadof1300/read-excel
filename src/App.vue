<template>

  <router-view/>
  <Input/>
  <Table/>
</template>

<style>

</style>

<script>

import Input from '@/components/Input.vue'
import Table from './components/Table.vue';

export default {
  name: 'HomeView',
  components: {
    Input,
    Table
  }
}
</script>
