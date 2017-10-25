<template>
  <div>
    <h3>{{user.id}} has been a user {{user.created | timeSince}}</h3>
  </div>
</template>

<script>
  import axios from "~/plugins/axios"
  export default {
    async asyncData({route}){
      const response = await axios.get(`/user/${route.params.id}.json`)
      return {user: response.data}
    }
  }
</script>
