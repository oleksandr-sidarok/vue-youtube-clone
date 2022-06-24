<template>
  <the-header />
  <the-sidebar-small />
  <the-sidebar />
  <the-sidebar-mobile />
  <the-categories />
  <main class="pt-32 px-5 pb-5 xl:ml-64 md:ml-24">
    <div class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 2xl:grid-cols-5 gap-4 max-w-screen-2xl m-auto">
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/edejee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/edqejw3ee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/e31wdejee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/1edejee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/ejee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/aej3ee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/34ejee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/ee/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/934jrndnwe/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/1oirfj3/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/28jdek/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/ncne/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/d3js/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/cnew3/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/cne/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
      <a href="" class="mb-7 group">
        <div class="relative">
          <img src="https://picsum.photos/seed/jfnn/720/404">
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-0 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-0 group-hover:opacity-100 bg-opacity-60 absolute top-8 right-0 bg-black text-white rounded-sm m-1 p-1">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
                  <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h6a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd" />
                </svg>
            </span>
          <span class="opacity-100 group-hover:opacity-0 duration-500 absolute bottom-0 right-0 bg-black text-white rounded-sm m-1 p-1 text-xs font-semibold">6:35</span>
        </div>
        <div class="flex items-start my-3">
          <img src="https://picsum.photos/68" class="mr-3 rounded-full w-9 h-9">
          <div class="text-sm">
            <span class="font-semibold text-gray-800">Video Title 1</span>
            <div class="mt-1 flex items-center">
              <span>Chanel Name 1</span>
              <svg xmlns="http://www.w3.org/2000/svg" class="h-3.5 w-3.5 ml-1" viewBox="0 0 20 20" fill="currentColor">
                <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
              </svg>
            </div>
            <div>
              <span>1K views</span>
              &middot;
              <span>1 day ago</span>
            </div>
          </div>
          <button class="-mt-1 ml-auto p-1 opacity-0 group-hover:opacity-100 text-gray-500 hover:text-gray-700 focus:outline-none">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" viewBox="0 0 20 20" fill="currentColor">
              <path d="M10 6a2 2 0 110-4 2 2 0 010 4zM10 12a2 2 0 110-4 2 2 0 010 4zM10 18a2 2 0 110-4 2 2 0 010 4z" />
            </svg>
          </button>
        </div>
      </a>
    </div>
  </main>
</template>

<script>
  import TheHeader from "./components/TheHeader.vue";
  import TheSidebarSmall from "./components/TheSidebarSmall.vue";
  import TheSidebar from "./components/TheSidebar.vue";
  import TheSidebarMobile from "./components/TheSidebarMobile.vue";
  import TheCategories from "./components/TheCategories.vue";
  export default {
    components: {
      TheHeader,
      TheSidebarSmall,
      TheSidebar,
      TheSidebarMobile,
      TheCategories
    }

  }
</script>

<style>
  .custom-scroll::-webkit-scrollbar {
    width: 1px;
    height: 1px;
  }

  .custom-scroll::-webkit-scrollbar-track {
    background-color: transparent;
  }

  .custom-scroll::-webkit-scrollbar-thumb {
    border-radius: 100px;
    background-color: transparent;
  }

  .custom-scroll:hover::-webkit-scrollbar-thumb {
    border-radius: 100px;
    background-color: gray;
  }
</style>
