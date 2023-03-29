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
    
        <v-toolbar-title>Adam</v-toolbar-title>
    
        <v-spacer></v-spacer>
    
        <v-spacer></v-spacer>

        <v-btn variant="text">Projects</v-btn>
        <v-btn variant="text">Contact</v-btn>

        <v-divider vertical></v-divider>
    </v-toolbar>
</template>

<script>

export default {
    name: 'AppBar',
};
</script>

<style scoped>
.appBar{
    height: 10px;
}
</style>