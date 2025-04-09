<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
	<div class="max-w-[1200px] p-2 w-full">
		<h1 class="text-white text-3xl">{{ msg }}</h1>
		<iframe style="border-radius:12px" src="https://open.spotify.com/embed/album/1r0F1EzzNOaJyB7U0Jp5RH?utm_source=generator" width="100%" height="452" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

		<p class="text-white">
			Что то еще добавлю позже
		</p>
	</div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
