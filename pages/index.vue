<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="6" md="6">
      <v-card class="logo py-4 d-flex justify-center">
        <NuxtLogo />
        <!-- <VuetifyLogo /> -->
      </v-card>
      <v-card>
        <v-card-title class="headline">
          こんにちは
        </v-card-title>
        <v-card-text>
          <p>よろしくお願いいたします。</p>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>
