<template>
      <v-container align="center" justify="center" fill-height>
        <v-row align="center" justify="center">
          <div class="text-center">
            <h1 class="mb-2">Profile Dashboard</h1>
          </div>
        </v-row>
        <v-row class="bg-img" justify="space-around">
          <v-col cols="12" class="mt-8">
            <v-card width="400">
              <v-img
                  height="200px"
                  src="http://ailab.siu.edu.vn/static/assets/images/ai-explore.jpg"
              >
                <v-app-bar
                    class="mt-8"
                    flat
                    color="rgba(0, 0, 0, 0)"
                >
                  <v-avatar size="100">
                    <img
                        alt="user"
                        src="http://ailab.siu.edu.vn/static/assets/images/img22.jpg"
                    >
                  </v-avatar>

                  <v-spacer></v-spacer>

                  <v-menu offset-y left>
                    <template v-slot:activator="{ on, attrs }">
                      <v-btn
                          v-bind="attrs"
                          v-on="on"
                          color="white"
                          icon
                      >
                        <v-icon>mdi-dots-vertical</v-icon>
                      </v-btn>
                    </template>
                    <v-list>
                      <v-list-item href="https://edu.fedorae.com">
                        <v-list-item-title>Edit</v-list-item-title>
                      </v-list-item>
                    </v-list>
                  </v-menu>

                </v-app-bar>

                <v-card-title class="white--text mt-8">
                  <p class="ml-3">
                    SIU AILAB
                  </p>
                </v-card-title>
              </v-img>

              <v-card-text>

                <div class="font-weight-bold ml-8 mb-2">
                  Details
                </div>

                <v-list two-line>
                  <v-list-item href="http://ailab.siu.edu.vn/home/">
                    <v-list-item-icon>
                      <v-icon color="indigo">
                        mdi-phone
                      </v-icon>
                    </v-list-item-icon>

                    <v-list-item-content>
                      <v-list-item-title>028.64093928</v-list-item-title>
                      <v-list-item-subtitle>Fax</v-list-item-subtitle>
                    </v-list-item-content>

                    <v-list-item-icon>
                      <v-icon>mdi-message-text</v-icon>
                    </v-list-item-icon>
                  </v-list-item>

                  <v-divider inset></v-divider>

                  <v-list-item href="http://ailab.siu.edu.vn/siubot/">
                    <v-list-item-icon>
                      <v-icon color="indigo">
                        mdi-email
                      </v-icon>
                    </v-list-item-icon>

                    <v-list-item-content>
                      <v-list-item-title>tranhamduong@siu.edu.vn</v-list-item-title>
                      <v-list-item-subtitle>Admin</v-list-item-subtitle>
                    </v-list-item-content>

                    <v-list-item-icon>
                      <v-icon>mdi-message-text</v-icon>
                    </v-list-item-icon>
                  </v-list-item>

                  <v-divider inset></v-divider>

                  <v-list-item href="http://ailab.siu.edu.vn/research">
                    <v-list-item-icon>
                      <v-icon color="indigo">
                        mdi-map-marker
                      </v-icon>
                    </v-list-item-icon>

                    <v-list-item-content>
                      <v-list-item-title>Address</v-list-item-title>
                      <v-list-item-subtitle>Online</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-list>
              </v-card-text>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
</template>

<script>
export default {
  name: "app-profile-contact-card"
}
</script>

<style>
.bg-img {
  background-image: url("https://bernardmarr.com/img/What%20is%20an%20Artificial%20Neural%20Networks.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center top;
  border-radius: 3px;
}
</style>