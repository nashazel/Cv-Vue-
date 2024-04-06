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
    <template #heading>Biography</template>

    was born at 26th june 2005, and the only child. Usually called with 
    <a href="https://vuejs.org/" target="_blank" rel="noopener">Nasha.</a>
    An Informatics Engineering student at Riau Islamic Univesity.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Interest</template>

    Like to play game, such a FPS game.
    <a href="https://vitejs.dev/guide/features.html" target="_blank" rel="noopener"></a>The
    game that i play is
    <a href="https://code.visualstudio.com/" target="_blank" rel="noopener">Valorant</a> &
    <a href="https://github.com/johnsoncodehk/volar" target="_blank" rel="noopener">Fortnite</a>. I
    sometimes do stream of my gameplay. Other, i like listening to music to. Don't
    have any spesific genre, just like songs that sounds good on my ear.
    <a
      ></a
    >

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Skill</template>

    I can say im fluent in
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">English</a>,
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener">Indonesia</a>, and
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener">Malay</a>. I can operate 
    MySQL, html and good at 
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener">UI</a>
    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">UX</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Media Social</template>

    Here's my media social:
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Instagram</a>@nashazell,
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"
      >Tiktok</a
    > @user6463659,
    <a href="https://news.vuejs.org" target="_blank" rel="noopener">Spotify</a> @ash.
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Me</template>

    As an independent worker, Me relies on community backing for its sustainability. You can help
    me by
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">becoming a sponsor</a>.
  </WelcomeItem>
</template>
