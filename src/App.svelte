<script>
	import LoginCard from './LoginCard.svelte' 
</script>

<main class="flex items-center justify-center bg-gray-100 h-screen">
	<div class="w-1/3">
		<img class="w-80" src="/images/fb.svg" alt="Facebook Logo" />
		<p class="mx-8 font-sans text-2xl">Facebook helps you connect and share with the people in your life.</p>
	</div>
	<div class="w-1/4 m-6 flex flex-col">
		<LoginCard />
		<div class="text-sm mt-6 self-center"><span class="font-bold hover:underline cursor-pointer">Create a Page</span> for a celebrity, brand or business.</div>
	</div>
</main>
