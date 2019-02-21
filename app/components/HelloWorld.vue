<template lang="pug">
    #hello
        p {{ hello }}
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
    hello: string = 'Hello World!'
}
</script>

<style lang="stylus" scoped>
    #hello
        color: blue
</style>
