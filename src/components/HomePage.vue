<template>
  <v-container class="body">
    <v-row class="text-center">
      <v-col class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">
          Welcome to My Basic Portfolio!
        </h1>

        <p class="subheading font-weight-regular">
          Here you can learn more about me, see the work and projects that I have done
          as well as projects I am currently working on through my GitHub link below.
        </p>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          About Me
        </h2>

        <v-row justify="center">
          <p>
            Hello, my name is Adam Lederer, and I just recently became a Full-Stack Developer.
            <br>
            <br>
            Growing up I was always found playing with technology and games. It became who I was as I went through my teenage years.
            I was the student that helped the teachers get their computers working or helped make sure the projectors were operating properly.
            Over the years, I enjoyed learning more about more about the inner workings of technology. Recently, I chose to step into the realm
            of programming the technology instead. This lead me to Full-Stack Development and I am hoping to use this knowledge to learn
            more languages and increase my knowledge into more programming. 
            <br>
            <br>
            Feel free to contact me if you would like to know me with the button above.
          </p>
        </v-row>
      </v-col>

      <v-col
        class="mb-5"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3">
          Skills & Technologies
        </h2>

        <v-row justify="center">
          <p>Skilled in API Testing with Postman.
            Database building in DBeaver.
            Usage of Git & GitHub for repositories and collaboration.
            Deploying web domains through GCP.
          </p>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'HomePage',

    data: () => ({
      reference: [
        {
          text: 'github',
          href: 'https://github.com/AdamL29',
        },
      ],
    }),
  }
</script>

<style scoped>
.body{
    height: 90vh;
}
.text-center{
  position: absolute;
  top: 10px;
  left: 50%;
  transform: translateX(-50%);
}
</style>