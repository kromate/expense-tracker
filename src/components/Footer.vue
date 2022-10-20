<template>
	<footer class="h-14 fixed bottom-0 inset-x-0 grid grid-cols-3 items-center justify-center border-t border-primary shadow">
		<nuxt-link to="/" class="w-full flex items-center justify-center h-full">
			<i class="las la-signal text-4xl" />
		</nuxt-link>
		<nuxt-link to="/add" class="w-full flex items-center justify-center h-full">
			<i class="las la-plus text-4xl" />
		</nuxt-link>
		<nuxt-link to="/settings" class="w-full flex items-center justify-center h-full">
			<i class="las la-user text-4xl" />
		</nuxt-link>
	</footer>
</template>

<script setup lang="ts">

</script>

<style scoped>
.router-link-active.router-link-exact-active{
   background: linear-gradient(180deg, #549994 0%, #408782 100%);
   /* background-image: linear-gradient( rgba(90,92,106,1) 0%, rgba(32,45,58,1) 81.3% ); */
}
.router-link-active.router-link-exact-active > i{
    @apply text-white
}
</style>
