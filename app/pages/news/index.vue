<template lang="pug">
    #news
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class News extends Vue {
    page_name: string = 'News Page'
}
</script>

<style lang="stylus" scoped>

</style>
