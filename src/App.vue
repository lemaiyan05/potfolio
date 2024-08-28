<script setup>

</script>

<template>
    <div  class="font-sans text-gray-900 pb-12 ">
      <header class="bg-teal-600 text-white p-4  fixed w-full z-50 ">
        <nav class="container mx-auto flex justify-between items-center  h-24">
          <div class="text-3xl font-bold">My Portfolio</div>
          <div>
            <a href="#home" class="px-4 py-2 hover:underline">Home</a>
            <a href="#about" class="px-4 py-2 hover:underline">About</a>
            <a href="#projects" class="px-4 py-2 hover:underline">Projects</a>
            <a href="#skills" class="px-4 py-2 hover:underline">Skills</a>
            <a href="#contact" class="px-4 py-2 hover:underline">Contact</a>
          </div>
        </nav>
      </header>
  
      <main class="mt-16">
  
        <section id="home" class="min-h-screen bg-blue-300 flex items-center justify-center">
          <div class="text-center">
            <div class="item-center pl-48">
            <img src="./assets/images/pic. lemaiyan.png" class="w-72 h-72 rounded-2xl ">
        </div>
            <h1 class="text-5xl font-bold mb-4">Hello, I'm James Lemaiyan</h1>
            <p class="text-xl mb-4">Front end Developer & Designer</p>
            <a href="" class="mt-4 inline-block bg-teal-500 text-white px-6 py-3 rounded-full hover:bg-teal-600">View My Work</a>
          </div>
        </section>
  
        
        <section id="about" class="min-h-screen bg-gray-300 flex items-center justify-center">
          <div class="container mx-auto p-8 text-center">
            <h2 class="text-4xl font-semibold mb-8">About Me</h2>
            <p class="text-lg leading-relaxed mb-8">I am a passionate Front end developer with over 2 years of experience in building web applications using modern technologies such as Vue, React, Node.js, and more. My mission is to design and build exceptional digital experiences. When I'm not coding, I enjoy designing and exploring new technologies.</p>
            <img class="mx-auto rounded-full w-48 h-48 object-cover mb-8" src="" alt="Your Name">
          </div>
        </section>
  
      
        <section id="projects" class="min-h-screen bg-blue-100 py-12">
          <div class="container mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-12">My Projects</h2>
            <div class="flex space-x-4">
                
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
              <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                <img src="" alt="Project 1" class="w-full h-48 object-cover mb-4 rounded-t-lg">
                <h3 class="text-2xl font-semibold mb-2">Project 1</h3>
                <p class="text-gray-600">A description of the project. Mention the technologies used and the goals achieved.</p>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 ">
              <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                <img src="" alt="Project 1" class="w-full h-48 object-cover mb-4 rounded-t-lg">
                <h3 class="text-2xl font-semibold mb-2">Project 1</h3>
                <p class="text-gray-600">A description of the project. Mention the technologies used and the goals achieved.</p>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
              <div class="bg-white p-6 rounded-lg shadow-lg hover:shadow-xl transition duration-300">
                <img src="" alt="Project 1" class="w-full h-48 object-cover mb-4 rounded-t-lg">
                <h3 class="text-2xl font-semibold mb-2">Project 1</h3>
                <p class="text-gray-600">A description of the project. Mention the technologies used and the goals achieved.</p>
              </div>
            </div>

        </div>

          </div>
        </section>
  
      
        <section id="skills" class="min-h-screen bg-gray-100 py-12">
          <div class="container mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-12">My Skills</h2>
            <div class="grid grid-cols-2 sm:grid-cols-4 gap-8">
              <div class="p-6">
                <i class="fab fa-js text-4xl text-teal-500"></i>
                <h3 class="text-xl font-semibold mt-4">JavaScript</h3>
              </div>
            
            </div>
          </div>
        </section>
  
        
        <section id="contact" class="min-h-screen bg-gray-200 py-12">
          <div class="container mx-auto text-center">
            <h2 class="text-4xl font-semibold mb-8">Contact Me</h2>
            <form class="w-full max-w-lg mx-auto">
              <div class="mb-4">
                <input class="bg-white border border-gray-300 text-gray-900 py-3 px-4 w-full rounded focus:outline-none focus:ring-2 focus:ring-teal-500" type="text" placeholder="Your Name">
              </div>
              <div class="mb-4">
                <input class="bg-white border border-gray-300 text-gray-900 py-3 px-4 w-full rounded focus:outline-none focus:ring-2 focus:ring-teal-500" type="email" placeholder="Your Email">
              </div>
              <div class="mb-4">
                <textarea class="bg-white border border-gray-300 text-gray-900 py-3 px-4 w-full rounded focus:outline-none focus:ring-2 focus:ring-teal-500" placeholder="Your Message"></textarea>
              </div>
              <button class="bg-teal-500 text-white py-3 px-6 rounded hover:bg-teal-600">Send Message</button>
            </form>
          </div>
        </section>
      </main>
  
      <footer class="bg-gray-800 text-white py-6 text-center">
        <p>&copy; 2024 Your Name. All rights reserved.</p>
        <div class="flex justify-center space-x-4 mt-4">
          <a href="https://github.com" class="hover:text-teal-500"><i class="fab fa-github text-2xl"></i></a>
          <a href="https://linkedin.com" class="hover:text-teal-500"><i class="fab fa-linkedin text-2xl"></i></a>
          
        </div>
      </footer>
    </div>
  </template>
  
  <!-- <script>
  export default {
    name: "App",
  };
  
  </script> -->
  
