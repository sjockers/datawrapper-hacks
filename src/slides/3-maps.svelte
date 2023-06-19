<script lang="ts">
	import { base } from '$app/paths'
	import Slide from '../lib/deck/slide.svelte'
</script>

<Slide>
	<Slide backgroundIframe="https://app.datawrapper.de/select/map">
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">Karten</b>
		</h2>
	</Slide>

	<Slide backgroundColor="#FAB17C">
		<h3>3000 Karten!</h3>
		<img
			src="{base}/assets/maps-index.gif"
			alt=""
			style="margin: 0 auto; width: 500px !important"
		/>
	</Slide>

	<Slide>
		<h3>Kartogramm [Choroplethen&#8209;Karte]</h3>
		<iframe
			id="datawrapper-chart-MJsiM"
			title="Cartogram"
			class="mx-auto"
			data-src="//datawrapper.dwcdn.net/MJsiM/9/"
			scrolling="no"
			height="450"
			width="480"
			frameborder="0"
		/>
		<small>
			<a href="https://blog.datawrapper.de/cartograms/">Blog Post: Cartograms in Datawrapper </a>
			(Lisa C. Muth)
		</small>
	</Slide>

	<Slide>
		<h3>Eigene Choroplethen-Karten</h3>
		<iframe
			title="Choropleth Map"
			aria-label="Map"
			id="datawrapper-chart-rnaey"
			class="mx-auto"
			data-src="https://datawrapper.dwcdn.net/rnaey/1/"
			scrolling="no"
			data-external="1"
			height="450"
			width="340"
			frameborder="0"
		/>
		<small>
			<a href="https://blog.datawrapper.de/central-park-squirrel-map/">
				Blog Post: The 2018 Central Park Squirrel Census
			</a>
			(Rose Minzer-Sweeney)
		</small>
	</Slide>

	<Slide>
		<img
			src="{base}/assets/maps-choropleth-mannheim.png"
			alt=""
			style="margin: 0 auto; width: 500px !important"
		/>
		<small>
			<a
				href="https://www.mannheimer-morgen.de/politik/wahlen_artikel,-wahlen-landtagswahl-gruene-gewinnen-beide-mannheimer-wahlkreise-_arid,1769351.html"
			>
				Mannheimer Morgen: Landtagswahl Baden Württemberg
			</a>
			(Daniel Kraft)
		</small>
	</Slide>

	<Slide>
		<h3>Locator Maps</h3>
		<iframe
			class="mx-auto"
			title="Locator Maps"
			scrolling="no"
			src="https://datawrapper.dwcdn.net/8gJ2C"
			height="450"
			width="600"
		/>
		<small>
			<a
				href="https://www.spiegel.de/auto/49-euro-ticket-wer-vom-deutschlandticket-wirklich-profitiert-a-f3645761-be73-45ab-9adb-0bf937917db5"
			>
				Der Spiegel: Wer vom Deutschlandticket wirklich profitiert
			</a>
			(eingesendet von Patrick Stotz)
		</small>
	</Slide>

	<Slide>
		<iframe
			title="Restaurant-Tipps zur Buga in Mannheim"
			class="mx-auto"
			aria-label="Locator-Karte"
			id="datawrapper-chart-Xk3x2"
			src="https://datawrapper.dwcdn.net/Xk3x2/1/"
			scrolling="no"
			height="500"
			width="500"
			frameborder="0"
		/>
		<small>
			<a
				href="https://www.mannheimer-morgen.de/leben/geniessen_artikel,-gastro-die-besten-restaurants-fuer-ihren-buga-23-besuch-in-mannheim-_arid,2044205.html"
			>
				Mannheimer Morgen: Restaurant-Tipps zur Buga in Mannheim
			</a>
			<br />(eingesendet von Daniel Kraft)
		</small>
	</Slide>

	<Slide backgroundImage="{base}/assets/geojson.png" backgroundSize="contain">
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">geojson.io</b>
		</h2>
	</Slide>

	<Slide backgroundIframe="https://mapshaper.org">
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">Map Shaper</b>
		</h2>
	</Slide>

	<Slide backgroundIframe="https://pitchinteractiveinc.github.io/tilegrams/">
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">Tilegrams</b>
		</h2>
	</Slide>

	<Slide backgroundIframe="https://go-cart.io/cartogram">
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">Go-Cart</b>
		</h2>
	</Slide>
</Slide>
