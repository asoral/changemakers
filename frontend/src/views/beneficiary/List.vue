<template>
	<ListView
		doctype="Beneficiary"
		:filterConfig="{
			gender: { type: 'link', doctype: 'Gender' },
			state: { type: 'link', doctype: 'State' },
			age: { type: 'number' },
		}"
	/>
</template>

<script setup lang="ts">
import ListView from "@/components/ListView.vue"
</script>
