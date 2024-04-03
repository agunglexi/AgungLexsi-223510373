<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Tentang Saya</template>
    Saat ini, saya tengah menempuh pendidikan sebagai mahasiswa di Universitas Islam Riau, yang berlokasi di Jalan Kaharuddin Nst, Pekanbaru. Sedang berada di semester 4, saya mengambil jurusan Teknik Informatika di institusi tersebut.
    Saya Berasal dari Kota Siak, Riau 
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Saat ini berkuliah di 
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya, saya bersekolah di Sekolah Menengah Atas
    <a href="https://smanegeri1kerincikanan.sch.id/" target="_blank" rel="noopener">SMA 1 Kerinci kanan</a>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi saya</template>
    Melalui hobi, saya temukan kebahagiaan dalam kegiatan yang saya cintai.
    <ul>
      <li>Futsal</li>
      <li>Berenang</li>
      <li>Basket</li>
      <li>Voli</li>
      <li>Magic chess</li>
    </ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman</template>
    Saya percaya bahwa pengalaman adalah guru terbaik dalam hidup saya. Setiap momen memberikan pelajaran berharga yang saya bisa ambil. Saya tidak akan menyia-nyiakan kesempatan untuk belajar dan berkembang dari setiap pengalaman yang saya alami.
    <ul>
    <li>02SN</li>
      <li>Magang</li>
      <li>Mengikuti Seminar Cyber Securiy</li>
</ul>
  </WelcomeItem>
  <hr />
  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>
untuk menghubungi saya kalian dapat mengontak di bawah ini
   sosmed Instagram :<a href="https://www.instagram.com/agunglexsi_" target="_blank">agunglexsi_ </a
    ><br />
    Email : agungsiak707@gmail.com<br/>
    No HP : 083894280058
  </WelcomeItem>
</template>