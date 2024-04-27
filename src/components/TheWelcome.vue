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
    <template #heading>PENGALAMAN KERJA</template>

    Project Manager PT BUMI SIAK PUSAKO
    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>SKILL</template>

    Public Speking , Problem Salving
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener"></a> 
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener"></a>
    <a href="https://www.cypress.io/" target="_blank" rel="noopener"></a>
    <a href="https://on.cypress.io/component" target="_blank" rel="noopener"></a>

    <br />

  <code></code>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>PENDIDIKAN</template>
    SDN 10 Sungai Apit ,
    SMPN 1 Sungai Apit ,
    SMAN 1 Sungai Apit .
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>HOBI</template>

    Baca buku , Menyanyi
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      ></a
    >
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a> 
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>KONTAK</template>

    Email : mirandadwiwahyuni01@gmail.com Telepon : 082169835281
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>.
  </WelcomeItem>
</template>
