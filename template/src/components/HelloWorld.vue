<template>
  <div>{{name}}, Hello World!</div>
</template>

<script lang='ts'>
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component({})
export default class HelloWorld extends Vue {
  @Prop() name!: string
}
</script>
