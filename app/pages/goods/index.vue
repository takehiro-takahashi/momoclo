<template lang="pug">
    #goods
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Goods extends Vue {
    page_name: string = 'Goods Page'
}
</script>

<style lang="stylus" scoped>

</style>
