<script lang="ts">
	export let id: string | null = null
	export let animate = false
	export let restart = false
	export let backgroundColor: string | null = null
	export let backgroundImage: string | null = null
	export let backgroundVideo: string | null = null
	export let backgroundIframe: string | null = null
	export let backgroundSize: string | null = null
	export let backgroundInteractive = false
</script>

<section
	data-auto-animate-id={id}
	data-auto-animate={animate || null}
	data-auto-animate-restart={restart || null}
	data-background-color={backgroundColor}
	data-background-image={backgroundImage || null}
	data-background-video={backgroundVideo || null}
	data-background-iframe={backgroundIframe}
	data-background-size={backgroundSize}
	data-background-interactive={backgroundInteractive || null}
>
	<slot />
</section>
