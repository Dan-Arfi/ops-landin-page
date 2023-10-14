<template>
  <div data-theme="light">
    <div
      class="absolute inset-0 h-full w-full bg-base-100 bg-[linear-gradient(to_right,#80808012_1px,transparent_1px),linear-gradient(to_bottom,#80808012_1px,transparent_1px)] bg-[size:24px_24px]"
    ></div>

    <nav class="navbar bg-base-100 shadow-lg sticky top-0 w-full z-50">
      <div class="flex-1 px-2 mx-2">
        <span class="text-lg font-bold">Mega City Interactive</span>
      </div>
    </nav>

    <div class="hero min-h-screen bg-transparent">
      <div class="hero-content flex-col lg:flex-row">
        <div>
          <h1 class="text-5xl font-bold">OPS - your next meal</h1>
          <p class="py-6">
            🍴📱 Explore and share delightful recipes worldwide with our
            intuitive app. Join a vibrant community of food lovers, capture your
            kitchen victories, and savor the joy of cooking with us! 🌟🥘📸
          </p>

          <div
            class="flex mt-3 w-48 h-14 bg-black text-white rounded-lg items-center justify-center"
          >
            <div class="mr-3">
              <svg viewBox="30 336.7 120.9 129.2" width="30">
                <path
                  fill="#FFD400"
                  d="M119.2,421.2c15.3-8.4,27-14.8,28-15.3c3.2-1.7,6.5-6.2,0-9.7  c-2.1-1.1-13.4-7.3-28-15.3l-20.1,20.2L119.2,421.2z"
                />
                <path
                  fill="#FF3333"
                  d="M99.1,401.1l-64.2,64.7c1.5,0.2,3.2-0.2,5.2-1.3  c4.2-2.3,48.8-26.7,79.1-43.3L99.1,401.1L99.1,401.1z"
                />
                <path
                  fill="#48FF48"
                  d="M99.1,401.1l20.1-20.2c0,0-74.6-40.7-79.1-43.1  c-1.7-1-3.6-1.3-5.3-1L99.1,401.1z"
                />
                <path
                  fill="#3BCCFF"
                  d="M99.1,401.1l-64.3-64.3c-2.6,0.6-4.8,2.9-4.8,7.6  c0,7.5,0,107.5,0,113.8c0,4.3,1.7,7.4,4.9,7.7L99.1,401.1z"
                />
              </svg>
            </div>
            <div>
              <div class="text-xs">GET IT ON</div>
              <div class="text-xl font-semibold font-sans -mt-1">
                Google Play
              </div>
            </div>
          </div>
        </div>

        <img src="@/assets/phone1.png" class="max-w-sm" />
      </div>
    </div>

    <footer class="footer footer-center p-10 bg-primary text-primary-content">
      <aside>
        <p class="font-bold">
          Mega City Interactive Ltd. <br />by
          <a href="https://github.com/Dan-Arfi" class="underline">Dan Arfi</a>
          and
          <a href="https://github.com/forecaster-cyber" class="underline"
            >Serg Brainin</a
          >
        </p>
        <p>Copyright © 2023 - All right reserved</p>
      </aside>
    </footer>
  </div>
</template>
