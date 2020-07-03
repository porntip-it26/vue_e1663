<template>
  <v-container fluid class="pa-0">
    <v-row align="center">
      <v-col cols="12" sm="6">
        <div class="text-center">
          <div class="my-2">
            <nuxt-link to="/activity/flag">
              <v-btn color="secondary" dark large>กิจกรรมหน้าเสาธง</v-btn>
            </nuxt-link>
          </div>

          <div class="my-2">
            <nuxt-link to="/activity/home_room">
              <v-btn color="primary" dark large>กิจกรรมโฮมรูม</v-btn>
            </nuxt-link>
          </div>

          <div class="my-2">
            <nuxt-link to="/activity/society">
              <v-btn color="warning" dark large>กิจกรรมชมรม</v-btn>
            </nuxt-link>
          </div>

          <div class="my-2">
            <nuxt-link to="/activity/extra">
              <v-btn color="success" dark large>กิจกรรมพิเศษ</v-btn>
            </nuxt-link>
          </div>

           <div class="my-2">
            <nuxt-link to="/admin">
              <v-btn color="error" dark large>กลับหน้าหลัก</v-btn>
            </nuxt-link>
          </div>
          
       </div>
      </v-col>   
    </v-row>
  </v-container>
</template>