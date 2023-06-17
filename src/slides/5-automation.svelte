<script lang="ts">
	import { base } from '$app/paths'
	import Slide from '../lib/deck/slide.svelte'
</script>

<Slide>
	<Slide backgroundImage="{base}/assets/automation-index.png">
		<h2><b class="font-bold px-3 bg-cyan-500 text-white">Automation & Integration</b></h2>
	</Slide>

	<Slide>
		<h2>Beispiele</h2>
		<ul>
			<li>Automatisiert verschiedene Varianten einer Grafik erzeugen und veröffentlichen (REST)</li>
			<li>Grafiken automatisch aktualisieren (REST)</li>
			<li>Nach der Veröffentlichung einer Grafik eine Nachricht verschicken (Webhooks)</li>
			<li>Mit der Website interagieren, auf der eine Grafik eingebunden ist (Chart Events)</li>
		</ul>
	</Slide>

	<Slide>
		<h3>Grafiken für Regionen</h3>
		<img src="{base}/assets/automation-zeit-dropdown.png" alt="" />
		<small>
			<a href="https://www.zeit.de/wissen/2022-09/duerre-klimakrise-entwicklung-daten-uebersicht">
				Zeit Online: So stark ist Ihre Region von Dürre betroffen
			</a>
			<br />(eingesendet von Julius Tröger)
		</small>
	</Slide>

	<Slide backgroundIframe="https://www.sueddeutsche.de/projekte/bundestagswahl-2021/kiel" />

	<Slide>
		<h3>Grafiken für Regionen</h3>
		<iframe
			title="Ausbau Solarenergie in Kilchberg"
			aria-label="Datawrapper visualization"
			src="https://datawrapper.dwcdn.net/uGom1/"
			scrolling="no"
			style="width: 0px; min-width: 100%;"
			height="450"
			frameborder="0"
		/>
		<small>
			<a
				href="https://www.tagesanzeiger.ch/so-weit-ist-ihre-gemeinde-beim-solarausbau-171221255553?gemeinde=135"
			>
				Tagesanzeiger: So weit ist Ihre Gemeinde beim Solarausbau
			</a>
			<br />(eingesendet von Timo Grossenbacher)
		</small>
	</Slide>

	<Slide>
		<h3>Charts animieren (API + Video)</h3>
		<video class="mx-auto" autoplay muted playsinline style="height: 450px !important">
			<source
				src="https://interactive.zeit.de/g/videoplayer-pembed/videos/2022/inflation/light.mp4"
				type="video/mp4"
			/>
		</video>
		<small>
			<a href="https://www.zeit.de/wirtschaft/2022-12/inflation-europa-g7-staaten">
				Zeit Online: Hat die Inflation ihren Höhepunkt erreicht?
			</a>
			<br />(eingesendet von Julius Tröger)
		</small>
	</Slide>

	<Slide>
		<h3>Daten aktualisieren über API</h3>
		<iframe
			title="DAX im Tagesverlauf"
			aria-label="Datawrapper visualization"
			src="https://datawrapper.dwcdn.net/xXBfe/"
			scrolling="no"
			style="width: 0px; min-width: 100%;"
			height="412"
			frameborder="0"
		/>
		<small>
			<a href="https://www.tagesanzeiger.ch/">Tagesanzeiger</a>
			(eingesendet von Timo Grossenbacher)
		</small>
	</Slide>

	<Slide backgroundIframe="https://datawrapper.readthedocs.io/" />

	<Slide backgroundIframe="https://munichrocker.github.io/DatawRappr/" />

	<Slide backgroundIframe="https://developer.datawrapper.de/docs/" />

	<Slide>
		<h3>Zugriff auf Datawrapper-APIs</h3>
		<ul>
			<li>
				<a href="https://developer.datawrapper.de/docs/getting-started">
					Datawrapper-APIs (REST, Webhooks, Events, etc.)
				</a>
			</li>
			<li>
				<a href="https://munichrocker.github.io/DatawRappr/">
					DatawrappR (inoffizielle R-Bibliothek)
				</a>
			</li>
			<li>
				<a href="https://datawrapper.readthedocs.io/">
					Datawrapper (inoffizielle Python-Bibliothek)
				</a>
			</li>
		</ul>
	</Slide>
</Slide>
