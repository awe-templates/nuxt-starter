<template>
	<div>
		<h1 class="text-2xl text-green-600 underline">Home</h1>
		<p>My name is {{ name }}</p>
	</div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const name = ref('John Doe');
</script>
