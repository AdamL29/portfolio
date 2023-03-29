<template>
    <v-container>
        <footer>
            <h4>COPYRIGHT © 2023 by Adam</h4>
            <h4>Contact Me: Adamlederer@live.ca</h4>

        </footer>
    </v-container>
</template>

<script>
import router from '@/router';

export default {
    name: 'FooterBar',
    methods: {
        support() {
            router.push('/support')
        }
    },
}
</script>

<style lang="scss" scoped>
footer{
    position: absolute;
    bottom: 5px;
    left: 50%;
    transform: translateX(-50%);
}
</style>