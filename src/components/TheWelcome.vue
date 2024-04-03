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
    <template #heading>Profile</template>

  <h4>Nama : Randy Ivando</h4>
  <h4>Tempat tanggal Lahir : Perawang, 14 july 2003</h4>
  <h4>Fakultas : Teknik Informatika </h4>
  

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    <h4>Sekolah Dasar : SDN 001  Perawang</h4>
    <h4>Sekolah Menengah Pertama : SMP 012 Mandau</h4>
    <h4>Sekolah Menengag Atas : SMA 010 Mandau</h4>
    <h4>Universitas : Universitas Islam Riau (UIR)</h4>

   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hard Skills </template>

    <h4>C++</h4>
    <h4>Python</h4>
    <h4>Figma</h4>
    <h4>MS Word</h4>
    <h4>MS Power Point</h4>
    <h4>HTML, CSS, JavaScript</h4>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Soft Skills</template>
    <h4>Bisa bekerja sama dengan baik</h4>
    <h4>Komunikatif</h4>
    <h4>Disiplin</h4>
    <h4>Jujur</h4>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Hobby</template>
    <h4>Membaca</h4>
    <h4>Badminto</h4>
    <h4>Competitive Player</h4>
  </WelcomeItem>
</template>
