<script>
	import { Github, Instagram, Mail, Twitch, Twitter } from 'lucide-svelte';

	import GitHub from '$lib/components/GitHub.svelte';

</script>

<div class="container mx-auto pt-2">
	<div class="flex flex-auto gap-4 justify-center items-center pt-2">
		<!--      <Button variant="default" class="bg-custom text-lg">-->
		<a href="mailto:cal@caldeirag.xyz"><Mail class="w-6 h-6 mr-2" /> </a>
		<!--      </Button>-->
		<!--      <Button variant="default" class="bg-custom text-lg">-->
		<a href="https://github.com/CaldeiraG"><GitHub/></a>
		<!--      </Button>-->
		<!--      <Button variant="default" class="bg-custom text-lg">-->
		<a href="https://instagram.com/caldeirag.xyz"><Instagram/></a>
		<!--      </Button>-->
		<!--      <Button variant="default" class="bg-custom text-lg">-->
		<a href="https://twitter.com/CaldeiraG"><Twitter/></a>
		<!--      </Button>-->
		<!--      <Button variant="default" class="bg-custom text-lg">-->
		<a href="https://twitch.tv/CaldeiraG"><Twitch/> </a>
		<!--      </Button>-->
	</div>
</div>

<style>
    .lucide {
        /* Change this! */
        width: 24px;
        height: 24px;
        stroke-width: 1px;
    }

		svg {
        width: 24px;
				height: 24px;
		}

</style>