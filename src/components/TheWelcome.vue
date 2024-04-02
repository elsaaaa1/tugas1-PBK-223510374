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
    <template #heading>pendidikan</template>

    TK Dharma Wanita, SDN 005 Bagan Laguh, SMP N 2 BUNUT, SMA N 1 BUNUT 
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tempat tanggal lahir</template>

    

    BAGAN LAGUH, 28 SEPTEMBER 2004 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Alamat</template>

    Pangkalan Kuras Pelalawan
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Prestasi</template>

  pernah menjadi ketua OSIS di smp dan wakil ketua OSIS di SMA
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Pengalaman </template>

menjadi panitia KPPS dan panitia di berbagai acara waktu sekolah
  </WelcomeItem>
</template>
