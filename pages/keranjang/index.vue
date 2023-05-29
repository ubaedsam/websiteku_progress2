<template>
<div class="cart">
    <HeroCart></HeroCart>
    <h2 class="text-3xl font-bold mt-12 mb-12 text-center">Order <span class="text-orange-500">List</span></h2>
    <div class="container my-15 px-6 mx-auto">
      <section class="mb-15 text-gray-800 text-center md:text-left">
      <div class="flex flex-col">
          <nav
            class="relative flex w-full flex-wrap items-center justify-between bg-neutral-100 py-3 text-neutral-500 shadow-lg hover:text-neutral-700 focus:text-neutral-700 dark:bg-neutral-600 lg:flex-wrap lg:justify-start"
            data-te-navbar-ref>
            <div class="flex w-full flex-wrap items-center justify-between px-3">
              <nav class="bg-grey-light w-full rounded-md" aria-label="breadcrumb">
                <ol class="list-reset flex">
                  <li>
                    <a
                      href="#"
                      class="text-neutral-500 hover:text-neutral-600 dark:text-neutral-200"
                      >Home</a
                    >
                  </li>
                  <li>
                    <span class="mx-2 text-neutral-500 dark:text-neutral-200"
                      >/</span
                    >
                  </li>
                  <li>
                    <a
                      href="#"
                      class="text-orange-500 hover:text-orange-600 dark:text-orange-200"
                      >Cart</a
                    >
                  </li>
                </ol>
              </nav>
            </div>
          </nav>
      <div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
          <div class="inline-block min-w-full py-2 sm:px-6 lg:px-8">
          <div class="overflow-hidden">
              <table class="min-w-full text-left text-sm font-light">
              <thead class="border-b font-medium dark:border-neutral-500">
                  <tr>
                  <th scope="col" class="px-6 py-4">#</th>
                  <th scope="col" class="px-6 py-4">First</th>
                  <th scope="col" class="px-6 py-4">Last</th>
                  <th scope="col" class="px-6 py-4">Handle</th>
                  </tr>
              </thead>
              <tbody>
                  <tr class="border-b dark:border-neutral-500">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">1</td>
                  <td class="whitespace-nowrap px-6 py-4">Mark</td>
                  <td class="whitespace-nowrap px-6 py-4">Otto</td>
                  <td class="whitespace-nowrap px-6 py-4">@mdo</td>
                  </tr>
                  <tr class="border-b dark:border-neutral-500">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">2</td>
                  <td class="whitespace-nowrap px-6 py-4">Jacob</td>
                  <td class="whitespace-nowrap px-6 py-4">Thornton</td>
                  <td class="whitespace-nowrap px-6 py-4">@fat</td>
                  </tr>
                  <tr class="border-b dark:border-neutral-500">
                  <td class="whitespace-nowrap px-6 py-4 font-medium">3</td>
                  <td class="whitespace-nowrap px-6 py-4">Larry</td>
                  <td class="whitespace-nowrap px-6 py-4">Wild</td>
                  <td class="whitespace-nowrap px-6 py-4">@twitter</td>
                  </tr>
              </tbody>
              </table>
          </div>
          </div>
      </div>
      </div>
      </section>
    </div>
</div>
</template>