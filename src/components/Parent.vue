<template>
  <Child :msg="msg" />
</template>

<script>
  import Child from '~/components/Child'

  export default {
    components: {
      Child
    }
  }
</script>