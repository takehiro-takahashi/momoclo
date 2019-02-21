<template lang="pug">
    #movie
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Movie extends Vue {
    page_name: string = 'Movie Page'
}
</script>

<style lang="stylus" scoped>

</style>
