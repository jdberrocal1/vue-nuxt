<template>
  <div>
    <items></items>
  </div>
</template>

<script>
import items from "~/components/items.vue"

export default {
  components: {
    items
  },
  async fetch({store}){
    await store.dispatch("LOAD_ITEMS","askstories.json")
  }
}
</script>

<style>

</style>
