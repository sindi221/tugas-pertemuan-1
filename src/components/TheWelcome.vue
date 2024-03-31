<script setup>
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
    <template #heading>PENDIDIKAN</template>

    Saat ini saya kuliah di salah satu Kampus swasta di Riau yaitu
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau</a>
    .
    Sebelumnya saya bersekolah di SMA NEGERI
    <a href="https://www.smkakbar.sch.id/profil-sekolah" target="_blank" rel="noopener">SMA NEGERI SATU TAPUNG HILIR</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat, Tanggal Lahir</template>

    Saya Lahir di sebuah kota kecil di Provinsi <a href="https://id.wikipedia.org/wiki/Sumatera_Utara" target="_blank" rel="noopener"
      >RIAU</a>
      yaitu 
    <a href="https://id.wikipedia.org/wiki/Dolok_Masihul,_Serdang_Bedagai" target="_blank" rel="noopener"
      >tapung hilir</a
    >.pada tanggal
     19 Agustus 2004
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>

    Prodi atau Jurusan Kuliah
Saya mengambil Program didik Teknik Informatika atau biasa disebut IT
    , sekarang saya berada di semester 4 dan berada di kelas paling solid yaitu
    <a href="https://www.instagram.com/b1universe/" target="_blank" rel="noopener">b1UNIVERSE</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>

    Hobi saya lampirkan sebagai berikut : <br />
    1.
    <a href="https://www.youtube.com/watch?v=JKByb0QwwSY" target="_blank" rel="noopener"
      >NGODANG(NGODING KADANG KADANG)</a
    ><br />
    2. <a href="https://cdn.gramedia.com/uploads/items/psychology_of_money.jpg" target="_blank" rel="noopener"
      >Membaca Buku</a> <br/>
    3.  <a href="https://www.instagram.com/p/C3fhehsv-AR/?igsh=ZXg1bDdhZzU2N29s" target="_blank" rel="noopener"
      >Ngopi</a> <br/>
    4. <a href="https://www.youtube.com/watch?v=10pvNtNoQs8&pp=ygUfYmVsYWphciBtZWxlcGFza2FuIGRpcmlueWEgcmVmZg%3D%3D" target="_blank" rel="noopener"
      >Belajar</a> </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Social Media</template>

    Saya lumayan aktif di sosial media dengan tujuan untuk meroastink orang,sarkas mencari informasi serta berkeluh kesah serta untuk hal-hal random saya sehari hari.<br />
    Instagram = @<a href="https://www.instagram.com/sndi_maharani/" target="_blank" rel="noopener"
      >sndi.maharani</a
    > <br/>
dan saya juga memliki secound akun= @<a href="https://www.instagram.com/sec.syns/" target="_blank" rel="noopener"
      >sec.syns</a
    >.
  </WelcomeItem>#ff00c8
</template>