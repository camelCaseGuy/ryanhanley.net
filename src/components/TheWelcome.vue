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
    <template #heading>Admin Dashboard</template>
    Building a dashboard for this site.
    <a href="https://github.com/camelCaseGuy/adminDashboard" target="_blank" rel="noopener">dashboard</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>To Do List</template>

    <a href="https://github.com/camelCaseGuy/todoList" target="_blank" rel="noopener">todoList</a>

    <br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Linked Lists</template>
    <a href="https://github.com/camelCaseGuy/linkedLists" target="_blank" rel="noopener">
      linkedLists</a>

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>My Discord Server</template>

    Want to chat? You can reach me here:
    <a href="https://discord.gg/93hGCjBE" target="_blank" rel="noopener">discord</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Data Structures Projects</template>

    <a href="https://github.com/camelCaseGuy/recursion" target="_blank">
      Here are some of my graduate degree projects.</a>
  </WelcomeItem>
</template>
