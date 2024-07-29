<template>
  <nav class="bg-white border-gray-200 z-10 dark:bg-black">
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <NuxtLink to="/" class="flex items-center space-x-3 rtl:space-x-reverse">
        <img src="/assets/images/archive-logo.png" class="h-11" alt="Logo" />
      </NuxtLink>

      <button
        data-collapse-toggle="navbar-default"
        type="button"
        class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
        aria-controls="navbar-default"
        aria-expanded="false"
      >
        <span class="sr-only">Open main menu</span>
        <svg
          class="w-5 h-5"
          aria-hidden="true"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 17 14"
        >
          <path
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M1 1h15M1 7h15M1 13h15"
          />
        </svg>
      </button>
      <div class="hidden w-full md:block md:w-auto" id="navbar-default">
        <ul
          class="font-medium flex flex-col p-4 md:p-0 mt-4 bg-black border border-gray-100 rounded-lg md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0"
        >
          <li>
            <NuxtLink
              to="/archives"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Archives
            </NuxtLink>
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >The Beginning</a
            >
          </li>
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Unl Flashback</a
            >
          </li>
          <li>
            <NuxtLink
              to="/credits"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent"
              >Credits
            </NuxtLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <slot />
  <footer class="footer bg-neutral text-neutral-content items-center p-2">
    <div
      class="w-full mx-auto max-w-screen-xl p-4 md:flex md:items-center md:justify-between"
    >
      <span class="text-sm text-gray-500 sm:text-center dark:text-gray-400">
        <a href="https://ushersnewlook.org/"
          ><NuxtImg
            class="h-9 pb-2"
            src="https://4kx760.p3cdn1.secureserver.net/wp-content/uploads/2019/05/unlLogo.png"
          ></NuxtImg
        ></a>
      </span>
      <nav class="md:place-self-center md:justify-self-end">
        <div class="grid grid-flow-col gap-4">
          <a
            class="transition duration-300 ease-in-out hover:text-blue-800"
            href="https://www.facebook.com/ushersnewlookfoundation/"
          >
            <i class="fab fa-facebook fa-2xl"></i>
          </a>
          <a
            class="transition duration-300 ease-in-out hover:text-red-500"
            href="https://www.instagram.com/ushersnewlook/"
          >
            <i class="fab fa-instagram fa-2xl"></i>
          </a>
          <a
            class="transition duration-300 ease-in-out hover:text-sky-500"
            href="https://x.com/ushersnewlook"
          >
            <i class="fab fa-twitter fa-2xl"></i>
          </a>
          <a
            class="transition text-base-content duration-300 ease-in-out hover:text-blue-800"
            href="https://www.linkedin.com/company/usher's-new-look-foundation/"
          >
            <i class="fab fa-linkedin fa-2xl"></i>
          </a>
        </div>
      </nav>
    </div>
  </footer>
  <footer class="footer bg-neutral text-base-content items-center px-10">
    <div
      class="w-full mx-auto max-w-screen-xl p-2 md:flex md:items-center md:justify-between"
    >
      <aside class="grid-flow-col md:items-center">
        <p class="text-md">
          Made with <i class="fad fa-heart text-red-400"></i> by
          <a
            href="https://github.com/im-aeo"
            class="bg-gradient-to-t from-black via-yellow-400 to-white inline-block text-transparent bg-clip-text font-semibold cursor-pointer"
            >Aeo</a
          >
          <br />
        </p>
      </aside>
    </div>
  </footer>
</template>
