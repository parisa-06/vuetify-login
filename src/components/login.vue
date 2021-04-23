<template>
  <v-app id="inspire">
    <v-content>
      <v-container class="fill-height" fluid>
        <v-row align="center" justify="center">
          <v-col cols="12" sm="8" md="8">
            <v-card class="elevation-12">
              <v-window v-model="step">
                <v-window-item :value="1">
                  <v-row>
                    <v-col cols="12" md="5">
                      <v-card-text class="mt-12">
                        <h1
                          class="text-center display-1 teal--text text--accent-3"
                        >ورود به سهمان</h1>
                        <div class="text-center mt-1">
                         <v-icon>fab fa-linkedin-in</v-icon>
                         <p class="text-center " >اطلاعات وارد شده درست نمی‌باشد. </p>
                        </div>

                        <v-form>
                          <v-text-field
                            label="نام کاربری"
                            name="Email"
                            prepend-icon="email"
                            type="text"
                            color="teal accent-3"
                          />

                          <v-text-field
                            id="password"
                            label="پسورد"
                            name="password"
                            prepend-icon="lock"
                            type="password"
                            color="teal accent-3"
                          />
                        </v-form>
                        <h3 class="text-center display-6 mt-5">رمز عبورتان را فراموش کرده‌اید؟‌‌‌‌‌‌‌‌‌</h3>
                      </v-card-text>
                      <div class="text-center mt-3 mb-12">
                        <v-btn rounded color="teal accent-3" dark> ورود </v-btn>
                      </div>
                    </v-col>
                    <v-col cols="12" md="7" class="teal accent-3">
                      <v-card-text class="white--text mt-12">
                        <h1 class="text-center display-1"> سلام دوست من </h1>
                        <h5
                          class="text-center"
                        >
                        مشخصات شخصی خود را وارد کنید و عضوی از خانواده سهمان شوید.
                        </h5>
                      </v-card-text>
                      <div class="text-center">
                        <v-btn rounded outlined dark @click="step++"> ثبت نام</v-btn>
                      </div>
                    </v-col>
                  </v-row>
                </v-window-item>
                <v-window-item :value="2">
                  <v-row class="fill-height">
                    <v-col cols="12" md="7" class="teal accent-3">
                      <v-card-text class="white--text mt-12">
                        <h1 class="text-center display-1">خوش آمدید!</h1>
                        <h5
                          class="text-center"
                        >
                        برای ارتباط با ما لطفا مشخصات خود را وارد کنید.
                        </h5>
                      </v-card-text>
                      <div class="text-center">
                        <v-btn rounded outlined dark @click="step--">ورود</v-btn>
                      </div>
                    </v-col>

                    <v-col cols="12" md="5">
                      <v-card-text class="mt-12">
                        <h2 class="text-center display-6 teal--text text--accent-3"> ثبت اطلاعات مدیر و آموزشگاه  </h2>
                        <div class="text-center mt-4">
                          <h5
                          class="text-center"
                        >
                        برای ارتباط با ما لطفا مشخصات خود را وارد کنید.
                        </h5>
                        </div>
                        <h4 class="text-center mt-4">اطلاعات خودرا واردکنید</h4>
                        <v-form>
                          <v-text-field
                            label="نام کاربری"
                            name="Name"
                            prepend-icon="person"
                            type="text"
                            color="teal accent-3"
                          />
                          <v-text-field
                            label="ایمیل"
                            name="Email"
                            prepend-icon="email"
                            type="text"
                            color="teal accent-3"
                          />

                          <v-text-field
                            id="password"
                            label="رمز عبور"
                            name="password"
                            prepend-icon="lock"
                            type="password"
                            color="teal accent-3"
                          />
                        </v-form>
                      </v-card-text>
                      <div class="text-center mt-5 mb-12 ">
                        <v-btn rounded color="teal accent-3" dark>ورود</v-btn>
                      </div>
                    </v-col>
                  </v-row>
                </v-window-item>
              </v-window>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {
  data: () => ({
    step: 1
  }),
  props: {
    source: String
  }
};
</script>