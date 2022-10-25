<template>
  <section id="contact-us" class="contact-section bg-bright-gray pt-9 pb-40">
    <div class="max-w-7xl mx-auto lg:grid lg:grid-cols-2 px-4">
      <div
        class="py-12 before:content-[''] before:block before:bg-[#B9B9B9] before:absolute before:w-[85px] before:h-2"
      >
        <h1 class="font-bold text-[42px] leading-[75px] text-debian-red mt-10">
          Questions?
        </h1>
        <h1 class="font-bold text-[42px] leading-[75px] text-debian-red">
          Need Product ideas?
        </h1>
        <h1 class="font-bold text-[42px] leading-[75px] text-debian-red">
          Let's connect.
        </h1>
        <div class="mt-7">
          <h6 class="font-bold text-debian-red">Canada Toll-Free:</h6>
          <p class="text-debian-red">1-866-366-9766</p>
        </div>

        <div class="mt-7">
          <h6 class="font-bold text-debian-red">US Toll-Free:</h6>
          <p class="text-debian-red">1-877-920-7924</p>
        </div>
      </div>
      <div class="lg:pt-10 lg:pl-6">
        <form class="max-w-md">
          <div class="flex flex-col mt-[60px]">
            <label class="text-cerise font-bold mb-1.5">Name</label>
            <input
              type="text"
              class="px-5 py-3 bg-white focus:border-cerise border hover:border-cerise bg-cultured focus-visible:rounded-none focus-visible:border focus-visible:border-cerise focus-visible:outline-0"
            />
          </div>

          <div class="flex flex-col mt-10">
            <label class="text-cerise font-bold mb-1.5">Email</label>
            <input
              type="email"
              class="px-5 py-3 bg-white focus:border-cerise border hover:border-cerise bg-cultured focus-visible:rounded-none focus-visible:border focus-visible:border-cerise focus-visible:outline-0"
            />
          </div>

          <div class="flex flex-col mt-10">
            <label class="text-cerise font-bold mb-1.5">Company Name</label>
            <input
              type="text"
              class="px-5 py-3 bg-white focus:border-cerise border hover:border-cerise bg-cultured focus-visible:rounded-none focus-visible:border focus-visible:border-cerise focus-visible:outline-0"
            />
          </div>

          <div class="flex flex-col mt-10">
            <label class="text-cerise font-bold mb-1.5">Message</label>
            <textarea
              rows="8"
              class="border hover:border-cerise px-5 py-3 bg-cultured focus-visible:rounded-none focus-visible:border focus-visible:border-cerise focus-visible:outline-0"
            ></textarea>
          </div>

          <button
            class="px--5 py-4 w-64 text-white text-center bg-cerise mt-6 text-xs font-bold hover:bg-debian-red border-0 uppercase"
          >
            Submit
          </button>
        </form>
      </div>
    </div>
  </section>
</template>
