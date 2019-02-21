<template lang="pug">
    #schedule
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Schedule extends Vue {
    page_name: string = 'Schedule Page'
}
</script>

<style lang="stylus" scoped>

</style>
