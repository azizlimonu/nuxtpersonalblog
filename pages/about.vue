<script setup lang="ts">
defineOgImage()
</script>

<template>
  <div class="py-5">
    <div class="sm:grid grid-cols-8 px-6 py-5 sm:py-9 gap-5 container max-w-5xl  mx-auto">
      <div class="col-span-5  max-w-md">
        <div class="flex justify-between">
          <div>
            <h1 class="text-xl sm:text-4xl  pb-2 font-bold ">
              Al Asad Nur Riyad
            </h1>

            <div class="my-3 space-x-3 pb-10">
              <NuxtLink
                to="https://github.com/azizlimonu"
                target="_blank"
                class="px-3 py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="Github"
              >
                <Icon name="fa:github" size="1em" />
              </NuxtLink>
              <NuxtLink
                to="https://www.linkedin.com/in/aziz-limonu-ba20a42a6/"
                target="_blank"
                class="px-3 py-2 bg-gray-300 text-gray-800 rounded-md dark:bg-slate-700 dark:text-[#F1F2F4]"
                aria-label="LinkedIn"
              >
                <Icon name="fa:linkedin-square" size="1em" />
              </NuxtLink>
            </div>
          </div>
          <div class="sm:hidden block col-span-3 pb-5 dark:bg-slate-700 dark:text-[#F1F2F4]">
            <NuxtImg
              src="/profile.jpg"
              width="125"
              height="115"
              quality="50"
              class="rounded-md"
            />
          </div>
        </div>

        <h3 class="text-base sm:text-3xl font-semibold pb-7 sm:pb-12">
          Software Engineer, Frontend Developer, Backend Developer.
        </h3>

        <p>Hello world! 👋 I'm an enthusiastic and dedicated web developer, With a solid foundation built over the past two years, I bring both experience and a fresh perspective to my work. Currently seeking exciting opportunities to contribute my skills and collaborate on innovative web development projects!</p>
      </div>
      <div class="hidden sm:block col-span-3">
        <NuxtImg
          src="/profile.jpg"
          width="450"
          height="500"
          quality="50"
          class="rounded-md"
        />
      </div>
    </div>
  </div>
</template>
