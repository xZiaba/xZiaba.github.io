<script setup></script>

<template>
  <header class="bg-black shadow-sm">
    <div class="flex items-center justify-end mx-4 ml-9">
      <img
        class="w-16 mx-auto my-2 items-center cursor-pointer"
        src="./assets/waligora-logo.png"
      />
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6 stroke-white cursor-pointer"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5"
          class=""
        />
      </svg>
    </div>
  </header>

  <section class="">
    <div class="relative">
      <img
        class="min-w-screen object-cover"
        src="./assets/placeholder.jpg"
        alt=""
      />
      <div
        class="absolute inset-0 flex items-center justify-center text-white font-bold text-6xl drop-shadow-md"
      >
        <h1 class="">
          Najlepszy <br />
          barber <br />
          w mieście
        </h1>
        <div
          class="absolute top-64 inset-0 flex items-center justify-center text-white font-semibold text-xl drop-shadow-md"
        >
          <p class="p-2 px-9 border-solid border-2 border-white cursor-pointer">
            Sprawdz naszą ofertę
          </p>
        </div>
      </div>
    </div>
  </section>
  <article class="">
    <h1 class="font-bold text-2xl py-24 mx-8 text-center drop-shadow-md">
      - O mnie -
    </h1>
    <h1 class="m-5 text-xl font-semibold text-center px-9 mb-24 drop-shadow-md">
      Cześć jestem Karol, jestem barbrem od x lat, możesz oczekiwać ode mnie
      solidnego cięcia
    </h1>
  </article>
  <section>
    <p class="font-bold text-2xl py-5 pb-24 mx-8 text-center drop-shadow-md">
      - Nasza oferta -
    </p>
    <div>
      <img src="./assets/barber-scissors.svg" class="w-28 m-auto" />
      <p class="mt-4 text-center text-xl font-semibold mx-8">
        Strzyżenie męskie
      </p>
      <p class="mt-4 text-center text-lg mx-8 drop-shadow-md">
        Męskie strzyżenie włosów na głowie
      </p>
      <p class="mt-4 text-center text-lg pb-24 mx-8 drop-shadow-md">60 zł</p>
    </div>
    <div>
      <img src="./assets/barber-seat.svg" class="w-28 m-auto" />
      <p class="mt-4 text-center text-xl font-semibold drop-shadow-md">
        Strzyżenie włosów i zarostu
      </p>
      <p class="mt-4 text-center text-lg mx-8 drop-shadow-md">
        Precyzyjne strzyżenie włosów i zarostu, dopasowane do Twoich potrzeb
      </p>
      <p class="mt-4 text-center text-lg pb-24 mx-8 drop-shadow-md">100 zł</p>
    </div>
    <div>
      <img src="./assets/barber-scissors.svg" class="w-28 m-auto" />
      <p class="mt-4 text-center text-xl font-semibold mx-8 drop-shadow-md">
        Strzyżenie męskie
      </p>
      <p class="mt-4 text-center text-lg mx-8 drop-shadow-md">
        Męskie strzyżenie włosów na głowie
      </p>
      <p class="mt-4 text-center text-lg pb-24 mx-8 drop-shadow-md">60 zł</p>
    </div>
  </section>
  <section class="relative">
    <img src="./assets/placeholder2.jpg" />
    <div class="absolute inset-0 bottom-20 flex items-center justify-center">
      <h2 class="text-white shadow-md text-4xl">Godziny otwarcia</h2>
    </div>
    <div class="absolute inset-0 bottom-20 flex items-center justify-center">
      <h2 class="text-white shadow-md text-4xl">Godziny otwarcia</h2>
    </div>
  </section>
  <section class="">
    <p></p>
    <div class="relative w-full h-96">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2518.8019763069765!2d19.962079212224516!3d50.85335115815431!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x471765e128978957%3A0x9de456f2e1eaa9e9!2sWalig%C3%B3ra%20Barber!5e0!3m2!1spl!2spl!4v1711510345448!5m2!1spl!2spl"
        width="400"
        height="300"
        style="border: 0"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        class="absolute top-0 left-0 w-full h-full"
      ></iframe>
    </div>
  </section>
  <footer class="bg-black">
    <img src="./assets/waligora-logo.png" class="w-32 m-auto" />
    <div class="text-white mx-5">
      <div class="flex">
        <p class="my-6">Kontakt</p>
      </div>
      <div class="flex mb-4">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          strokeWidth="{1.5}"
          stroke="currentColor"
          className="w-6 h-6"
          class="w-6"
        >
          <path
            strokeLinecap="round"
            strokeLinejoin="round"
            d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"
          />
        </svg>

        <p class="ml-3">waligorabarber@gmail.com</p>
      </div>
      <div class="flex mb-4">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-6 h-6"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 0 0 2.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 0 1-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 0 0-1.091-.852H4.5A2.25 2.25 0 0 0 2.25 4.5v2.25Z"
          />
        </svg>

        <p class="ml-3">123 456 789</p>
      </div>
      <div class="flex pb-4">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-6 h-6"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
          />
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"
          />
        </svg>

        <p class="ml-3">ul.Henryka Sienkiewicza 20, 29-100 Włoszczowa</p>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
