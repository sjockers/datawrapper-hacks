<script lang="ts">
	import Slide from '../lib/deck/slide.svelte'
	import { base } from '$app/paths'
</script>

<Slide>
	<Slide>
		<h3>
			<span class="font-bold normal-case"> Die besten </span>
			<b class="font-bold normal-case px-3 bg-cyan-500 text-white"> Datawrapper-Hacks </b>
			<span class="font-bold normal-case block">
				für Datenprofis (und alle, die es werden wollen) 📈🔥
			</span>
		</h3>
	</Slide>

	<Slide backgroundIframe="https://www.datawrapper.de/charts" backgroundInteractive />

	<Slide animate>
		<div class="flex">
			<div class="w-1/2">
				<h3>💖 MySpace</h3>
				<ul>
					<li class="fragment">Einfach zu bedienen</li>
					<li class="fragment">Alle benutzen es</li>
					<li class="fragment">
						<b class="inline-block px-2 mt-2 bg-cyan-500 text-white">Hackable!</b>
					</li>
				</ul>
			</div>
			<div class="w-1/2 pl-5">
				<img src="{base}/assets/myspace.gif" alt="Hit me up on MySpace!" />
			</div>
		</div>
	</Slide>

	<Slide animate>
		<div class="flex">
			<div class="w-1/2">
				<h3>📈 Datawrapper</h3>
				<ul>
					<li>Einfach zu bedienen</li>
					<li>Alle benutzen es</li>
					<li>
						<b class="inline-block px-2 mt-2 bg-cyan-500 text-white">Hackable! </b>
					</li>
				</ul>
			</div>
			<div class="w-1/2">
				<iframe
					title="Datawrapper example chart"
					aria-label="Line chart"
					src="https://datawrapper.dwcdn.net/4Nma0"
					style="border: none; width: 100%; height:350px;"
				/>
			</div>
		</div>
	</Slide>

	<Slide>
		<h3>Agenda</h3>
		<ol>
			<li>Spaß mit Diagrammen, Tabellen und Karten</li>
			<li>Spaß mit HTML & Annotations</li>
			<li>Spaß mit Automatisierung & APIs</li>
			<li>
				Eure Grafiken und Hacks:
				<b class="inline-block px-2 mt-2 bg-cyan-500 text-white">notes.datawrapper.de/p/hacks</b>
			</li>
		</ol>
	</Slide>

	<Slide backgroundIframe="https://notes.datawrapper.de/p/hacks" backgroundInteractive={true}>
		<b class="inline-block px-2 mt-2 bg-cyan-500 text-white">notes.datawrapper.de/p/hacks</b>
	</Slide>
</Slide>
