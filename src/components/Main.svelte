<script>
  import Banner from "./Banner.svelte";
  import Links from "./Links.svelte";

  let profilecopia = "profilecopia.jpg";
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
        <div class="mt-6 flex justify-start space-x-1">
          <a href="https://github.com/esarmiem" target="_blank">
            <svg
              class="w-6 h-6 cursor-pointer text-gray-600 hover:text-[#6e5494] fill-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
            >
              <path
                d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"
              />
            </svg>
          </a>
          <a
            href="https://www.linkedin.com/in/elder-sarmiento/"
            target="_blank"
          >
            <svg
              class="w-6 h-6 cursor-pointer text-gray-600 hover:text-blue-500 fill-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 448 512"
            >
              <path
                d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"
              />
            </svg>
          </a>
          <a href="https://www.instagram.com/eldersarmiento/" target="_blank">
            <svg
              class="w-6 h-6 cursor-pointer text-gray-600 hover:text-blue-500 fill-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
            >
              <path
                d="M13.028 2.001a78.82 78.82 0 0 1 2.189.022l.194.007c.224.008.445.018.712.03c1.064.05 1.79.218 2.427.465c.66.254 1.216.598 1.772 1.154a4.908 4.908 0 0 1 1.153 1.771c.247.637.415 1.364.465 2.428c.012.266.022.488.03.712l.006.194a79 79 0 0 1 .023 2.188l.001.746v1.31a78.836 78.836 0 0 1-.023 2.189l-.006.194c-.008.224-.018.445-.03.712c-.05 1.064-.22 1.79-.466 2.427a4.884 4.884 0 0 1-1.153 1.772a4.915 4.915 0 0 1-1.772 1.153c-.637.247-1.363.415-2.427.465c-.267.012-.488.022-.712.03l-.194.006a79 79 0 0 1-2.189.023l-.746.001h-1.309a78.836 78.836 0 0 1-2.189-.023l-.194-.006a60.64 60.64 0 0 1-.712-.03c-1.064-.05-1.79-.22-2.428-.466a4.89 4.89 0 0 1-1.771-1.153a4.904 4.904 0 0 1-1.154-1.772c-.247-.637-.415-1.363-.465-2.427a74.367 74.367 0 0 1-.03-.712l-.005-.194A79.053 79.053 0 0 1 2 13.028v-2.056a78.82 78.82 0 0 1 .022-2.188l.007-.194c.008-.224.018-.446.03-.712c.05-1.065.218-1.79.465-2.428A4.88 4.88 0 0 1 3.68 3.68a4.897 4.897 0 0 1 1.77-1.155c.638-.247 1.363-.415 2.428-.465l.712-.03l.194-.005A79.053 79.053 0 0 1 10.972 2h2.056Zm-1.028 5A5 5 0 1 0 12 17a5 5 0 0 0 0-10Zm0 2A3 3 0 1 1 12.001 15a3 3 0 0 1 0-6Zm5.25-3.5a1.25 1.25 0 0 0 0 2.498a1.25 1.25 0 0 0 0-2.5Z"
              />
            </svg>
          </a>
          <a href="https://www.threads.net/@eldersarmiento" target="_blank">
            <svg
              class="w-6 h-6 cursor-pointer text-gray-600 hover:text-blue-500 fill-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
            >
              <path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M19 7.5c-1.333-3-3.667-4.5-7-4.5c-5 0-8 2.5-8 9s3.5 9 8 9s7-3 7-5s-1-5-7-5c-2.5 0-3 1.25-3 2.5C9 15 10 16 11.5 16c2.5 0 3.5-1.5 3.5-5s-2-4-3-4s-1.833.333-2.5 1"
              />
            </svg>
          </a>
        </div>
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
        <aside class="mt-1 text-md font-semibold text-center text-gray-600">
          <p>Frontend y Mobile Developer apasionado por crear</p>
          experiencias digitales sorprendentes 🎨🖌
        </aside>
      </div>

      <Banner />
      <Links />
    </section>
  </section>
</main>
