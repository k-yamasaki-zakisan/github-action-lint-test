<template>
  <div>
    {{test}}
    <p>{{test2}}</p>
  </div>
</template>

<script lang="ts">
import { Vue } from 'nuxt-property-decorator'

export default class test extends Vue {
  get test() {
    return 'test'
  }

  get test2() {
    return this.test == 'test'
  }
}
</script>