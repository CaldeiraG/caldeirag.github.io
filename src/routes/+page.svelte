<script>
	import { Avatar, AvatarFallback, AvatarImage } from '$lib/components/ui/avatar/index.ts';
	import SocialButtons from '$lib/components/SocialButtons.svelte';
</script>

<div>
	<div class="flex md:flex-grow flex-grow justify-center items-center">
		<Avatar class="w-60 h-60">
			<AvatarImage src="profile.png" alt="CaldeiraG avatar" />
			<AvatarFallback>CG</AvatarFallback>
		</Avatar>
	</div>
	<div class="flex md:flex-grow flex-grow justify-center items-center pt-2">
		<p class="font-bold text-4xl">CaldeiraG</p>
	</div>
	<div class="flex md:flex-grow flex-grow justify-center items-center pt-2">
		<p class="font-normal text-xl">Lorem Ipsum</p>
	</div>
	<SocialButtons/>
</div>