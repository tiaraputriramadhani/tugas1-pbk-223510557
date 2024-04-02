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
    <p>Seseorang yang lahir pada 19 November 2003 di Kota Duri dan sedang menempuh pendidikan di Universitas Islam Riau program studi Teknik Informatika. Sedang berusaha mencari kesibukan di tengah hujaman tugas serta keluhan yang tidak akan pernah terlupakan setiap harinya.</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    Pendidikan yang sudah ditempuh :
    <ul>
      <li><a href="https://www.smp3mandau.sch.id/"target="_blank" rel="noopener">SMP Negeri 3 Mandau (2016-2019)</a></li>
      <li><a href="https://dapo.kemdikbud.go.id/sekolah/7D35BE20049606E6936D
" target="_blank" rel="noopener">SMA Negeri 8 Mandau (2019-2022)</a></li>
      <li><a href="https://uir.ac.id/" target="_blank" rel="noopener">Universitas Islam Riau (2022-Sekarang)</a></li>
    </ul>
  </WelcomeItem>
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>

    <ul>
      <li>Tidur</li>
      <li>Makan tapi ga gendut"</li>
      <li>Mendengarkan Musik</li>
    </ul>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontak Saya</template>
    Telepon : +62 831-8510-0000 <br>
    Email : <a href="https://mail.google.com/mail/u/1/?ogbl#inbox?compose=new
" target="_blank" rel="noopener">tiaraputri9586@gmail.com</a> <br>
    Twitter : <a href="https://twitter.com/jejepasha" target="_blank" rel="noopener">jejepasha</a> <br>
    Intagram : <a href="https://www.instagram.com/1923files?igsh=MWNpYWt1bXp5czMzdA==" target="_blank" rel="noopener">1923files</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Tentang Saya</template>
    <p>Salah seorang pecinta kucing dan tentunya Lee Jeno yang sedang berjuang untuk menyelesaikan pendidikannya sambil Yaa Allah Yaa Allah. Sepasang matanya sering sekali lelah melihat komputer tapi malah memilih jurusan seputar perkomputeran dan pemrograman sebagai pendidikan setelah sekolah menengah atasnya. Mumet rek mataku :((((.</p>
  </WelcomeItem>
</template>
