<template>
  <div class="bg-gradient-to-b from-gray-200 to-gray-100 min-h-screen py-10 px-5 relative">
    <!-- Background -->
    <div class="relative bg-white/80 backdrop-blur-sm shadow-lg rounded-xl max-w-6xl mx-auto p-10">
      
      <!-- Highlight Bar dengan Foto Profil di Tengah dan Background Transparan -->
      <header 
        class="relative h-80 flex flex-col items-center justify-center bg-cover bg-center rounded-lg shadow-md p-6" 
        :style="{ backgroundImage: 'linear-gradient(rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0.5)), url(/grey.jpeg)' }"
      >
        <!-- Foto Profil di Tengah -->
        <img
          src="/Nuriza.jpg"
          alt="Profile Picture"
          class="w-40 h-40 rounded-full shadow-lg border-4 border-white object-cover"
        />
        <!-- Info Profil dan Media Sosial -->
        <div class="text-center text-black">
          <h1 class="text-4xl font-bold">Nuriza Zulfa Nabila</h1>
          <p class="text-lg">Information Technology Students of Brawijaya University</p>
          <div class="flex justify-center space-x-6 mt-4">
            <a href="#" class="text-black hover:text-blue-500"><i class="fab fa-github"></i> GitHub</a>
            <a href="#" class="text-black hover:text-blue-500"><i class="fab fa-instagram"></i> Instagram</a>
            <a href="#" class="text-black hover:text-blue-500"><i class="fab fa-twitter"></i> Twitter</a>
          </div>
        </div>
      </header>

      <!-- Section Description -->
      <section class="text-center py-8">
        <h2 class="text-3xl font-semibold text-gray-800 mb-4">About Me</h2>
        <p class="text-gray-700 leading-relaxed mx-auto max-w-3xl">
          I am an active student of Information Technology at Brawijaya University, Faculty of Vocational Studies since 2023. 
          I was once an Internship Staff of the Information Technology Study Program Student Association in the PUSKOMINFO Department. 
          I am also experienced in participating in a committee, namely the TechFair committee in 2023 in the PDD division. 
          I am also currently active in the organization Kumpulan Mahasiswa Sragen Jawa Timur (KMS JATIM) in the Public Relations division, 
          UKM Forum Mahasiswa Peduli Inklusi (FORMAPI) as a Young Staff in the Advocacy division, and active in one committee at the faculty level, 
          namely CREANOMIC. I was also active in various organizations and committees when I was in high school. 
        </p>
      </section>

      <!-- Experience and Education Section -->
      <section class="grid grid-cols-1 md:grid-cols-2 gap-8 py-8">
        <!-- Education -->
        <div class="bg-gray-100 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold text-gray-800 mb-4">Education</h3>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">MIPA Department</h4>
            <p class="text-gray-600">Senior High School 1 Sragen, 2020 - 2023</p>
          </div>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Information Technology - Diploma</h4>
            <p class="text-gray-600">Brawijaya University Faculty of Vocational Studies, 2023 - Now</p>
          </div>
          <div>
            <h4 class="text-lg font-semibold text-gray-700">Course Student</h4>
            <p class="text-gray-600">Kampung Inggris Languange Center Yogyakarta, 2024</p>
          </div>
        </div>

        <!-- Experience -->
        <div class="bg-gray-100 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold text-gray-800 mb-4">Experience</h3>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Intra-School Student Organization (OSIS) Spirituality Division</h4>
            <p class="text-gray-600">SMPIT AZ-ZAHRA SRAGEN, 2017-2019</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>School Anniversary Committee</li>
              <li>School Event Committee</li>
              <li>Person in charge of spiritual activities</li>
              <li>Person in charge of bunga tabur</li>
              <li>Person in charge of Friday Infaq</li>
            </ul>
          </div>
           <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Staff of SMANSA Student Creativity Magazine (MAVISSA) Art and Graphic Design Division</h4>
            <p class="text-gray-600">Senior High School 1 Sragen, 2020-2022</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>Create an instagram feed design</li>
              <li>Creating reels design</li>
              <li>Create instagram story design</li>
              <li>Creating a magazine design</li>
              <li>Shooting calendar photos</li>
              <li>MAVISSA Anniversary Committee</li>
              <li>MAVISSA Open Recruitment Committee</li>
              <li>MAVISSA Position Handover Committee</li>
            </ul>
          </div>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Internship Staff of Information Technology Study Program Student Association (HMPSTI) PUSKOMINFO Department</h4>
            <p class="text-gray-600">Brawijaya University Faculty of Vocational Studies, September - December 2023</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>Create Technotion 2023 instagram feed design.</li>
              <li>Holding and managing Technotion 2023's instagram.</li>
            </ul>
          </div>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">TechFair 2023 Committee PDD Division</h4>
            <p class="text-gray-600">Brawijaya University Faculty of Vocational Studies, September - November 2023</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>Making event decorations.</li>
            </ul>
          </div>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Public Relations Staff at Kumpulan Mahasiswa Sragen Jawa Timur (KMS Jatim)</h4>
            <p class="text-gray-600">Sragen, March 2024 - Now</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>KMS JATIM CUP III Committee</li>
              <li>School to School Committee</li>
              <li>Campus Expo Committee</li>
            </ul>
          </div>
          <div class="mb-4">
            <h4 class="text-lg font-semibold text-gray-700">Forum Mahasiswa Peduli Inklusi (FORMAPI) Advocacy Department</h4>
            <p class="text-gray-600">Brawijaya University, August 2024 - Now</p>
            <ul class="list-disc list-inside text-gray-600 mt-2">
              <li>FORMAPI Goes to Faculty Committee DDM Division</li>
            </ul>
          </div>
          <div>
            <h4 class="text-lg font-semibold text-gray-700">CREANOMIC Committee Consumption Division</h4>
            <p class="text-gray-600">Brawijaya University Faculty of Vocational Studies, August 2024 - Now</p>
          </div>
        </div>
      </section>

      <!-- Skills and Interests Section -->
      <section class="grid grid-cols-1 md:grid-cols-2 gap-8 py-8">
        <!-- Skills -->
        <div class="bg-gray-100 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold text-gray-800 mb-4">Skills</h3>
          <ul class="list-disc list-inside text-gray-600">
            <li>Corel Draw</li>
            <li>Canva</li>
            <li>Figma</li>
            <li>Ibis Paint</li>
            <li>HTML / PHP</li>
          </ul>
        </div>

        <!-- Interests -->
        <div class="bg-gray-100 p-6 rounded-lg shadow-md">
          <h3 class="text-xl font-semibold text-gray-800 mb-4">Interests</h3>
          <ul class="list-disc list-inside text-gray-600">
            <li>UI/UX Designer</li>
          </ul>
        </div>
      </section>

      <!-- Portfolio Section -->
      <section class="py-8">
        <h3 class="text-2xl font-semibold text-gray-800 mb-6 text-center">Portfolio</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 1</h4>
            <p class="text-gray-600">MAVISSA E-Magazine Design 2nd Edition “Hope”</p>
          </div>
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 2</h4>
            <p class="text-gray-600">MAVISSA Magazine Design 47th Edition “Rise Up”</p>
          </div>
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 3</h4>
            <p class="text-gray-600">MAVISSA Instagram Feeds Design for 2020-2022 period</p>
          </div>
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 4</h4>
            <p class="text-gray-600">Instagram Feeds Design Technotion 2023</p>
          </div>
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 5</h4>
            <p class="text-gray-600">Blog Admin with HTML / PHP</p>
          </div>
          <div class="bg-gray-100 p-6 rounded-lg shadow-md">
            <h4 class="text-lg font-semibold text-gray-700">Project 6</h4>
            <p class="text-gray-600">Creating a Camera Rental Website with HTML / PHP</p>
          </div>
        </div>
      </section>

      <!-- Contact Form Section -->
      <section class="py-8">
        <h3 class="text-2xl font-semibold text-gray-800 mb-6 text-center">Contact Me</h3>
        <form class="bg-gray-100 p-6 rounded-lg shadow-md max-w-lg mx-auto">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
            <input
              type="text"
              placeholder="Your Name"
              class="w-full p-3 rounded-md border-gray-300"
            />
            <input
              type="email"
              placeholder="Your Email"
              class="w-full p-3 rounded-md border-gray-300"
            />
          </div>
          <textarea
            placeholder="Your Message"
            class="w-full mt-4 p-3 rounded-md border-gray-300"
            rows="5"
          ></textarea>
          <button
            type="submit"
            class="bg-blue-500 hover:bg-blue-600 text-white py-2 px-6 rounded-lg mt-4"
          >
            Send Message
          </button>
        </form>
      </section>
    </div>
  </div>
</template>

<style>
  /* Atur background gambar dan ukuran highlight */
  header {
    background-size: cover;
    background-position: center;
  }
</style>
