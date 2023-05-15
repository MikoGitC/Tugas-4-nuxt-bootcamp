<template>
  <div class="p-4">
    <div class="bg-white dark:bg-gray-700">
      <nav class="2xl:container 2xl:mx-auto sm:py-6 sm:px-7 py-5 px-4">
        <!-- For large and Medium-sized Screen -->
        <div class="flex justify-between">
          <div class="hidden sm:flex flex-row items-center space-x-6">
            <img
              class="dark:bg-white p-1 rounded focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg1.svg"
              alt="twitter"
            />
            <img
              class="dark:bg-white p-1 rounded focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg2.svg"
              alt="facebook"
            />
            <img
              class="dark:bg-white p-1 rounded focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg3.svg"
              alt="linkdin"
            />
            <img
              class="dark:bg-white p-1 rounded focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 cursor-pointer"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg4.svg"
              alt="instagram"
            />
          </div>
          <div class="flex space-x-3 items-center">
            <img
              class="p-1 dark:bg-white rounded-full"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg5.svg"
              alt="circle"
            />
            <h1
              class="font-normal text-2xl leading-6 text-gray-800 dark:text-white"
            >
              PIZZA HOMEMADE
            </h1>
          </div>
          <div class="hidden sm:flex flex-row space-x-4">
            <button
              class="rounded-md flex space-x-2 w-24 h-10 font-normal text-sm leading-3 text-indigo-700 bg-white border border-indigo-700 focus:outline-none focus:bg-gray-200 hover:bg-gray-200 duration-150 justify-center items-center"
            >
              DAFTAR
            </button>
            <button
              class="rounded-md flex space-x-2 w-24 h-10 font-normal text-sm leading-3 text-white bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 focus:bg-indigo-600 hover:bg-indigo-600 duration-150 justify-center items-center"
            >
              LOGIN
            </button>
          </div>

          <!-- Pizza Icon -->
          <div
            id="bgIcon"
            onclick="toggleMenu()"
            class="focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-gray-800 flex justify-center items-center sm:hidden cursor-pointer"
          >
            <img
              class="dark:bg-white"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg6.svg"
              alt="burger"
            />
            <img
              class="dark:bg-white hidden"
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg7.svg"
              alt="cross"
            />
          </div>
        </div>

        <!-- Mobile and small-screen devices (toggle Menu) -->
        <div id="MobileNavigation" class="hidden sm:hidden mt-4 mx-auto">
          <div class="flex flex-row items-center justify-center space-x-6">
            <img
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg1.svg"
              alt="twitter"
            />
            <img
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg2.svg"
              alt="facebook"
            />
            <img
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg3.svg"
              alt="linkdin"
            />
            <img
              src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg4.svg"
              alt="instagram"
            />
          </div>
          <div class="flex flex-col gap-4 mt-4 w-80 mx-auto">
            <button
              class="rounded-md flex space-x-2 w-full h-10 font-normal text-sm leading-3 text-indigo-700 bg-indigo-600 bg-opacity-0 hover:opacity-100 duration-100 border border-indigo-700 focus:outline-none focus:bg-gray-200 hover:bg-gray-200 duration-150 justify-center items-center"
            >
              Sign Up
            </button>
            <button
              class="rounded-md flex space-x-2 w-full h-10 font-normal text-sm leading-3 text-white bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 focus:bg-indigo-600 hover:bg-indigo-600 duration-150 justify-center items-center"
            >
              Sign In
            </button>
          </div>
        </div>
      </nav>
    </div>

    <h1>TUTORIAL MEMBUAT HOMEMADE PIZZA</h1>
    <img
      src="https://hips.hearstapps.com/hmg-prod/images/delish-homemade-pizza-horizontal-1542312378.png?crop=1xw:0.843328335832084xh;center,top&resize=1200:*"
      width="720"
      height="480"
    />
    <p>Bahan yang diperlukan adalah :</p>
    <ul>
      <li>500 gr tepung terigu tinggi</li>
      <li>1 sendok makan gula</li>
      <li>7 gr ragi instan</li>
      <li>1 1/2 sendok takar garam</li>
      <li>50 ml olive oil</li>
      <li>360 ml air es</li>
    </ul>

    <p>Cara membuatnya adalah :</p>
    <ol>
      <li>
        Mix tepung, gula, susu, ragi hingga rata, tambahkan air, mix hingga
        kalus, tambahkan mentega dan garam, mix hingga elastis, bulatkan,
        diamkan 30 menit
      </li>
      <li>Bagi 3 bagian, bulatkan, diamkan kembali 10 menit</li>
      <li>
        Bentuk pizza dengan sisi luar lebih tebal, tusuk-tusuk dengan garpu,
        diam hingga kembang
      </li>
      <li>Oven setengah matang, keluarkan</li>
      <li>Oles saus pizza, tabur sosis, keju, dan bahan lainnya</li>
      <li>Oven kembali hingga matang, selamat menikmati.</li>
    </ol>

    <p>Kalau bingung bisa ikuti tutorial video dibawah ini :</p>

    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/12JNRq7e648"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
    ></iframe>

    <h1>PESAN HOMEMADE PIZZA</h1>
    <p>Pizza Homemade segar dan sehat siap santap pesan sekarang juga</p>

    <form>
      <label for="fname">Nama Anda:</label><br />
      <input type="text" id="fname" name="fname" value="Adam" /><br />
      <label for="lname">Email Anda:</label><br />
      <input type="text" id="lname" name="lname" value="Adam@gmail.com" />
    </form>

    <style>
      .button {
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
      }

      .button1 {
        background-color: #4CAF50;
      } /* Green */
      .button2 {
        background-color: #008CBA;
      } /* Blue */
    </style>
    <button class="button button1">Pesan</button>

    <div class="pt-12 xl:pt-14 px-6">
      <div
        tabindex="0"
        aria-label="footer"
        class="focus:outline-none w-full border-gray-300 dark:border-gray-700 border-t lg:w-11/12 md:w-11/12 lg:mx-auto md:mx-auto"
      >
        <div class="container mx-auto py-12">
          <div class="xl:flex lg:flex md:flex pt-6">
            <div class="w-11/12 xl:w-3/6 lg:w-2/5 mx-auto lg:mx-0 xl:mx-0">
              <div class="flex items-center mb-6 xl:mb-0 lg:mb-0">
                <div aria-label="logo" role="img">
                  <img
                    class="p-1 dark:bg-white rounded-full"
                    src="https://tuk-cdn.s3.amazonaws.com/can-uploader/header-3-svg5.svg"
                    alt="circle"
                  />
                </div>
                <p
                  tabindex="0"
                  class="focus:outline-none ml-3 dark:text-white font-bold text-xl"
                >
                  PIZZA HOMEMADE
                </p>
              </div>
            </div>
            <div
              class="w-11/12 xl:w-1/6 lg:w-2/5 mx-auto lg:mx-0 xl:mx-0 pt-3 xl:flex flex-col xl:justify-start pl-3 sm:pl-0"
            >
              <h2
                tabindex="0"
                class="focus:outline-none text-gray-800 dark:text-white font-bold text-xl mb-6"
              >
                Community
              </h2>
              <ul>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >About Us</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Guidelines and how to</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Quote from the best</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >How to start a blog</a
                  >
                </li>
              </ul>
            </div>
            <div
              class="w-11/12 xl:w-1/6 lg:w-2/5 mx-auto lg:mx-0 xl:mx-0 pt-3 xl:flex flex-col xl:justify-start pl-3 sm:pl-0"
            >
              <h2
                tabindex="0"
                class="focus:outline-none text-gray-800 dark:text-white font-bold text-xl mb-6"
              >
                Getting Started
              </h2>
              <ul>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >About Us</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Guidelines and how to</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Quote from the best</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >How to start a blog</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Quote from the best</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Guidelines and how to</a
                  >
                </li>
              </ul>
            </div>
            <div
              class="w-11/12 xl:w-1/6 lg:w-2/5 mx-auto lg:mx-0 xl:mx-0 pt-3 xl:flex flex-col xl:justify-start pl-3 sm:pl-0"
            >
              <h2
                tabindex="0"
                class="focus:outline-none text-gray-800 dark:text-white font-bold text-xl mb-6"
              >
                Resources
              </h2>
              <ul>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Accessibility</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Usability</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Marketplace</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Design & Dev</a
                  >
                </li>
                <li
                  class="text-base text-gray-800 dark:text-gray-200 hover:text-gray-700 mb-5"
                >
                  <a
                    tabindex="0"
                    class="focus:underline focus:outline-none"
                    href="javascript:void(0)"
                    >Marketplace</a
                  >
                </li>
              </ul>
            </div>
          </div>
          <div
            class="xl:flex flex-wrap justify-between xl:mt-24 mt-16 pb-6 pl-3 sm:pl-0"
          >
            <div class="w-11/12 xl:w-2/6 mx-auto lg:mx-0 xl:mx-0 mb-6 xl:mb-0">
              <p
                tabindex="0"
                class="focus:outline-none text-gray-800 dark:text-white text-base"
              >
                2023 PIZZA HOMEMADE. All Rights Reserved
              </p>
            </div>
            <div
              class="w-11/12 xl:w-2/6 mx-auto lg:mx-0 xl:mx-0 mb-6 lg:mb-0 xl:mb-0"
            >
              <ul class="xl:flex lg:flex md:flex sm:flex justify-between">
                <li
                  class="text-gray-800 dark:text-white hover:text-gray-900 text-base mb-4 sm:mb-0"
                >
                  <a
                    class="focus:outline-none focus:underline"
                    href="javascript:void(0)"
                    >Terms of service</a
                  >
                </li>
                <li
                  class="text-gray-800 dark:text-white hover:text-gray-900 text-base mb-4 sm:mb-0"
                >
                  <a
                    class="focus:outline-none focus:underline"
                    href="javascript:void(0)"
                    >Privacy Policy</a
                  >
                </li>
                <li
                  class="text-gray-800 dark:text-white hover:text-gray-900 text-base mb-4 sm:mb-0"
                >
                  <a
                    class="focus:outline-none focus:underline"
                    href="javascript:void(0)"
                    >Security</a
                  >
                </li>
                <li
                  class="text-gray-800 dark:text-white hover:text-gray-900 text-base mb-4 sm:mb-0"
                >
                  <a
                    class="focus:outline-none focus:underline"
                    href="javascript:void(0)"
                    >Sitemap</a
                  >
                </li>
              </ul>
            </div>
            <div
              class="w-11/12 xl:w-1/6 lg:w-1/6 sm:w-11/12 mx-auto lg:mx-0 xl:mx-0 mb-6 lg:mb-0 xl:mb-0 mt-8 lg:mt-8 xl:mt-0"
            >
              <div
                class="flex justify-start sm:justify-start xl:justify-end space-x-6 pr-2 xl:pr-0 lg:pr-0 md:pr-0 sm:pr-0"
              >
                <div>
                  <a aria-label="Twitter" role="link" href="javascript:void(0)">
                    <img
                      src="https://tuk-cdn.s3.amazonaws.com/can-uploader/footer_with_sitemap-svg2.svg"
                      alt="Twitter"
                    />
                  </a>
                </div>
                <div>
                  <a
                    aria-label="Instagram"
                    role="link"
                    href="javascript:void(0)"
                  >
                    <img
                      src="https://tuk-cdn.s3.amazonaws.com/can-uploader/footer_with_sitemap-svg3.svg"
                      alt="Instagram"
                    />
                  </a>
                </div>
                <div>
                  <a aria-label="Dribble" role="link" href="javascript:void(0)">
                    <img
                      src="https://tuk-cdn.s3.amazonaws.com/can-uploader/footer_with_sitemap-svg4.svg"
                      alt="Dribble"
                    />
                  </a>
                </div>
                <div>
                  <a aria-label="Github" role="link" href="javascript:void(0)">
                    <img
                      src="https://tuk-cdn.s3.amazonaws.com/can-uploader/footer_with_sitemap-svg5.svg"
                      alt="Github"
                    />
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- FOOTER END -->
  </div>
</template>

<style lang="postcss" scoped>
.badge {
  @apply inline-block bg-gray-200 rounded-full px-3 py-1 text-sm font-semibold text-gray-700;
  &:hover {
    @apply bg-gray-300;
  }
}
</style>