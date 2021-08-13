<template>
  <div class="welcome">
      <v-sheet
        class="overflow-y-auto"
        max-height="600"
      >
      <v-row>
        <v-col cols="6" class="pr-0">
          <v-img
          :src="require('@/assets/welcome.png')"
          height="100vh"
        />
        </v-col >
        <v-col class="pr-0"> 

        </v-col>
      </v-row>
      </v-sheet>
  </div>
</template>
<script>

export default({
    name: 'Welcome'
})
</script>

