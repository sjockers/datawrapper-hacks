<script lang="ts">
	import Slide from '../lib/deck/slide.svelte'
</script>

<Slide>
	<Slide animate>
		<h2><b class="font-bold px-3 bg-cyan-500 text-white">Chart-Hacks</b></h2>
		<p>Material für Datawrapper-Hacks:</p>
		<ul>
			<li>Line Charts</li>
			<li>Scatter Plots</li>
			<li>Tables</li>
		</ul>
	</Slide>

	<Slide>
		<h3><b class="font-bold px-3 bg-cyan-500 text-white">Line Charts</b></h3>
		<iframe
			title="Line chart"
			aria-label="Line chart"
			id="datawrapper-chart-4Nma0"
			class=" lazyloaded"
			data-src="https://datawrapper.dwcdn.net/4Nma0"
			style="border: none; width: 100%; height:480px;"
		/>
		<small>
			<a href="https://academy.datawrapper.de/category/76-line-area-charts">
				Dokumentation: Line & Area Charts
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Slope Chart [Line Chart]</h3>

		<iframe
			title="Population of animals on a fictional farm"
			aria-label="Interactive line chart"
			id="datawrapper-chart-SnXhD"
			src="https://datawrapper.dwcdn.net/SnXhD/2/"
			scrolling="no"
			height="480"
			width="480"
			frameborder="0"
			class="mx-auto"
		/>
		<small>
			<a href="https://academy.datawrapper.de/article/152-how-to-create-a-slope-chart">
				Dokumentation: Slope Charts
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Slope Chart [Line Chart]</h3>
		<small>
			<table>
				<tbody>
					<tr>
						<td> <strong> Year </strong> </td>
						<td style="text-align: right;"> <strong> Cat </strong> </td>
						<td style="text-align: right;"> <strong> Dogs </strong> </td>
						<td style="text-align: right;"> <strong> Horses </strong> </td>
						<td style="text-align: right;"> <strong> Mice </strong> </td>
						<td style="text-align: right;"> <strong> Cows </strong> </td>
						<td style="text-align: right;"> <strong> Pigs </strong> </td>
						<td style="text-align: right;"> <strong> Sheep </strong> </td>
						<td style="text-align: right;"> <strong> Goats</strong> </td>
					</tr>
					<tr>
						<td> <strong> 2005</strong> </td>
						<td style="text-align: right;"> 50 </td>
						<td style="text-align: right;"> 40 </td>
						<td style="text-align: right;"> 30 </td>
						<td style="text-align: right;"> 34 </td>
						<td style="text-align: right;"> 45 </td>
						<td style="text-align: right;"> 39 </td>
						<td style="text-align: right;"> 25 </td>
						<td style="text-align: right;"> 41 </td>
					</tr>
					<tr>
						<td> <strong> 2015</strong> </td>
						<td style="text-align: right;"> 34 </td>
						<td style="text-align: right;"> 31 </td>
						<td style="text-align: right;"> 39 </td>
						<td style="text-align: right;"> 44 </td>
						<td style="text-align: right;"> 47 </td>
						<td style="text-align: right;"> 50 </td>
						<td style="text-align: right;"> 40 </td>
						<td style="text-align: right;"> 46 </td>
					</tr>
				</tbody>
			</table>
		</small>

		<small>
			<a href="https://academy.datawrapper.de/article/152-how-to-create-a-slope-chart">
				Dokumentation: Slope Charts
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Konfidenzintervall [Line Chart]</h3>
		<iframe
			title="Global land temperature in July, 1753-2015"
			aria-label="Interactive line chart"
			id="datawrapper-chart-BsBaq"
			src="//datawrapper.dwcdn.net/2Ydl1/1/"
			scrolling="no"
			style="width: 0px; min-width: 100% !important;"
			height="480"
			frameborder="0"
		/>
		<small>
			<a
				href="https://academy.datawrapper.de/article/205-how-to-show-confidence-intervals-in-datawrapper-line-charts"
			>
				Dokumentation: Konfidenzintervall
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Konfidenzintervall [Line Chart]</h3>
		<small>
			<table>
				<tbody>
					<tr>
						<td> <strong>years</strong> </td>
						<td> <strong>temperature</strong> </td>
						<td> <strong>lower</strong> </td>
						<td> <strong>upper</strong> </td>
					</tr>
					<tr>
						<td> 1753 </td>
						<td> 15.092 </td>
						<td> 13.163 </td>
						<td> 17.021 </td>
					</tr>
					<tr>
						<td> 1754 </td>
						<td> 14.681 </td>
						<td> 12.28 </td>
						<td> 17.082 </td>
					</tr>
					<tr>
						<td> ... </td>
						<td> ... </td>
						<td> ... </td>
						<td> ... </td>
					</tr>
					<tr>
						<td> 2014 </td>
						<td> 14.873 </td>
						<td> 14.795 </td>
						<td> 14.951 </td>
					</tr>
					<tr>
						<td> 2015 </td>
						<td> 15.051 </td>
						<td> 14.965 </td>
						<td> 15.137 </td>
					</tr>
				</tbody>
			</table>
		</small>

		<img
			src="//d33v4339jhl8k0.cloudfront.net/docs/assets/588089eddd8c8e484b24e90a/images/5d8cbe1f2c7d3a7e9ae1a954/file-NBMerBximW.gif"
			alt=""
		/>

		<small>
			<a
				href="https://academy.datawrapper.de/article/205-how-to-show-confidence-intervals-in-datawrapper-line-charts"
			>
				Dokumentation: Konfidenzintervall
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Stepped Area Chart [Line Chart]</h3>
		<iframe
			title="SPD polls and election results compared"
			aria-label="Interactive line chart"
			id="datawrapper-chart-YR6tA"
			class=" lazyloaded"
			data-src="https://datawrapper.dwcdn.net/YR6tA/1/"
			scrolling="no"
			style="width: 0px; min-width: 100% !important;"
			height="450"
			frameborder="0"
		/>
		<small>
			<a href="https://blog.datawrapper.de/german-party-polls-vs-election-results/">
				Blog-Post: Party polls vs. election results
			</a>
			(Lisa C. Muth)
		</small>
	</Slide>

	<Slide>
		<h3>Techniken für Line Charts</h3>
		<ul>
			<li>
				<a href="https://academy.datawrapper.de/category/76-line-area-charts">
					Dokumentation: Line & Area Charts
				</a>
			</li>
			<li>
				<a href="https://academy.datawrapper.de/article/152-how-to-create-a-slope-chart">
					Dokumentation: Slope charts
				</a>
			</li>
			<li>
				<a
					href="https://academy.datawrapper.de/article/205-how-to-show-confidence-intervals-in-datawrapper-line-charts"
				>
					Dokumentation: Konfidenzintervall
				</a>
			</li>
		</ul>
	</Slide>

	<Slide>
		<h3><b class="font-bold px-3 bg-cyan-500 text-white">Scatter Plots</b></h3>
		<iframe
			title="Gross national income and CO2 emissions per capita"
			aria-label="Scatterplot"
			id="datawrapper-chart-CHzu8"
			class=" lazyloaded"
			data-src="//datawrapper.dwcdn.net/CHzu8/8/"
			scrolling="no"
			style="width: 0px; min-width: 100% !important; border: medium none; height: 501px;"
			height="480"
			frameborder="0"
		/>
		<small>
			<a href="https://academy.datawrapper.de/category/79-scatterplots">
				Dokumentation: Scatter Plots
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Lexis Diagram [Scatter Plot]</h3>
		<iframe
			title="How long European leaders have stayed in office"
			aria-label="Scatter Plot"
			id="datawrapper-chart-lT8J8"
			data-src="https://datawrapper.dwcdn.net/lT8J8/3/"
			scrolling="no"
			style="width: 0px; min-width: 100% !important;"
			height="480"
			frameborder="0"
		/>

		<small>
			<a href="https://blog.datawrapper.de/longest-terms-european-leaders/">
				Blog-Post: Three decades of European government leaders
			</a>
			(Gregor Aisch)
			<br />
			<a
				href="https://academy.datawrapper.de/article/260-how-to-connect-scatterplot-dots-with-lines"
			>
				Dokumentation: Punkte verbinden in Scatter Plots
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Timeline [Scatter Plot]</h3>
		<iframe
			title="Key dates: 2020 US Presidential election calendar"
			aria-label="chart"
			id="datawrapper-chart-0YLVf"
			class="mx-auto"
			src="https://datawrapper.dwcdn.net/0YLVf/1/"
			scrolling="no"
			height="1000"
			width="600"
			frameborder="0"
		/>

		<small>
			<a
				href="https://academy.datawrapper.de/article/292-how-to-create-a-timeline-using-scatter-plots"
			>
				Dokumentation: Timelines als Scatter Plots
			</a>
		</small>
	</Slide>

	<Slide>
		<h3>Beeswarm Plot [Scatter Plot]</h3>
		<iframe
			title="Inflation Lebensmittelpreise"
			aria-label="Datawrapper visualization"
			class="mx-auto"
			src="https://datawrapper.dwcdn.net/vx1wk/"
			scrolling="no"
			style="width: 0px; min-width: 100%;"
			height="450"
			frameborder="0"
		/>

		<small>
			<a href="https://www.datawrapper.de/_/vx1wk/">NTV: Lebensmittepreise und Inflation </a>
			(eingesendet von Laura Stresing)
		</small>
	</Slide>

	<Slide>
		<h3>Techniken für Scatter Plots</h3>
		<ul>
			<li>
				<a href="https://academy.datawrapper.de/category/79-scatterplots">
					Dokumentation: Scatter Plots
				</a>
			</li>
			<li>
				<a
					href="https://academy.datawrapper.de/article/260-how-to-connect-scatterplot-dots-with-lines"
				>
					Dokumentation: Punkte verbinden in Scatter Plots
				</a>
			</li>
			<li>
				<a
					href="https://academy.datawrapper.de/article/292-how-to-create-a-timeline-using-scatter-plots"
				>
					Dokumentation: Timelines als Scatter Plots
				</a>
			</li>
		</ul>
	</Slide>
</Slide>
