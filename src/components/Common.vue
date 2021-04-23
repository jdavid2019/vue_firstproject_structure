<template>
  <div>
    <h1>{{ sms }}</h1>
    <p>{{crack}}</p>
  </div>
</template>
<script>
export default {
  name: 'Common',
  props:{
    sms: String
},
  data() {
    return {
      crack: 'This is a example about the name'
    }
  }
}
</script>

<style>

</style>