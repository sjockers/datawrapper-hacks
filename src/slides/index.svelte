<script lang="ts">
	import { onMount } from 'svelte'

	import Reveal from 'reveal.js'
	import Highlight from 'reveal.js/plugin/highlight/highlight'
	import Markdown from 'reveal.js/plugin/markdown/markdown'
	import Notes from 'reveal.js/plugin/notes/notes'
	import Slide from '../lib/deck/slide.svelte'

	import 'reveal.js/dist/reveal.css'
	import 'reveal.js/dist/theme/white.css'
	import 'reveal.js/plugin/highlight/monokai.css'

	import IntroSlides from './0-intro.svelte'
	import ChartSlides from './1-charts.svelte'
	import TableSlides from './2-tables.svelte'
	import MapSlides from './3-maps.svelte'
	import AnnotationSlides from './4-annotations.svelte'
	import AutomationSlides from './5-automation.svelte'

	onMount(() => {
		const deck = new Reveal({
			plugins: [Markdown, Highlight, Notes],
			autoAnimateEasing: 'ease',
			autoAnimateDuration: 1,
			hash: true
		})

		deck.initialize()
	})
</script>

<div class="reveal">
	<div class="slides">
		<IntroSlides />
		<ChartSlides />
		<TableSlides />
		<MapSlides />
		<AnnotationSlides />
		<AutomationSlides />
	</div>
</div>
