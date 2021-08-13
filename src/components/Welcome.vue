<template>
  <section
    id="welcome"
    class="overflow-hidden"
  >
    <v-row no-gutters>
      <v-col
        class="hidden-sm-and-down"
        md="6"
      >
        <v-img
          :src="require('@/assets/welcome.png')"
          height="100vh"
        />
      </v-col>

      <v-col
        class="align-content-space-between layout wrap"
        cols="12"
        md="6"
        :pa-5="$vuetify.breakpoint.smAndDown"
      >
        <base-bubble-1
          style="transform: rotate(180deg) translateY(25%)"
        />

        <v-row
          align="center"
          justify="center"
          class="pl-10"
        >
          <v-col
            cols="10"
            md="6"
            class="ma-5"
            align="center"
          >
            <base-heading>Welcome!</base-heading>
            <base-text>
              kkkkkkkoichiです！aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa<br>
            </base-text>
            <base-btn class="mt-4">
              よかったら下も見てね。
            </base-btn>
          </v-col>
        </v-row>

        <base-bubble-2
          style="transform: rotate(180deg) translate(-200px, -15%)"
        />
      </v-col>
    </v-row>
  </section>
</template>
<style scoped>

</style>
