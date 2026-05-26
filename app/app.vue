<!--
    Copyright (c) 2026 The Aridity Team, all rights reserved.
    Licensed under the BSD 3-Clause License
-->

<script setup lang="ts">
useHead({
  	titleTemplate: (titleChunk) => {
    	return titleChunk ? `${titleChunk} - The Aridity Team website` : 'The Aridity Team website'
  	},
});
</script>

<template>
	<div>
		<NuxtLayout>
			<NuxtPage />
		</NuxtLayout>
	</div>
</template>
