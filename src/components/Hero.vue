<template>
  <section class="relative min-h-screen flex flex-col from-gray-900 to-gray-800 bg-gradient-to-tr w-full">
    <picture>
      <img class="absolute w-[850px] h-auto bottom-0 right-0 translate-x-1/4 z-0 pointer-events-none lazyloaded" alt="" :src="bg" data-eio="p" decoding="async" width="1200" height="870">
    </picture>
    <div class="lg:container lg:mx-auto z-[9999] px-4 md:px-0">
      <Navbar />
      <div class="container mx-auto grow py-16 grid grid-cols-12">
        <div class="col-span-full lg:col-span-6 text-center lg:text-left">
          <h2 class="text-white text-6xl font-semibold">
            Welcome to the future of artificial intelligence trading
          </h2>
          <p class="max-w-xl text-gray-100 mt-6 max-lg:mx-auto text-md">
            <font> Want to gain an edge in the market? </font>
            <font> Quantum App Trader can be your solution. </font>
            <font>
              With our cutting-edge artificail intelligence trading tools, you'll be able to make
              smarter, more rational decisions, helping you to earn huge profits
            </font>
          </p>

          <div
            class="flex gap-3 justify-center lg:justify-start items-center mt-4 divide-x divide-gray-500/70 text-sm"
          >
            <Rating />
            <div class="text-white pl-3">
              Rated 4.7 stars
              <span class="text-gray-100/90 text-xs">by over </span>
              <span class="text-green-500">4.121 users</span>
            </div>
          </div>

          <div class="mt-6 mx-auto text-gray-300">
            * All cryptocurrency trading involves risks and profitability is not guaranteed.
          </div>

          <div
            class="mt-7 md:mt-10 rounded-xl py-4 px-6 md:py-6 md:px-8 border border-white/10 bg-gray-900 inline-block mx-auto"
          >
            <h3
              class="mb-4 text-sm md:text-base text-transparent bg-clip-text bg-gradient-to-tr from-blue-400 to-emerald-400 font-semibold text-center uppercase tracking-wide inline-block mx-auto"
            >
              <font style="vertical-align: inherit">
                <font style="vertical-align: inherit"> As seen above </font></font
              >
            </h3>
            <div class="flex items-center flex-wrap gap-6 justify-center">
              <img
                :src="img1"
                alt="CBS_logo"
                class="h-10 w-auto md:h-12 md:w-auto lazyloaded"
                decoding="async"
              />
              <img
                :src="img2"
                alt="Fox_News_Channel_logo"
                class="h-10 w-auto md:h-12 md:w-auto lazyloaded"
                decoding="async"
              />
              <img
                :src="img3"
                alt="NBC_logo"
                class="h-10 w-auto md:h-12 md:w-auto lazyloaded"
                decoding="async"
              />
              <img
                :src="img4"
                alt="usa-today-logo-vector-2021"
                class="h-10 w-auto md:h-12 md:w-auto lazyloaded"
                decoding="async"
              />
              <img
                :src="img5"
                alt="usa-today-logo-vector-2021"
                class="h-10 w-auto md:h-12 md:w-auto lazyloaded"
                decoding="async"
              />
            </div>
          </div>
        </div>
        <div class="mt-12 sm:mt-24 col-span-full lg:col-span-6 xl:col-span-5 lg:mt-0">
          <div class="bg-white sm:mx-auto sm:w-full sm:max-w-md xl:mr-0 rounded-lg">
            <div class="px-6 py-8 sm:px-10">
              <div class="max-lg:text-center">
                <h2 class="text-2xl font-bold tracking-tight md:text-3xl">
                  <font style="vertical-align: inherit"
                    ><font style="vertical-align: inherit">Register now</font></font
                  >
                </h2>
                <p class="text-sm md:text-base text-gray-500 mt-1.5 md:mt-2.5">
                  <font style="vertical-align: inherit"
                    ><font style="vertical-align: inherit"
                      >Start your AI trading journey in less than 30 seconds</font
                    ></font
                  >
                </p>
              </div>
              <div class="mt-4 signup-form">
                <div id="registration" style="margin: -1rem">
                  <main data-version="2.8.2" class="tw-antialiased tw-font-sans">
                    <section class="tw-p-4">
                      <!---->
                      <!---->
                      <!---->
                      <!---->
                      <div class="f1t-form is-submited">
                        <div class="Dynaform-div default">
                          <form
                            method="post"
                            class="Dynaform-form [&_input]:p-2 [&_input]:border [&_input]:border-gray-200 [&_input]:w-full space-y-4"
                          >
                            <div class="row flex flex-col gap-4">
                              <div class="form-group Dynaformdiv-fname">
                                <input
                                  onchange="this.setCustomValidity('')"
                                  oninvalid="this.setCustomValidity('这是必填字段')"
                                  title="This is a required field"
                                  type="text"
                                  name="first_name"
                                  placeholder="name"
                                  required="false"
                                  value=""
                                />
                              </div>
                              <div class="form-group Dynaformdiv-lname">
                                <input
                                  onchange="this.setCustomValidity('')"
                                  oninvalid="this.setCustomValidity('这是必填字段')"
                                  title="This is a required field"
                                  type="text"
                                  name="last_name"
                                  placeholder="Last name"
                                  class="form-control"
                                  required="false"
                                />
                              </div>
                            </div>
                            <div class="row">
                              <div class="form-group Dynaformdiv-email">
                                <input
                                  onchange="this.setCustomValidity('')"
                                  oninvalid="this.setCustomValidity('请输入有效的电子邮件地址')"
                                  title="Please enter a valid email address"
                                  type="email"
                                  name="email"
                                  placeholder="e-mail"
                                  class="form-control"
                                  required="false"
                                  value=""
                                />
                              </div>
                            </div>
                            <div class="row">
                              <div class="form-group Dynaformdiv-submit">
                                <button
                                  type="submit"
                                  name="submit"
                                  class="Dynaform-btn rounded-lg bg-blue-600 text-white flex items-center justify-center p-4 w-full font-bold"
                                >
                                  <font style="vertical-align: inherit"
                                    ><font style="vertical-align: inherit"
                                      >Create your account</font
                                    ></font
                                  >
                                </button>
                              </div>
                            </div>
                          </form>
                          <div class="Dynaform-waiting" style="display: none">
                            <img src="//qapptrader.com//Dynaform/loading.gif" />
                            <h2 style="text-align: center">
                              <font style="vertical-align: inherit"
                                ><font style="vertical-align: inherit"
                                  >Please wait while we transfer it to your broker</font
                                ></font
                              >
                            </h2>
                          </div>
                          <div class="Dynaform-tymsg"></div>
                        </div>
                      </div>
                    </section>
                  </main>
                </div>
              </div>
            </div>
            <div
              class="border-t-2 border-gray-200 bg-gray-50 px-6 py-6 sm:px-10 rounded-b-lg prose prose-sm text-gray-500 form-disclaimer"
            >
              <p>
                <font style="vertical-align: inherit"
                  ><font style="vertical-align: inherit"
                    >By signing up, you agree to our&nbsp;
                  </font></font
                ><a
                  class="font-medium text-gray-900 hover:underline"
                  href="#"
                  rel="noopener"
                  target="_blank"
                  ><font style="vertical-align: inherit"
                    ><font style="vertical-align: inherit">Terms of Use</font></font
                  ></a
                ><font style="vertical-align: inherit"
                  ><font style="vertical-align: inherit"> &nbsp;and&nbsp; </font></font
                ><a
                  class="font-medium text-gray-900 hover:underline"
                  href="#"
                  target="_blank"
                  rel="noopener"
                  ><font style="vertical-align: inherit"
                    ><font style="vertical-align: inherit">Privacy Policy</font></font
                  ></a
                ><font style="vertical-align: inherit"
                  ><font style="vertical-align: inherit"> .</font></font
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts">
import Navbar from './Navbar.vue'
import Rating from './Rating.vue'
import img1 from '../assets/img01.png'
import img2 from '../assets/img02.png'
import img3 from '../assets/img03.png'
import img4 from '../assets/img04.png'
import img5 from '../assets/img05.png'
import bg from '../assets/bg.webp'
</script>

<style scoped></style>
