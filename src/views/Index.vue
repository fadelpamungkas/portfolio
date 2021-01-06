<template>
    <div class="profile-page">
        <section class="section section-shaped section-lg my-0">
            <div class="shape shape-style-1 shape-primary alpha-4"/>
            <div class="container">
                <card shadow class="card-profile my-0" no-body>
                    <div class="px-4">
                        <div class="img-center">
                          <div class="card-profile-image">
                              <img v-lazy="'img/theme/photo.jpg'" class="rounded">
                          </div>
                        </div>
                        <div class=" text-center">
                            <div class="card-profile-actions pt-150">
                                <h3>Fadel Pamungkas, 20
                                </h3>
                                <div class="h6 font-weight-300"><i class="ni location_pin mr-2"></i>Indonesian</div>
                                <div class="h6 mt-4"><i class="ni business_briefcase-24 mr-2"></i>Undergraduate Informatics Student</div>
                                <div><i class="ni education_hat mr-2"></i>Universitas Islam Indonesia</div>
                            </div>
                        </div>
                        <div class="text-center">
                            <div class="card-profile-stats d-flex justify-content-center">
                                <div>
                                    <a class="nav-link nav-link-icon" href="https://www.linkedin.com/in/fadel-pamungkas-310b4183" target="_blank" rel="noopener"
                                       data-toggle="tooltip">
                                        <i class="fa fa-linkedin"></i>
                                    </a>
                                    <span class="description">fadelpamungkas</span>
                                </div>
                                <div>
                                    <a class="nav-link nav-link-icon">
                                        <i class="fa fa-envelope"></i>
                                    </a>
                                    <span class="description">fadelpamungkas3@gmail.com</span>
                                </div>
                            </div>
                        </div>
                        <div class=" py-5 border-top text-center">
                            <div class="row justify-content-center">
                                <div class="col-lg-9">
                                    <p>Interest in Android development with Java and Kotlin as main languages. Also have some basic in cybersecurity and cloud computing.</p>
                                </div>
                            </div>
                        </div>

                        <div class=" mb-4 justify-content-center">
                            <div class=" mt-lg-0">
                                <!-- Menu -->
                                <tabs fill class="flex-column flex-md-row ">
                                    <card shadow class="card-profile my-0" >
                                        <tab-pane>
                                            <template slot="title">
                                                <i class="ni ni-book-bookmark mr-2"></i>Resume
                                            </template>
                                            <div>
                                                <h3 class="h4 text-primary font-weight-bold ml-5">Experience</h3>
                                                <div class="row py-3 align-items-center">
                                                    <div class="col-sm-3 col-6 mt-5 mt-sm-0 text-center">
                                                        <img v-lazy="'img/theme/team-3-800x800.jpg'" alt="Raised image" class="img-fluid rounded shadow-lg"
                                                             style="width: 100px;">
                                                    </div>
                                                    <div class="col-sm-9">
                                                      <h5 class="mb-0 font-weight-bold">Experience 1</h5>
                                                      <p class="text-muted">4 years • Yogyakarta, Indonesia</p>
                                                      <p>dsadjnasdksandksndskadnsakdnadnak</p>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class=" py-5 border-top">
                                                <h3 class="h4 text-primary font-weight-bold ml-5">Education</h3>
                                                <div class="row py-3 align-items-center">
                                                    <div class="col-sm-3 col-6 mt-5 mt-sm-0 text-center">
                                                        <img v-lazy="'img/theme/UII - Biru.png'" alt="Raised image" class="img-fluid rounded shadow"
                                                             style="width: 100px;">
                                                    </div>
                                                    <div class="col-sm-9">
                                                      <h5 class="mb-0 font-weight-bold">Undergraduate Information Technology</h5>
                                                      <h6 class="mb-0">Universitas Islam Indonesia • Yogyakarta, Indonesia</h6>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class=" py-5 border-top ">
                                                <h3 class="h4 text-primary font-weight-bold ml-5">What I use to</h3>
                                                <div class="row text-center justify-content-center">
                                                    <div class="col-sm-3">
                                                        <div class="row py-3 align-items-center justify-content-center">
                                                            <div class="mt-5 mt-sm-0">
                                                              <img v-lazy="'img/theme/androidstudio.png'" alt="Raised image" class="img-fluid rounded shadow"
                                                             style="width: 100px;">
                                                              <h5 class="mt-3">Android Studio</h5>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-sm-3">
                                                        <div class="row py-3 align-items-center justify-content-center">
                                                            <div class="mt-5 mt-sm-0">
                                                              <img v-lazy="'img/theme/kotlin.png'" alt="Raised image" class="img-fluid rounded shadow"
                                                             style="width: 100px;">
                                                              <h5 class="mt-3">Kotlin</h5>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="col-sm-3">
                                                        <div class="row py-3 align-items-center justify-content-center">
                                                            <div class="mt-5 mt-sm-0">
                                                              <img v-lazy="'img/theme/java.png'" alt="Raised image" class="img-fluid rounded shadow"
                                                             style="width: 100px;">
                                                              <h5 class="mt-3">Java</h5>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </tab-pane>

                                        <tab-pane>
                                            <template slot="title">
                                                <i class="ni ni-app mr-2"></i>Portfolio
                                            </template>
                                                <div class="container">
                                                    <h3 class="h4 text-primary font-weight-bold ml-4">Single Project</h3>
                                                    <div class="row justify-content-center mt-5">
                                                        <div class="col-lg-12">
                                                            <div class="row row-grid">
                                                                <div class="col-lg-4">
                                                                    <card class="border-0" hover shadow body-classes="py-5">
                                                                        <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                                                        </icon>
                                                                        <h6 class="text-primary text-uppercase">Movie Catalogue</h6>
                                                                        <p class="description mt-3">Based on themoviedb.org API that uses RxJava for asynchronous fetching data and then Room Database to make it persistent for better experience. Built with full Java language.</p>
                                                                        <div>
                                                                            <badge type="primary" rounded>RxJava</badge>
                                                                            <badge type="primary" rounded>Movie API</badge>
                                                                            <badge type="primary" rounded>Room DB</badge>
                                                                        </div>
                                                                        <base-button tag="a" href="https://github.com/fadelpamungkas/MovieCatalogue" type="primary" class="mt-4">
                                                                            See Github
                                                                        </base-button>
                                                                    </card>
                                                                </div>
                                                                <div class="col-lg-4">
                                                                    <card class="border-0" hover shadow body-classes="py-5">
                                                                        <icon name="ni ni-istanbul" type="primary" rounded class="mb-4">
                                                                        </icon>
                                                                        <h6 class="text-primary text-uppercase ">Atpic</h6>
                                                                        <p class="description mt-3">E-commerce app that people may buy and sell digital products. Built with mixed Kotlin and Java language and Firebase for main component such as Database, Authentication, and Storage.</p>
                                                                        <div>
                                                                            <badge type="primary" rounded>Firebase</badge>
                                                                            <badge type="primary" rounded>Kotlin</badge>
                                                                            <badge type="primary" rounded>Java</badge>
                                                                        </div>
                                                                        <base-button tag="a" href="https://github.com/fadelpamungkas/Atpic" type="primary" class="mt-4">
                                                                            See Github
                                                                        </base-button>
                                                                    </card>
                                                                </div>
                                                                <div class="col-lg-4">
                                                                    <card class="border-0" hover shadow body-classes="py-5">
                                                                        <icon name="ni ni-planet" type="primary" rounded class="mb-4">
                                                                        </icon>
                                                                        <h6 class="text-primary text-uppercase">Bitter</h6>
                                                                        <p class="description mt-3">This is my ongoing personal project. Main purposes is to implement Spotify API and Jetpack Compose as a new Android modern library. Perhaps uses Kotlin for whole project.</p>
                                                                        <div>
                                                                            <badge type="primary" rounded>Spotify API</badge>
                                                                            <badge type="primary" rounded>Kotlin</badge>
                                                                            <badge type="primary" rounded>Room DB</badge>
                                                                        </div>
                                                                        <base-button tag="a" href="https://github.com/fadelpamungkas/Bitter" type="primary" class="mt-4">
                                                                            See Github
                                                                        </base-button>
                                                                    </card>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </div>
                                        </tab-pane>
                                    </card>
                                </tabs>
                            </div>
                        </div>


                    </div>
                </card>
            </div>
        </section>
    </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style>
</style>
