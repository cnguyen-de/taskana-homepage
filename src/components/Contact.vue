<template>
  <div
    id="contact"
    class="content-wrapper py-16 bg-gradient-to-br from-secondary-800 to-primary-700 dark:from-secondary-900 dark:to-primary-900"
  >
    <div class="content z-10">
      <p class="content-title--alt">
        {{ $t('contact.headline') }}
        <Link path="#contact" />
      </p>
      <div data-aos="fade-up" data-aos-anchor-placement="center-bottom">
        <div class="mt-8 px-6 text-white text-base md:text-lg">
          {{ $t('contact.description1') }}
          <a class="hover:text-secondary-600" href="mailto:taskana@novatec-gmbh.de">taskana@novatec-gmbh.de</a>
          {{ $t('contact.description2') }}
        </div>
        <div class="mt-8 py-4 flex justify-center">
          <div
            class="contact-info w-[90%] sm:min-w-[400px] md:w-1/2 h-96 sm:h-64 bg-white rounded-md flex flex-col sm:flex-row"
          >
            <div class="avatar relative pt-2 sm:pt-0 h-48 w-48 sm:h-auto sm:w-64 mx-auto sm:mx-0">
              <img
                class="absolute w-full h-full rounded-full sm:rounded-none sm:rounded-l-md object-cover"
                src="holger.jpeg"
                alt=""
              />
            </div>
            <div class="info text-center sm:text-left p-4 my-auto">
              <p class="name mb-1 text-lg font-bold uppercase tracking-tight">Holger Hagen</p>
              <p class="text-gray-600">Head of Practice Area</p>
              <p class="text-gray-600">Business Process Management</p>
              <div class="h-1 mt-4 mb-2 mx-auto sm:mx-0 bg-gradient-to-r from-primary-600 to-secondary-600 w-2/3"></div>
              <div class="text-gray-700">
                <svg
                  class="w-4 h-4 inline mr-0 md:mr-2"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M16 12a4 4 0 10-8 0 4 4 0 008 0zm0 0v1.5a2.5 2.5 0 005 0V12a9 9 0 10-9 9m4.5-1.206a8.959 8.959 0 01-4.5 1.207"
                  ></path>
                </svg>
                <a class="hover:text-secondary-600 select-all" href="mailto:holger.hagen@novatec-gmbh.de">
                  holger.hagen@novatec-gmbh.de
                </a>
              </div>
              <div class="text-gray-700">
                <svg
                  class="w-4 h-4 inline mr-2"
                  fill="none"
                  stroke="currentColor"
                  viewBox="0 0 24 24"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                  ></path>
                </svg>
                <a class="select-all hidden sm:inline-block">+49 711 22040-827</a>
                <a href="tel:+4971122040-827" class="select-all inline-block sm:hidden">
                  +49 711 22040-827
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="pattern top-0 absolute h-full w-full z-[-10]"></div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import Link from '@/core/Link.vue'

@Options({
  components: { Link }
})
export default class Solution extends Vue {}
</script>

<style lang="scss" scoped>
.pattern {
  background-color: transparent;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 56 28' width='56' height='28'%3E%3Cpath fill='%239C92AC' fill-opacity='0.27' d='M56 26v2h-7.75c2.3-1.27 4.94-2 7.75-2zm-26 2a2 2 0 1 0-4 0h-4.09A25.98 25.98 0 0 0 0 16v-2c.67 0 1.34.02 2 .07V14a2 2 0 0 0-2-2v-2a4 4 0 0 1 3.98 3.6 28.09 28.09 0 0 1 2.8-3.86A8 8 0 0 0 0 6V4a9.99 9.99 0 0 1 8.17 4.23c.94-.95 1.96-1.83 3.03-2.63A13.98 13.98 0 0 0 0 0h7.75c2 1.1 3.73 2.63 5.1 4.45 1.12-.72 2.3-1.37 3.53-1.93A20.1 20.1 0 0 0 14.28 0h2.7c.45.56.88 1.14 1.29 1.74 1.3-.48 2.63-.87 4-1.15-.11-.2-.23-.4-.36-.59H26v.07a28.4 28.4 0 0 1 4 0V0h4.09l-.37.59c1.38.28 2.72.67 4.01 1.15.4-.6.84-1.18 1.3-1.74h2.69a20.1 20.1 0 0 0-2.1 2.52c1.23.56 2.41 1.2 3.54 1.93A16.08 16.08 0 0 1 48.25 0H56c-4.58 0-8.65 2.2-11.2 5.6 1.07.8 2.09 1.68 3.03 2.63A9.99 9.99 0 0 1 56 4v2a8 8 0 0 0-6.77 3.74c1.03 1.2 1.97 2.5 2.79 3.86A4 4 0 0 1 56 10v2a2 2 0 0 0-2 2.07 28.4 28.4 0 0 1 2-.07v2c-9.2 0-17.3 4.78-21.91 12H30zM7.75 28H0v-2c2.81 0 5.46.73 7.75 2zM56 20v2c-5.6 0-10.65 2.3-14.28 6h-2.7c4.04-4.89 10.15-8 16.98-8zm-39.03 8h-2.69C10.65 24.3 5.6 22 0 22v-2c6.83 0 12.94 3.11 16.97 8zm15.01-.4a28.09 28.09 0 0 1 2.8-3.86 8 8 0 0 0-13.55 0c1.03 1.2 1.97 2.5 2.79 3.86a4 4 0 0 1 7.96 0zm14.29-11.86c1.3-.48 2.63-.87 4-1.15a25.99 25.99 0 0 0-44.55 0c1.38.28 2.72.67 4.01 1.15a21.98 21.98 0 0 1 36.54 0zm-5.43 2.71c1.13-.72 2.3-1.37 3.54-1.93a19.98 19.98 0 0 0-32.76 0c1.23.56 2.41 1.2 3.54 1.93a15.98 15.98 0 0 1 25.68 0zm-4.67 3.78c.94-.95 1.96-1.83 3.03-2.63a13.98 13.98 0 0 0-22.4 0c1.07.8 2.09 1.68 3.03 2.63a9.99 9.99 0 0 1 16.34 0z'%3E%3C/path%3E%3C/svg%3E");
}
</style>
