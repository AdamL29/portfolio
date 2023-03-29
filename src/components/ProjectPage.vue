<template>
    <v-container class="body">
        <div>
            <h1>Projects</h1>
            <p>Past projects and current projects can be found in my GitHub linked below.</p>
            <v-btn href="https://github.com/AdamL29"><v-icon>mdi-github</v-icon></v-btn>
        </div>
    </v-container>
</template>

<script>
    export default {
        name: "ProjectPage",
    }
</script>

<style lang="scss" scoped>
.body{
    height: 90vh;
}
</style>