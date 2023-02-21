<script setup lang="ts">
const router = useRouter()
</script>

<template>
  <nav text-xl flex items-center mb-4>
    <a href="/" @click.prevent="router.push('/')">Logo</a>
    <div flex-1 />
    <div flex items-center gap-2>
      <a
        icon-btn i-carbon-logo-github
        rel="noreferrer"
        href="https://github.com/llx-00/vitesse-lite"
        target="_blank"
        title="GitHub"
      />

      <BtnDarkMode />
    </div>
  </nav>
</template>
