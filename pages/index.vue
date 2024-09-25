<template>
    <section id="bg">
        <div class="relative z-10">
            <div class="grid grid-cols-2 gap-2">
                <div id="col-1" class="flex flex-col justify-center ml-6">
                    <h1 class="text-6xl antialiased font-bold text-left" id="judul">Hello, <br> I'am Pai Pai !</h1>
                    <p class="text-xl">I am a Software Engineer <br> and like to create some fucking dope art !!!</p>
                </div>
                <div class="items-center justify-content-center" data-aos="fade-up" data-aos-duration="3000">
                    <img class="items-center justify-content-center" id="photo-profile" src="../assets/img/coba.png">
                </div>
            </div>
        </div>
    </section>
    <section id="bg-2">
        <h1 class="text-center text-5xl font-bold text-white mt-6 mb-8" id="judul">Where I'am Good at</h1>
        <div class="flex flex-col justify-center mt-6 mb-8">
            <div class="grid grid-cols-4 gap-4">
            <div data-aos="fade-up" data-aos-duration="1500" data-aos-easing="linear">
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img" src="../assets/img/website-vector-bw.png">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Web Development</h5>
                    <p class="font-normal text-center">I think I am Good at this point.</p>
                </a>
            </div>
            <div  data-aos="fade-up" data-aos-duration="3000">
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img-2" src="../assets/img/design-vector-bw.png">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Design Graphic</h5>
                    <p class="font-normal text-center">I think I am Good at this point.</p>
                </a>
            </div>
            <div data-aos="fade-up" data-aos-duration="1500">
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img-3" src="../assets/img/edit-vector-bw.png">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Editing Video</h5>
                    <p class="font-normal text-center">I think I am Good at this point.</p>
                </a>
            </div>
            <div  data-aos="fade-up" data-aos-duration="3000" data-aos-easing="linear">
                <a href="#" id="card" class="block max-w-sm p-6 rounded-lg dark:bg-gray-800 dark:border-gray-700 h-96 flex flex-col justify-center">
                    <img id="card-img-4" src="../assets/img/music-vector-bw.png">
                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-center pt-5">Music Production</h5>
                    <p class="font-normal text-center">I think I am Good at this point.</p>
                </a>
            </div>
        </div>
        </div>
    </section>
    <section id="bg">
      <div class="relative z-10">
          <h1 class="text-center text-5xl font-bold mb-8" id="judul">My Experience</h1>
          <div class="flex flex-col justify-center items-center mt-6 mb-8">
              <div class="grid grid-cols-2 gap-8">
                  <div class="rounded-lg p-8 text-center h-96 flex flex-col justify-center items-center" data-aos="zoom-in-up" data-aos-duration="1500" data-aos-easing="linear" id="card">
                      <img class="h-40 mx-auto" id="card-img-5" src="../assets/img/gamelab-logo-bw.png">
                      <h3 class="text-2xl font-bold mb-2">Gamelab ID</h3>
                      <p class="font-medium text-gold">Software Engineer</p>
                      <p class="mt-4">Developing web applications using HTML, CSS, JavaScript, React.js, and Node.js</p>
                      <p class="mt-2 text-sm text-gray-500">August 2022 - December 2022</p>
                  </div>
                  <div class="rounded-lg p-8 text-center h-96 flex flex-col justify-center items-center" id="card" data-aos="zoom-in-up" data-aos-duration="3000">
                      <img class="h-40 mx-auto" id="card-img-6" src="../assets/img/telkom-logo-bw.png">
                      <h3 class="text-2xl font-bold mb-2">Telkom DigiUp</h3>
                      <p class="font-medium text-gold">Graphic Designer</p>
                      <p class="mt-4">Create design for Telkom DigiUp Sport.</p>
                      <p class="mt-2 text-sm text-gray-500">December 2022 - January 2023</p>
                  </div>
              </div>
          </div>
      </div>
    </section>
    <section id="bg-2" class="py-12">
      <div class="max-w-2xl mx-auto px-4">
          <h1 class="text-center text-5xl font-bold text-white mb-8" id="judul">Contact Me</h1>
          <form class=" p-6 rounded-lg shadow-lg" id="card" action="#" method="POST">
              <div class="mb-4">
                  <label for="name" class="block text-lg font-medium mb-2">Name</label>
                  <input type="text" id="name" name="name" class="w-full px-4 py-2 text-gray-800 rounded-lg" placeholder="Your Name" required>
              </div>
              <div class="mb-4">
                  <label for="email" class="block text-lg font-medium mb-2">Email</label>
                  <input type="email" id="email" name="email" class="w-full px-4 py-2 text-gray-800 rounded-lg" placeholder="Your Email" required>
              </div>
              <div class="mb-4">
                  <label for="message" class="block text-lg font-medium mb-2">Message</label>
                  <textarea id="message" name="message" rows="5" class="w-full px-4 py-2 text-gray-800 rounded-lg" placeholder="Your Message" required></textarea>
              </div>
              <div class="text-center">
                  <button type="submit" class="bg-gray-900 text-white font-bold py-2 px-6 rounded-lg transition transform hover:scale-105">Send Message</button>
              </div>
          </form>
      </div>
    </section>
    <section class="bg-stone-900 p-10 text-white">
      <div class="relative z-10">
        <div class="grid grid-cols-2 gap-2 text-center">
          <div class="flex flex-col justify-center ml-6">
            <h1>© 2024 Muhammad Fa'iz Ramadhan. All rights reserved</h1>
          </div>
          <div class="flex flex-col justify-center ml-6">
            <h1>@m.faiz.rmdn</h1>
          </div>
        </div>
      </div>
    </section>
</template>
  
<script>
</script>
<style>
#bg {
  position: relative;
  padding-top: 80px;
  padding-bottom: 150px;
  padding-left: 80px;
  padding-right: 80px;
  z-index: 1;
}

#bg::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-image: url("../assets/img/background.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  opacity: 20%;
  z-index: -1;
}
#judul{
    font-family: Shrikhand;
}
#photo-profile{
    max-width: 600px;
    opacity: 80%;
    border-radius: 20px;
    transition: 0.5s;
    filter: drop-shadow(-22px 6px 29px #707070);
}
#photo-profile:hover{
    filter: drop-shadow(9px 6px 29px #707070);
    transform: scale(1.02);
    opacity: 100%;
}

#bg-2{
    background-color: #282828;
    background-size: cover;
    padding-top: 40px;
    padding-bottom: 40px;
    padding-left: 80px;
    padding-right: 80px;
}
#card{
background-color: #d6d6d6;
filter: drop-shadow(-6px 6px 11px #5f5f5f);
transition: 0.3s;
}
#card:hover{
    filter: drop-shadow( 6px 6px 11px #707070);
    /* transform: scale(1.05); */
}

#card-img {
  transition: 0.5s;
}
#card-img-2 {
  transition: 0.5s;
}
#card-img-3 {
  transition: 0.5s;
}
#card-img-4 {
  transition: 0.5s;
}
#card-img-5 {
  transition: 0.5s;
}
#card-img-6 {
  transition: 0.5s;
}

#card:hover #card-img {
  content: url('../assets/img/website-vector.png');
}
#card:hover #card-img-2 {
  content: url('../assets/img/design-vector.png');
}
#card:hover #card-img-3 {
  content: url('../assets/img/edit-vector.png');
}
#card:hover #card-img-4 {
  content: url('../assets/img/music-vector.png');
}
#card:hover #card-img-5 {
  content: url('../assets/img/gamelab-logo.png');
}
#card:hover #card-img-6 {
  content: url('../assets/img/telkom-logo.png');
}
</style>
  