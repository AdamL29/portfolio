<template>
    <v-toolbar color="orange">
        <template v-slot:prepend>
            <div class="text-h5">Title</div>
        </template>

        <v-divider
            class="ms-3"
            inset
            vertical
        ></v-divider>
    
        <v-btn @click="goHome"><v-icon>mdi-home</v-icon></v-btn>

        <h1>Adam Lederer</h1>
    
        <v-spacer></v-spacer>
    
        <v-spacer></v-spacer>

        <v-btn @click="projects" variant="text">Projects</v-btn>
        <!-- <v-btn @click="contact" variant="text">Contact</v-btn> -->

        <v-divider vertical></v-divider>
    </v-toolbar>
</template>

<script>
import router from '@/router'

export default {
    name: 'AppBar',
    methods: {
        goHome(){
            router.push('/')
        },
        projects() {
            router.push('/projects')
        },
        // contact() {
        //     router.push('/contact')
        // }
    },
}
</script>

<style scoped>
.appBar{
    height: 10px;
}
h1{
    position: absolute;
    left: 50%;
    transform: translateX(-50%);
}
</style>