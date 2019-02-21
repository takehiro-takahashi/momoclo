<template lang="pug">
    #profile
        p {{ page_name }}
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator'
@Component
export default class Profile extends Vue {
    page_name: string = 'Profile Page'
}
</script>

<style lang="stylus" scoped>

</style>
