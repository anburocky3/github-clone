<template>
  <div class="text-gray-900 text-sm">
    <div class="bg-gray-50">
      <GitHeader />

      <GitTopNav />
    </div>

    <div class="container mx-auto my-8 flex gap-4">
      <div class="w-3/4 px-5">
        <!-- action -->
        <div class="flex justify-between">
          <div class="flex items-center gap-4">
            <button
              class="px-4 py-1.5 border flex items-center gap-1.5 rounded-md bg-gray-50 hover:bg-gray-100"
            >
              <svg
                class="w-4 h-4 fill-current text-gray-600"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                ></path>
              </svg>
              master
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                class="w-3 h-3 fill-current ml-1"
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
            </button>

            <div
              class="flex items-center gap-1.5 hover:text-blue-500 cursor-pointer"
            >
              <svg
                class="w-4 h-4 fill-current text-gray-600"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"
                ></path>
              </svg>
              <strong>1</strong>
              <span class="text-gray-600">branch</span>
            </div>

            <div class="flex items-center gap-1.5">
              <svg
                class="w-4 h-4 fill-current text-gray-600"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
                ></path>
              </svg>
              <strong>0</strong>
              <span class="text-gray-600">tags</span>
            </div>
          </div>

          <div class="flex items-center gap-2">
            <button class="px-4 py-1.5 bg-gray-50 border rounded-md">
              Go to file
            </button>
            <button class="px-4 py-1.5 bg-gray-50 border rounded-md">
              Add file
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                class="w-3 h-3 fill-current inline-block"
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
            </button>
            <button
              class="px-4 py-1.5 text-white border rounded-md"
              style="background-color: #2ea44f"
            >
              <div class="flex items-center gap-1.5">
                <svg
                  class="w-4 h-4 fill-current text-gray-200"
                  viewBox="0 0 16 16"
                  aria-hidden="true"
                >
                  <path
                    fill-rule="evenodd"
                    d="M7.47 10.78a.75.75 0 001.06 0l3.75-3.75a.75.75 0 00-1.06-1.06L8.75 8.44V1.75a.75.75 0 00-1.5 0v6.69L4.78 5.97a.75.75 0 00-1.06 1.06l3.75 3.75zM3.75 13a.75.75 0 000 1.5h8.5a.75.75 0 000-1.5h-8.5z"
                  ></path>
                </svg>

                <span>Code</span>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  class="w-3 h-3 fill-current inline-block"
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
              </div>
            </button>
          </div>
        </div>
        <!-- end action -->

        <!-- code head -->
        <div
          class="mt-5 py-3 px-3 flex justify-between bg-blue-50 border border-b-0 rounded-md rounded-b-none"
        >
          <div class="flex items-center gap-3">
            <a href="#">
              <img
                alt="@anburocky3"
                src="https://avatars0.githubusercontent.com/u/15264938?s=120"
                class="w-8 h-8 rounded-full"
              />
            </a>

            <div class="flex items-center gap-2">
              <span class="font-semibold">anburocky3</span>
              <span>Feature: Header UI Designed</span>
            </div>
          </div>

          <div class="flex items-center gap-4 text-gray-600">
            <div class="flex gap-2">
              <span>4744fae</span>
              <span>4 days ago</span>
            </div>
            <div class="flex items-center gap-1">
              <svg
                class="w-4 h-4 fill-current"
                viewBox="0 0 16 16"
                aria-hidden="true"
              >
                <path
                  fill-rule="evenodd"
                  d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"
                ></path>
              </svg>
              <strong class="text-gray-900">2</strong> commits
            </div>
          </div>
        </div>
        <!-- end code head -->

        <!-- Commits container -->
        <div class="rounded-md rounded-t-none border border-t-0">
          <commit-item :data="commitsData" />
        </div>

        <div class="border rounded-md p-5 my-5">
          <div class="flex justify-between items-center">
            <span class="font-semibold">README.md</span>
            <svg
              class="w-4 h-4 fill-current text-gray-600"
              viewBox="0 0 16 16"
              aria-hidden="true"
            >
              <path
                fill-rule="evenodd"
                d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"
              ></path>
            </svg>
          </div>

          <div class="py-5 text-gray-600">
            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae
              aliquam incidunt minima! Quibusdam error delectus aliquid magni
              esse fugiat voluptate, omnis beatae animi harum odit. Maxime esse
              mollitia quaerat neque?
            </p>

            <br />

            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae
              aliquam incidunt minima! Quibusdam error delectus aliquid magni
              esse fugiat voluptate, omnis beatae animi harum odit. Maxime esse
              mollitia quaerat neque?
            </p>
            <br />

            <p>
              Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quae
              aliquam incidunt minima! Quibusdam error delectus aliquid magni
              esse fugiat voluptate, omnis beatae animi harum odit. Maxime esse
              mollitia quaerat neque?
            </p>
          </div>
        </div>

        <!-- end commits container -->
      </div>

      <!-- Right Sidebar -->
      <div class="w-1/4 space-y-4">
        <!-- header -->
        <div class="flex justify-between items-center">
          <h1 class="text-base font-semibold text-gray-900">About</h1>

          <svg
            aria-label="Edit repository metadata"
            class="w-4 h-4 fill-current text-gray-600"
            height="16"
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            role="img"
          >
            <path
              fill-rule="evenodd"
              d="M7.429 1.525a6.593 6.593 0 011.142 0c.036.003.108.036.137.146l.289 1.105c.147.56.55.967.997 1.189.174.086.341.183.501.29.417.278.97.423 1.53.27l1.102-.303c.11-.03.175.016.195.046.219.31.41.641.573.989.014.031.022.11-.059.19l-.815.806c-.411.406-.562.957-.53 1.456a4.588 4.588 0 010 .582c-.032.499.119 1.05.53 1.456l.815.806c.08.08.073.159.059.19a6.494 6.494 0 01-.573.99c-.02.029-.086.074-.195.045l-1.103-.303c-.559-.153-1.112-.008-1.529.27-.16.107-.327.204-.5.29-.449.222-.851.628-.998 1.189l-.289 1.105c-.029.11-.101.143-.137.146a6.613 6.613 0 01-1.142 0c-.036-.003-.108-.037-.137-.146l-.289-1.105c-.147-.56-.55-.967-.997-1.189a4.502 4.502 0 01-.501-.29c-.417-.278-.97-.423-1.53-.27l-1.102.303c-.11.03-.175-.016-.195-.046a6.492 6.492 0 01-.573-.989c-.014-.031-.022-.11.059-.19l.815-.806c.411-.406.562-.957.53-1.456a4.587 4.587 0 010-.582c.032-.499-.119-1.05-.53-1.456l-.815-.806c-.08-.08-.073-.159-.059-.19a6.44 6.44 0 01.573-.99c.02-.029.086-.075.195-.045l1.103.303c.559.153 1.112.008 1.529-.27.16-.107.327-.204.5-.29.449-.222.851-.628.998-1.189l.289-1.105c.029-.11.101-.143.137-.146zM8 0c-.236 0-.47.01-.701.03-.743.065-1.29.615-1.458 1.261l-.29 1.106c-.017.066-.078.158-.211.224a5.994 5.994 0 00-.668.386c-.123.082-.233.09-.3.071L3.27 2.776c-.644-.177-1.392.02-1.82.63a7.977 7.977 0 00-.704 1.217c-.315.675-.111 1.422.363 1.891l.815.806c.05.048.098.147.088.294a6.084 6.084 0 000 .772c.01.147-.038.246-.088.294l-.815.806c-.474.469-.678 1.216-.363 1.891.2.428.436.835.704 1.218.428.609 1.176.806 1.82.63l1.103-.303c.066-.019.176-.011.299.071.213.143.436.272.668.386.133.066.194.158.212.224l.289 1.106c.169.646.715 1.196 1.458 1.26a8.094 8.094 0 001.402 0c.743-.064 1.29-.614 1.458-1.26l.29-1.106c.017-.066.078-.158.211-.224a5.98 5.98 0 00.668-.386c.123-.082.233-.09.3-.071l1.102.302c.644.177 1.392-.02 1.82-.63.268-.382.505-.789.704-1.217.315-.675.111-1.422-.364-1.891l-.814-.806c-.05-.048-.098-.147-.088-.294a6.1 6.1 0 000-.772c-.01-.147.039-.246.088-.294l.814-.806c.475-.469.679-1.216.364-1.891a7.992 7.992 0 00-.704-1.218c-.428-.609-1.176-.806-1.82-.63l-1.103.303c-.066.019-.176.011-.299-.071a5.991 5.991 0 00-.668-.386c-.133-.066-.194-.158-.212-.224L10.16 1.29C9.99.645 9.444.095 8.701.031A8.094 8.094 0 008 0zm1.5 8a1.5 1.5 0 11-3 0 1.5 1.5 0 013 0zM11 8a3 3 0 11-6 0 3 3 0 016 0z"
            ></path>
          </svg>
        </div>
        <!-- end header -->
        <p class="text-base">
          Github clone with latest tailwindcss, nuxt ;) Happy learning.
        </p>

        <div class="flex items-center">
          <svg
            class="octicon octicon-link flex-shrink-0 mr-2"
            height="16"
            viewBox="0 0 16 16"
            version="1.1"
            width="16"
            aria-hidden="true"
          >
            <path
              fill-rule="evenodd"
              d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"
            ></path>
          </svg>

          <a href="#" class="text-blue-600 font-semibold hover:underline"
            >github.com/anburocky3</a
          >
        </div>

        <!-- badges -->
        <div class="tags flex items-center flex-wrap text-xs">
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >vue
          </a>
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >nuxtjs
          </a>
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >tailwindcss
          </a>
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >responsive
          </a>
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >tutorial
          </a>
          <a
            href="#"
            class="px-3 py-1 rounded-full text-blue-600 hover:bg-blue-100 bg-blue-50 mr-2 mt-2"
            >clone-ui
          </a>
        </div>

        <ul class="py-5 text-gray-700 space-y-5">
          <a href="#" class="flex gap-4 items-center hover:text-blue-600">
            <svg
              class="w-4 h-4 fill-current"
              viewBox="0 0 16 16"
              aria-hidden="true"
            >
              <path
                fill-rule="evenodd"
                d="M0 1.75A.75.75 0 01.75 1h4.253c1.227 0 2.317.59 3 1.501A3.744 3.744 0 0111.006 1h4.245a.75.75 0 01.75.75v10.5a.75.75 0 01-.75.75h-4.507a2.25 2.25 0 00-1.591.659l-.622.621a.75.75 0 01-1.06 0l-.622-.621A2.25 2.25 0 005.258 13H.75a.75.75 0 01-.75-.75V1.75zm8.755 3a2.25 2.25 0 012.25-2.25H14.5v9h-3.757c-.71 0-1.4.201-1.992.572l.004-7.322zm-1.504 7.324l.004-5.073-.002-2.253A2.25 2.25 0 005.003 2.5H1.5v9h3.757a3.75 3.75 0 011.994.574z"
              ></path>
            </svg>
            Readme</a
          >
          <a href="#" class="flex gap-4 items-center hover:text-blue-600">
            <svg
              class="w-4 h-4 fill-current"
              viewBox="0 0 16 16"
              aria-hidden="true"
            >
              <path
                fill-rule="evenodd"
                d="M8.75.75a.75.75 0 00-1.5 0V2h-.984c-.305 0-.604.08-.869.23l-1.288.737A.25.25 0 013.984 3H1.75a.75.75 0 000 1.5h.428L.066 9.192a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.514 3.514 0 00.686.45A4.492 4.492 0 003 11c.88 0 1.556-.22 2.023-.454a3.515 3.515 0 00.686-.45l.045-.04.016-.015.006-.006.002-.002.001-.002L5.25 9.5l.53.53a.75.75 0 00.154-.838L3.822 4.5h.162c.305 0 .604-.08.869-.23l1.289-.737a.25.25 0 01.124-.033h.984V13h-2.5a.75.75 0 000 1.5h6.5a.75.75 0 000-1.5h-2.5V3.5h.984a.25.25 0 01.124.033l1.29.736c.264.152.563.231.868.231h.162l-2.112 4.692a.75.75 0 00.154.838l.53-.53-.53.53v.001l.002.002.002.002.006.006.016.015.045.04a3.517 3.517 0 00.686.45A4.492 4.492 0 0013 11c.88 0 1.556-.22 2.023-.454a3.512 3.512 0 00.686-.45l.045-.04.01-.01.006-.005.006-.006.002-.002.001-.002-.529-.531.53.53a.75.75 0 00.154-.838L13.823 4.5h.427a.75.75 0 000-1.5h-2.234a.25.25 0 01-.124-.033l-1.29-.736A1.75 1.75 0 009.735 2H8.75V.75zM1.695 9.227c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L3 6.327l-1.305 2.9zm10 0c.285.135.718.273 1.305.273s1.02-.138 1.305-.273L13 6.327l-1.305 2.9z"
              ></path>
            </svg>
            MIT License</a
          >
        </ul>

        <!-- releases -->
        <div class="border-t">
          <div class="head py-5">
            <h1>
              <strong class="text-base">Releases</strong>
              <span class="bg-gray-200 px-2 py-0.5 rounded-full text-xs ml-0.5"
                >145</span
              >
            </h1>
          </div>

          <a href="#" class="flex items-start group">
            <svg
              class="w-4 h-4 mt-1 text-green-600 fill-current group-hover:text-blue-500"
              viewBox="0 0 16 16"
              aria-hidden="true"
            >
              <path
                fill-rule="evenodd"
                d="M2.5 7.775V2.75a.25.25 0 01.25-.25h5.025a.25.25 0 01.177.073l6.25 6.25a.25.25 0 010 .354l-5.025 5.025a.25.25 0 01-.354 0l-6.25-6.25a.25.25 0 01-.073-.177zm-1.5 0V2.75C1 1.784 1.784 1 2.75 1h5.025c.464 0 .91.184 1.238.513l6.25 6.25a1.75 1.75 0 010 2.474l-5.026 5.026a1.75 1.75 0 01-2.474 0l-6.25-6.25A1.75 1.75 0 011 7.775zM6 5a1 1 0 100 2 1 1 0 000-2z"
              ></path>
            </svg>
            <span class="ml-2">
              <strong class="group-hover:text-blue-600">v2.0.1</strong>
              <span
                class="ml-1 text-xs border border-green-600 text-green-600 px-2 rounded-full inline-block font-semibold"
                >Latest</span
              >
              <span
                class="block text-xs group-hover:text-blue-600 text-gray-600 mt-1"
                >on 19 Nov 2020</span
              >
            </span>
          </a>

          <div class="mt-4">
            <a href="#" class="text-blue-600 hover:underline text-xs"
              >+144 releases</a
            >
          </div>
        </div>

        <div class="border-t py-5">
          <h1>
            <strong class="text-base">Packages</strong>
          </h1>
          <p class="mt-3 text-gray-600">No packages published.</p>
        </div>

        <!-- Used by -->
        <div class="used_by border-t py-5">
          <h1>
            <strong class="text-base">Used by</strong>
            <span class="bg-gray-200 px-2 py-0.5 rounded-full text-xs ml-0.5"
              >125k</span
            >
          </h1>
          <div class="mt-5">
            <a href="#" class="flex items-center -space-x-2">
              <img
                src="https://randomuser.me/api/portraits/men/86.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />
              <img
                src="https://randomuser.me/api/portraits/women/86.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />
              <img
                src="https://randomuser.me/api/portraits/men/6.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />
              <img
                src="https://randomuser.me/api/portraits/women/81.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />
              <img
                src="https://randomuser.me/api/portraits/men/26.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />
              <img
                src="https://randomuser.me/api/portraits/women/16.jpg"
                class="w-10 rounded-full border-2 border-white"
                alt="avatar"
              />

              <span
                class="text-xs text-blue-600 font-semibold hover:underline pl-5"
                >+123,702</span
              >
            </a>
          </div>
        </div>

        <!-- Contributors -->
        <div class="contributors border-t py-5">
          <h1>
            <strong class="text-base">Contributors</strong>
            <span class="bg-gray-200 px-2 py-0.5 rounded-full text-xs ml-0.5"
              >152</span
            >
          </h1>
          <div class="mt-2">
            <div href="#" class="flex items-center flex-wrap">
              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/men/34.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>

              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/women/87.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
              /></a>
              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/men/36.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
              /></a>
              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/women/41.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
              /></a>
              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/men/66.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>
              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/women/44.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>

              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/men/23.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>

              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/women/14.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>

              <a href="#">
                <img
                  src="https://randomuser.me/api/portraits/men/40.jpg"
                  class="w-10 rounded-full mr-2 mt-2"
                  alt="avatar"
                />
              </a>
            </div>

            <div class="mt-4">
              <a href="#" class="text-xs text-blue-600 hover:underline mt-3"
                >+141 contributors</a
              >
            </div>
          </div>
        </div>

        <!-- Languages -->
        <div class="languages border-t py-5">
          <h4 class="text-base font-semibold">Languages</h4>
          <div class="mt-4 flex">
            <div
              class="w-11/12 h-2 rounded-md rounded-r-none bg-purple-800"
            ></div>
            <div
              class="w-1/12 h-2 rounded-md rounded-l-none bg-yellow-400"
            ></div>
          </div>
          <ul class="mt-2 flex space-x-8 items-center text-xs">
            <li class="flex items-center">
              <span class="w-2 h-2 rounded-full bg-purple-800"></span>
              <div class="ml-4">
                <span class="font-semibold">CSS</span>
                <span class="text-gray-600">96.8%</span>
              </div>
            </li>
            <li class="flex items-center">
              <span class="w-2 h-2 rounded-full bg-yellow-400"></span>
              <div class="ml-4">
                <span class="font-semibold">JavaScript</span>
                <span class="text-gray-600">3.2%</span>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <!-- end code-rep-container -->
    </div>

    <!-- footer -->
    <footer
      class="container mx-auto border-t py-10 flex justify-between items-center text-xs"
    >
      <div class="flex gap-12">
        <span class="text-gray-600"
          >&copy; {{ new Date().getFullYear() }} Github, Inc</span
        >
        <ul class="flex gap-14">
          <a href="#" class="text-blue-600 hover:underline">Terms</a>
          <a href="#" class="text-blue-600 hover:underline">Privacy</a>
          <a href="#" class="text-blue-600 hover:underline">Security</a>
          <a href="#" class="text-blue-600 hover:underline">Status</a>
          <a href="#" class="text-blue-600 hover:underline">Help</a>
        </ul>
      </div>
      <div class="mx-8">
        <svg
          class="w-6 h-6 fill-current text-gray-300 hover:text-gray-500 cursor-pointer"
          viewBox="0 0 16 16"
          aria-hidden="true"
        >
          <path
            fill-rule="evenodd"
            d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
          ></path>
        </svg>
      </div>
      <ul class="flex gap-16">
        <a href="#" class="text-blue-600 hover:underline">Contact Github</a>
        <a href="#" class="text-blue-600 hover:underline">Pricing</a>
        <a href="#" class="text-blue-600 hover:underline">API</a>
        <a href="#" class="text-blue-600 hover:underline">Training</a>
        <a href="#" class="text-blue-600 hover:underline">Blog</a>
        <a href="#" class="text-blue-600 hover:underline">About</a>
      </ul>
    </footer>
  </div>
</template>

<script>
export default {
  head: {
    title: 'Github Clone',
  },
  data() {
    return {
      commitsData: [
        {
          id: 1,
          resourceType: 'dir',
          resourceName: 'assets',
          commitMsg: 'Initial commit',
          commitDate: '4 days ago',
        },
        {
          id: 2,
          resourceType: 'dir',
          resourceName: 'components',
          commitMsg: 'Feature: Header UI designed',
          commitDate: '4 days ago',
        },
        {
          id: 3,
          resourceType: 'dir',
          resourceName: 'layouts',
          commitMsg: 'Initial commit',
          commitDate: '4 days ago',
        },
        {
          id: 4,
          resourceType: 'file',
          resourceName: 'index.html',
          commitMsg: 'Feature: Header UI designed',
          commitDate: '4 days ago',
        },
        {
          id: 5,
          resourceType: 'file',
          resourceName: 'tailwind.config.js',
          commitMsg: 'Initial commit',
          commitDate: '4 days ago',
        },
      ],
    }
  },
}
</script>

<style></style>
