<template>
      <v-container class="fill-height" fluid>
        <v-row align="center" justify="center" dense>
          <v-col cols="12" sm="8" md="4" lg="4">
            <v-card elevation="0">
              <div class="text-center">
                <h1 class="mb-2"></h1>
              </div>
              <a href="https://edu-fedorae.netlify.app" name="Fedorae Education" title="Fedorae Education" target="_blank">
                <v-img src="@/assets/AI_Lab-trans.png" alt="Fedorae Education Log" contain height="200"></v-img>
              </a>
              <v-card-text>
                <v-form>
                  <v-text-field label="Enter your name" name="name" prepend-inner-icon="mdi-account" type="text" class="rounded-0" outlined></v-text-field>
                  <v-text-field label="Enter your email" name="email" prepend-inner-icon="mdi-email" type="email" class="rounded-0" outlined></v-text-field>
                  <v-text-field label="Enter your password" name="password" prepend-inner-icon="mdi-lock" type="password" class="rounded-0" outlined></v-text-field>
                  <v-text-field label="Re-enter password" name="password" prepend-inner-icon="mdi-lock-outline" type="password" class="rounded-0" outlined></v-text-field>
                  <v-btn class="rounded-0" color="#000000" x-large block dark>Register</v-btn>
                  <v-card-actions class="text--secondary">
                    <v-spacer></v-spacer>
                    <!-- <router-link :to="{ name: 'SignUp' }">Sign Up</router-link> -->
                    Already have an account? <a href="#" class="pl-2" style="color: #000000">Sign In</a>
                  </v-card-actions>
                </v-form>
              </v-card-text>
              <v-card-actions class="ml-6 mr-6 text-center">
                <!-- <p>By continuing, you agree to<a href="#" class="pl-2" style="color: #000000">Policy</a> and <a href="#" class="pl-2" style="color: #000000">Terms of Use</a></p> -->
                <h3>Hỗ trợ công nghệ: <span class="blue--text">tranhamduong@siu.edu.vn</span></h3>
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
</template>

<script>
export default {
  name: "app-register"
}
</script>

<style lang="css" scoped>
</style>
