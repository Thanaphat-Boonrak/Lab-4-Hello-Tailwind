<script setup>
import ProfileCard from "./components/ProfileCard.vue";
import me from "./assets/profileimg.jpg";
import pun from "./assets/pun.jpg"
import note from "./assets/note.jpg"
</script>

<template>
  <div
    class="flex items-center justify-center gap-8 min-h-screen bg-gradient-to-br from-green-500 to-sky-400"
  >
    <ProfileCard
      :profileimg="me"
      :background="profileimg"
      name="Thanaphat"
      subheading="Student, 20 , BKK"
      :followers="1"
      :following="100000"
      :projects="50"
    />

        <ProfileCard
      :profileimg="pun"
      :background="profileimg"
      name="Sakdichot"
      subheading="Student, 20 , BKK"
      :followers="200000"
      :following="123"
      :projects="100"
    />

           <ProfileCard
      :profileimg="note"
      :background="profileimg"
      name="Chayanon"
      subheading="Student, 20 , BKK"
      :followers="200000"
      :following="3213123"
      :projects="50"
    />
  </div>
</template>
