<script>
  import Banner from "./Banner.svelte";
  import Links from "./Links.svelte";
  import Icons from "./socialIcons/Icons.svelte";
  let profilecopia = "profilecopia.webp";
</script>

<main class="flex-block max-w-xl p-4 md:pd-8 mx-auto mt-4">
  <section class="bg-white shadow overflow-hidden rounded-lg">
    <section class="px-4 py-5 sm:px-6 flex justify-between">
      <div>
        <h1 class="text-xl leading-6 font-bold text-gray-900">
          Elder Sarmiento Martinez 🇨🇴
        </h1>
        <h2 class="text-sm leading-6 text-gray-500 -mt-1">@esarmiem</h2>
        <p class="mt-1 pr-12 max-w-2xl text-sm text-gray-500">
          #Flutter #Android #Kotlin #Dart #JavaScript #React #Svelte #Tailwind
          #Figma
        </p>
        <Icons />
      </div>
      <figure>
        <img
          class="rounded-full w-48"
          src={profilecopia}
          alt="Elder Sarmiento"
        />
      </figure>
    </section>
    <section class="border-t border-gray-200">
      <div class="bg-white px-4 py-5 w-full flex justify-center space-x-0.5">
        <aside class="mt-1 text-sm md:text-lg lg:text-lg whitespace-normal font-semibold text-center text-gray-600">
          <p>Analista IT Senior y Desarrollador de Software</p>
          + 9 años de experiencia en la industria tech 🎨
        </aside>
      </div>
      <Banner />
      <Links />
    </section>
  </section>
</main>
