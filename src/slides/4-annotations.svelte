<script lang="ts">
	import Slide from '../lib/deck/slide.svelte'
	import Code from '../lib/deck/code.svelte'
</script>

<Slide>
	<Slide backgroundVideo="/assets/annotations-index.mp4" backgroundSize="contain" animate>
		<h2 class="fragment fade-out">
			<b class="font-bold px-3 bg-cyan-500 text-white">Annotations & HTML</b>
		</h2>
	</Slide>

	<Slide animate>
		<h3>HTML & CSS in Datawrapper</h3>
		<iframe
			title="Title 💖 HTML"
			aria-label="Interactive area chart"
			id="datawrapper-chart-7XVg1"
			src="https://datawrapper.dwcdn.net/7XVg1/1/"
			scrolling="no"
			frameborder="0"
			style="border: none;"
			width="600"
			height="400"
			class="mx-auto"
			data-external="1"
		/>

		<small>
			<a href="https://academy.datawrapper.de/article/304-how-to-use-html-css-in-datawrapper">
				Dokumentation: HTML und CSS in Datawrapper
			</a>
		</small>
	</Slide>

	<Slide backgroundColor="black" animate>
		<h3>HTML & CSS in Datawrapper</h3>
		<h3>
			<Code id="code">
				{`
                Annotations 💖 <b style="color:hotpink">HTML</b>
            `}
			</Code>
		</h3>
		<small>
			<a href="https://academy.datawrapper.de/article/304-how-to-use-html-css-in-datawrapper">
				Dokumentation: HTML und CSS in Datawrapper
			</a>
		</small>
	</Slide>

	<Slide animate>
		<h3>Eigene Farblegende mit HTML&nbsp;und&nbsp;CSS</h3>

		<iframe
			title="National responsibility for ecological overshoot"
			aria-label="Interactive area chart"
			id="datawrapper-chart-U0ckT"
			class="mx-auto"
			data-src="https://datawrapper.dwcdn.net/U0ckT/10/"
			scrolling="no"
			height="800"
			width="680"
			frameborder="0"
		/>
	</Slide>

	<Slide animate>
		<h3>Eigene Farblegende mit HTML&nbsp;und&nbsp;CSS</h3>

		<img
			src="//d33v4339jhl8k0.cloudfront.net/docs/assets/588089eddd8c8e484b24e90a/images/5ca738920428633d2cf480aa/file-eHw0tm9z9I.gif"
		/>

		<small>
			<a href="https://academy.datawrapper.de/article/190-how-to-turn-your-title-into-a-color-key">
				Dokumentation: Titel als Farblegende
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Tab-Navigation zwischen Charts</h3>

		<iframe
			title="Anteil der positiv auf das Coronavirus getesteten Engländer"
			aria-label="Interactive area chart"
			id="datawrapper-chart-U0ckT"
			class="mx-auto"
			data-src="https://datawrapper.dwcdn.net/Zwucc/6/"
			scrolling="no"
			height="500"
			width="600"
			frameborder="0"
		/>
		<small>
			<a href="https://www.sueddeutsche.de/"> Süddeutsche Zeitung </a>
			(eingesendet von Sören Müller-Hansen)
		</small>
	</Slide>

	<Slide backgroundColor="black" animate>
		<h3>Tab-Navigation zwischen Charts</h3>
		<h3>
			<Code id="code">
				{`
                <a target="_self" href="https://datawrapper.dwcdn.net/RxU9O/" [...]> 
            `}
			</Code>
		</h3>
		<small>
			<a href="https://academy.datawrapper.de/article/305-how-to-add-tabs-and-drop-downs">
				Dokumentation: Tabs und Dropdowns mit HTML
			</a>
		</small>
	</Slide>

	<Slide animate>
		<h3>Tab-Navigation zwischen Charts</h3>
		<img src="/assets/taz-tab-links.jpg" alt="" style="margin: 0 auto; height: 400px !important" />
		<small> Taz: Internes Tool für Tab-Navigation (eingesendet von Lalon Sander) </small>
	</Slide>

	<Slide animate>
		<h3>Bilder einfügen</h3>

		<iframe
			title="Daten zum Klimawandel"
			src="https://datawrapper.dwcdn.net/JNH5Z/"
			scrolling="no"
			height="450"
			width="600"
			frameborder="0"
			class="mx-auto"
		/>
		<small>
			<a
				href="https://www.zdf.de/nachrichten/politik/klimawandel-deutschland-welt-folgen-daten-100.html"
			>
				ZDF: Daten zum Klimawandel
			</a>
			(Moritz Zajonz, Michael Hörz)
		</small>
	</Slide>

	<Slide backgroundColor="black" animate>
		<h3>🖼 BASE64!</h3>
		<Code id="code">
			{`<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYA
              AACqaXHeAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAC4jAAAuIwF4pT92AAAAB3RJ
              TUUH4wwQCRM6Yd/avQAAABl0RVh0Q29tbWVudABDcmVhdGVkIHdpdGggR0lNUFeBDhcA
              AATMSURBVHja7VptbFNVGH7ec/vB2MC5TTACi1s73LK2WwSN6ExbZ3ARE2KIJGYx8StB
              JUZ/QExkfpAlmpjwD2L8wTT8MMoSBTV8ZLK2MPHHHLh1MGDt1IgYXZC4bLBu7Xn9sYYQ
              17Oxft6u9/n7nvPe9zz3/Tz3AgYMGDBgwEDBgjL9AAboRG1tGVGkBBZz9A7T+LX1fVeu
              L1oCGKCAa20Ty9gWInoUQB2Aov+t+hOgXgZ3WQgHHxkI/70oCPC7ap4F8zvxQ98upplw
              AMD73oHQ5bwkIOCwrWGiAwA8KaiZIOAtdzC0L68I8DVUN5EUhwCUp8mmzyuk9QXHuXNT
              uieg21XdLFh8OzvGU8axCmndnA0SRLIbTzqqXILF1xk4PAC0jIpIRzY8ICkCjrtcxZK0
              TgDL5lgWAfgzYtrCmqnKUjK5dNoiSxmijpleJSAwj2u2Bpz27boMAb/D9hGIds6h9HA0
              GnujeeiX3+bMHy5bCzHtB3CPKjEyoTaT1WHBBJxoWLtKk3IEgEXRCbS7g+H3COAF6DsK
              wKlY0uEJhl7STQhoLLerDs/APk8w/O7tHh4Amvsv/UHMmwComqHnvndUrdRPDmC0KiTn
              Ub76zWSMcA+Gf2fwNoXYbILYqgsCAo6aOgCViXnhXV6/P5qsId5g+BBAvYmtpI368AAh
              H1RIrqF8zXdpmCS+UHjdA/oggGFX5FJ/Km//pnpJ3QrRSl99fUnOCWAmVbubnjK1hJR6
              zLhRpockaE7sADyeDmPumjSPqWQxzazl3gMIVxWhUZEOY0a1yAqVzHo9djXnBBDwl4Ka
              2vRcpsj7FKKph0KhMR0QIC8qJBtOOSvvTNkYFpsUDz6viypQbJn0zww5s2CKwprS4BIn
              8HmFa/h0QUD8MvNk4pfEO3vqqyuTNUSS+QMACb1IChzXTStMhL0K0fKoJg4nU68Dzppt
              zPSKQnzJ2x/q0g0B7oHQNwDOKFy1kbTIqYV4gs9Z08bgj9V5h/cQIPV1IyR5B1RGMRqj
              QgwEXLZdvsZ7SxVTIwVctsf8TvtpArerxnIC+ootpZ/q7kJkxm1t7Qxq..." alt="" />
            `}
		</Code>
	</Slide>

	<Slide animate>
		<h3>Bilder einfügen</h3>
		<img
			src="/assets/ntv-image-embed.png"
			alt=""
			style="margin: 0 auto; height: 400px !important"
		/>
		<small>
			<a
				href="https://www.n-tv.de/mediathek/videos/panorama/Animation-zeigt-Deutschlands-Weg-durch-die-Pandemie-article22988820.html"
			>
				Animation zeigt Deutschlands Weg durch die Pandemie
			</a>
			(Charistoph Wolf, Laura Stresing)
		</small>
	</Slide>

	<Slide animate>
		<h3>HTML-Charts einfügen</h3>
		<small class="my-2">
			<a
				href="https://www.hessenschau.de/politik/ergebnisse-des-frankfurter-buergerentscheids-zu-ob-feldmann---infografik-v11,feldmann-referendum-ergebnis-live-100.html"
			>
				Hessenschau: "Feldmann-O-Meter"
			</a>
			(eingesendet von Jan Eggers)
		</small>
		<iframe
			title="Feldmann-O-Meter"
			scrolling="no"
			src="https://datawrapper.dwcdn.net/bIm87/"
			width="700"
			height="700"
			class="mx-auto"
			frameborder="0"
		/>
	</Slide>

	<Slide animate>
		<h3>HTML-Charts einfügen</h3>
		<small class="my-2">
			<a href="https://www.datawrapper.de/_/ovDnV/"> Kompakte Bar-Charts in Tooltips </a>
			(eingesendet von Michael Hörz)
		</small>
		<iframe
			title="Gemeindewahlen im Kreis Stormarn: Die Gewinner"
			aria-label="Datawrapper visualization"
			src="https://datawrapper.dwcdn.net/ovDnV/"
			scrolling="no"
			class="mx-auto"
			width="600"
			height="600"
			frameborder="0"
		/>
		<small>
			<a
				href="https://www.n-tv.de/mediathek/videos/panorama/Animation-zeigt-Deutschlands-Weg-durch-die-Pandemie-article22988820.html"
			>
				Animation zeigt Deutschlands Weg durch die Pandemie
			</a>
			(Christoph Wolf, Laura Stresing)
		</small>
	</Slide>

	<Slide>
		<h3>HTML und CSS mit Datawrapper</h3>
		<ul>
			<li>
				<a href="https://academy.datawrapper.de/article/304-how-to-use-html-css-in-datawrapper">
					Dokumentation: HTML und CSS mit Datawrapper
				</a>
			</li>
			<li>
				<a href="https://academy.datawrapper.de/article/305-how-to-add-tabs-and-drop-downs">
					Dokumentation: Tabs und Dropdowns
				</a>
			</li>
			<li>
				<a href="https://academy.datawrapper.de/article/282-how-to-embed-charts-into-tooltips">
					Dokumentation: HTML-Charts in Tooltips
				</a>
			</li>
			<li>
				<a href="https://academy.datawrapper.de/article/248-how-to-insert-images">
					Dokumentation: Bilder einfügen (fast überall!)
				</a>
			</li>
		</ul>
	</Slide>
</Slide>
