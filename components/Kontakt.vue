<template>
  <div
    class="text-center md:grid md:grid-cols-2 md:gap-12 space-y-10 md:space-y-0"
  >
    <div>
      <div
        class="flex justify-center items-center mx-auto mb-4 w-10 h-10 bg-gray-100 rounded-lg dark:bg-gray-800 lg:h-16 lg:w-16"
      >
        <UIcon
          name="i-heroicons-phone"
          class="w-5 h-5 text-primary-600 lg:w-8 lg:h-8"
          dynamic
        />
      </div>
      <p class="mb-2 text-xl font-bold dark:text-white">Zadzwoń pod:</p>
      <p class="mb-3 text-gray-500 dark:text-gray-400">
        Chętnie odpowiemy na Twoje pytania i zapytania telefonicznie.
      </p>
      <NuxtLink
        to="tel:+48510249613"
        class="font-semibold text-primary-600 dark:text-primary-500"
        >+48 510 249 613</NuxtLink
      >
    </div>
    <div>
      <div
        class="flex justify-center items-center mx-auto mb-4 w-10 h-10 bg-gray-100 rounded-lg dark:bg-gray-800 lg:h-16 lg:w-16"
      >
        <UIcon
          name="i-heroicons-map-pin"
          class="w-5 h-5 text-primary-600 lg:w-8 lg:h-8"
          dynamic
        />
      </div>
      <p class="mb-3 text-xl font-bold dark:text-white">Lokalizacja</p>
      <p class="mb-3 text-gray-500 dark:text-gray-400">
        Sprawdź naszą lokalizację i odwiedź nas w dogodnym dla Ciebie terminie.
      </p>
      <NuxtLink
        to="https://maps.app.goo.gl/NE5fGeTzj5Jud4UE6"
        target="_blank"
        class="inline-flex py-2 px-4 text-sm font-medium text-center rounded-lg border text-primary-600 border-primary-600 hover:text-white hover:bg-primary-600 focus:ring-4 focus:outline-none focus:ring-primary-300 dark:border-primary-500 dark:text-primary-500 dark:hover:text-white dark:hover:bg-primary-600 dark:focus:ring-primary-800"
        >Furgoła 183, 44-230 Czerwionka-Leszczyny</NuxtLink
      >
    </div>
  </div>
</template>
