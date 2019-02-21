<template lang="pug">
    #link
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Link extends Vue {
    page_name: string = 'Link Page'
}
</script>

<style lang="stylus" scoped>

</style>
