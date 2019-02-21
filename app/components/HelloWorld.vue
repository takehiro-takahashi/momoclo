<template>
    <div id="hello">{{ hello }}</div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class HelloWorld extends Vue {
    hello: string = 'Hello World!'
}
</script>

