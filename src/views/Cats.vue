<template>
    <div>
        <h1>Cats for Adoption</h1>
       <b-table striped hover :items="cats" />
    </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
    data(){
        return {}
    },
    computed: {
    ...mapState([
      'cats'
    ])
  }
}
</script>