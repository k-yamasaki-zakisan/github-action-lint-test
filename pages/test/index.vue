<template>
  <div>{{test}}</div>
</template>

<script lang="ts">
import { Vue } from 'nuxt-property-decorator'

export default class extends Vue {
  get test() {
    return 'test'
  }
}
</script>