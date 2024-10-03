<script setup>
import CardContent from './CardContent.vue'
</script>
<template>
  <div class="grid mt-20">
    <div class="items-center justify-center overflow-y-auto overflow-x-hidden">
      <div class="mb-10">
        <p class="text-gray-400 mb-4">
          I thoroughly enjoy diving into programming and everything related to it. I am a
          self-taught programmer, learning through online classes at Dicoding Indonesia, YouTube
          tutorials, and several interesting books. I approach every opportunity with a commitment
          to continuous learning, always looking for ways to broaden my knowledge and sharpen my
          skills with<a class="font-bold text-white"> a growth mindset.</a> <br /><br />
          Outside of programming, I am also interested in network engineering, keeping up with the
          latest device trends and certification training. Additionally, I enjoy reading psychology
          and self-development books that explore the meaning of life~
        </p>
      </div>
      <div class="text-center">
        <h1 class="text-2xl font-bold mb-4">Experience Projects</h1>
      </div>
      <div class="grid mb-10">
        <CardContent
          title="Pustaka Digital"
          description="Pustaka Digital is a digital library platform that provides access to a wide range of books and resources. It aims to make reading more accessible and convenient by offering a vast collection of digital books that can be read anytime, anywhere. The platform supports various formats and devices, ensuring a seamless reading experience for users."
          image="./projecta.png"
          :links="['Laravel 11', 'Flutter', 'MySQL', 'Material-UI']"
        />

        <CardContent
          title="JDIH Samarinda"
          description="JDIH Samarinda is a legal information system that provides access to legal documents, regulations, and other legal resources related to the city of Samarinda. The system aims to promote transparency, accountability, and good governance by making legal information more accessible to the public. Users can search, view, and download legal documents through the platform, helping them stay informed about the latest laws and regulations in the city."
          image="./jdih.png"
          :links="['React Native', 'Node.js', 'Material-UI']"
        />
        <CardContent
          title="Layanan Informasi Pengaduan Masyarakat"
          description="Layanan Informasi Pengaduan Masyarakat is a public complaint information service that allows citizens to report issues, problems, or concerns to the local government. The platform aims to improve public services, enhance transparency, and strengthen accountability by enabling citizens to voice their opinions and feedback. Users can submit complaints, track their status, and receive updates on the resolution process, helping them engage with the government and contribute to community development."
          image="./projectc.png"
          :links="['React', 'Tailwind CSS', 'Material-Tailwind']"
        />
      </div>
    </div>
  </div>
</template>

<style scoped></style>
