<template>
  <header class="bg-gray-900 py-4 px-4 text-white">
    <div class="container mx-auto flex justify-between items-center">
      <div class="flex items-center space-x-5">
        <nuxt-link to="/github">
          <svg
            class="w-8 mr-2 fill-current hover:text-gray-400"
            viewBox="0 0 16 16"
            version="1.1"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
            ></path>
          </svg>
        </nuxt-link>

        <div class="relative">
          <input
            type="text"
            class="rounded px-4 py-1 bg-gray-800"
            placeholder="Search or jump to..."
          />
          <div class="absolute top-0 right-0 flex items-center h-full">
            <div
              class="border border-gray-600 rounded text-xs text-gray-400 px-2 mr-2"
            >
              /
            </div>
          </div>
        </div>

        <ul class="flex items-center font-semibold space-x-5">
          <li>
            <a href="#" class="hover:text-gray-400">Pull requests</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-400">Issues</a>
          </li>
          <li>
            <a href="#" class="hover:text-gray-400">Marketplace</a>
          </li>
          <li><a href="#" class="hover:text-gray-400">Explore</a></li>
        </ul>
      </div>
      <div class="flex items-center space-x-4">
        <a href="#" class="relative hover:text-gray-400">
          <svg
            class="w-4 h-4 fill-current"
            viewBox="0 0 16 16"
            version="1.1"
            aria-hidden="true"
          >
            <path
              d="M8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"
            ></path>
            <path
              fill-rule="evenodd"
              d="M8 1.5A3.5 3.5 0 004.5 5v2.947c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01l.001.006c0 .002.002.004.004.006a.017.017 0 00.006.004l.007.001h10.964l.007-.001a.016.016 0 00.006-.004.016.016 0 00.004-.006l.001-.007a.017.017 0 00-.003-.01l-1.703-2.554a1.75 1.75 0 01-.294-.97V5A3.5 3.5 0 008 1.5zM3 5a5 5 0 0110 0v2.947c0 .05.015.098.042.139l1.703 2.555A1.518 1.518 0 0113.482 13H2.518a1.518 1.518 0 01-1.263-2.36l1.703-2.554A.25.25 0 003 7.947V5z"
            ></path>
          </svg>
          <div
            class="bg-blue-500 rounded-full w-2 h-2 absolute top-0 right-0"
          ></div>
        </a>

        <a href="#" class="flex items-center hover:text-gray-400">
          <svg
            class="w-4 h-4 fill-current"
            viewBox="0 0 16 16"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.75 2a.75.75 0 01.75.75V7h4.25a.75.75 0 110 1.5H8.5v4.25a.75.75 0 11-1.5 0V8.5H2.75a.75.75 0 010-1.5H7V2.75A.75.75 0 017.75 2z"
            ></path>
          </svg>

          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            class="w-4 h-4 fill-current ml-1"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </a>

        <a href="#" class="flex items-center hover:text-gray-400">
          <img
            alt="@anburocky3"
            class="w-6 h-6 rounded-full"
            src="https://avatars2.githubusercontent.com/u/15264938?s=60&amp;v=4"
          />
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            class="w-5 h-5 fill-current ml-1"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="1"
              d="M19 9l-7 7-7-7"
            />
          </svg>
        </a>
      </div>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style></style>
