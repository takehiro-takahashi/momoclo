<template lang="pug">
    #discography
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Discography extends Vue {
    page_name: string = 'Discography Page'
}
</script>

<style lang="stylus" scoped>

</style>
