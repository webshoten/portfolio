<template>
  <v-card
    class="mx-auto"
    max-width="434"
    tile
  >
    <v-img
      height="100%"
      src="img/nav3.jpg"
    >
      <v-row
        align="end"
        class="fill-height"
      >
        <v-col
          align-self="start"
          class="pa-0"
          cols="12"
        >
          <v-avatar
            class="profile"
            color="grey"
            size="124"
          >
            <v-img src="img/me.jpg"></v-img>
          </v-avatar>
        </v-col>
        <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
              <v-img
                max-height="20"
                max-width="20"
                src="img/javascript.svg"
              ></v-img>
                Javascript
              </v-list-item-title>
              <v-list-item-subtitle>
              <v-rating
                background-color="orange lighten-3"
                color="orange"
                readonly
                value="3"
              ></v-rating>
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
                <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
              <v-img
                max-height="20"
                max-width="20"
                src="img/dotnet.svg"
              ></v-img>
                VB.NET
              </v-list-item-title>
              <v-list-item-subtitle>
              <v-rating
                background-color="orange lighten-3"
                color="orange"
                readonly
                value="3"
              ></v-rating>
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
               <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
              <v-img
                max-height="20"
                max-width="20"
                src="img/c-sharp.svg"
              ></v-img>
                C#
              </v-list-item-title>
              <v-list-item-subtitle>
              <v-rating
                background-color="orange lighten-3"
                color="orange"
                readonly
                value="3"
              ></v-rating>
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
                <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
              <v-img
                max-height="20"
                max-width="20"
                src="img/aws.svg"
              ></v-img>
                AWS
              </v-list-item-title>
              <v-list-item-subtitle>
              <v-rating
                background-color="orange lighten-3"
                color="orange"
                readonly
                value="2"
              ></v-rating>
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
                <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
              <v-img
                max-height="20"
                max-width="20"
                src="img/azure-icon.svg"
              ></v-img>
                Azure
              </v-list-item-title>
              <v-list-item-subtitle>
              <v-rating
                background-color="orange lighten-3"
                color="orange"
                readonly
                value="3"
              ></v-rating>
              </v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>

        <v-col class="py-0">
          <v-list-item
            color="rgba(0, 0, 0, .4)"
            dark
          >
            <v-list-item-content>
              <v-list-item-title class="text-h6">
                Hiroyuki Oshima
              </v-list-item-title>
              <v-list-item-subtitle>System Engineer,System Architect</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-col>
      </v-row>
    </v-img>
  </v-card>
</template>
