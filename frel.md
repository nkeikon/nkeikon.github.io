<h3>FAQ</h3>
<p>Frequently Asked Questions about our <a href="https://iopscience.iop.org/article/10.1088/1748-9326/aafc6b">paper</a> and <a href="https://redd.unfccc.int/fact-sheets/forest-reference-emission-levels.html">FREL/FRL</a></p>
<p>&nbsp;</p>
<p><strong>Question 1</strong>: What is FREL/FRL? What does it have to do with REDD+?</p>
<p><strong>Answer</strong>: In order to <span style="text-decoration: underline;">reduce</span> emissions from forests, you need to know the level of emissions you are reducing from. This benchmark emissions are Forest Reference Emission Levels (FREL) or Forest Reference Levels (FRL).&nbsp;</p>
<p><img style="display: block; margin-left: auto; margin-right: auto;" src="https://www.geos.ed.ac.uk/homes/s1683747/frel.gif" alt="" width="414" height="258" /></p>
<p>&nbsp;</p>
<p><strong>Question 2</strong>: What is the difference between FREL and FRL?&nbsp;</p>
<p><strong>Answer</strong>: FREL is the level of emissions from REDD of REDD+ (keep trees standing), but FRL includes removal of emissions (+ of REDD+, like planting new trees, to put it simply). You can find more information about FREL/FRL <a href="https://www.unredd.net/knowledge/redd-plus-technical-issues/nfms-rel.html">here</a>.&nbsp;</p>
<p>&nbsp;</p>
<p><strong>Question 3</strong>: There are so many REDD+ projects out there. How did you choose which one to look at?&nbsp;</p>
<p><strong>Answer</strong>: The number of REDD+ is limited and finite if we are talking about REDD+ at the national level, meaning one per country, with the exception of Brazil, which has two (Amazonia and Cerrado). Then why are there so many REDD+ projects? This is because anyone can use the word "REDD+" in naming a project without any process of verification that the project aims to reduce and remove emissions from forests. As more awareness was raised about the relationship between climate change and forests, which can be used to secure more funding to existing projects in the forestry, "REDD+" was often used to communicate that relationship and the importance of their project rather than to actually mean that the project aims to reduce or remove emissions from forests.&nbsp;</p>
<p>Having said that, there are REDD+ at the project level. It's fairly easy to distinguish them, because the project probably has emission information, monitoring and verification, safeguarding against leakage or displacement, etc.
<p>&nbsp;</p>
<p><strong>Question 4</strong>: I work for a government. How can I use the <a href='https://earthenginepartners.appspot.com/science-2013-global-forest'>Global Forest Change (GFC)</a> data to check deforestation? We do not include plantations and also have a specific definition of forests (e.g. minimum area and canopy cover).&nbsp;</p>
<p><strong>Answer</strong>: If you work for a government, you probably have geographical information about your forests, excluding or including certain plantations or other non-forest land use (e.g. settlements). You can use that information as a <a href="https://en.wikipedia.org/wiki/Shapefile">shapefile</a>&nbsp;to process GFC data. You can also <a href="https://docs.qgis.org/2.8/en/docs/training_manual/create_vector_data/create_new_vector.html">draw a polygon</a> of the area by hand for a quick analysis using <a href="https://www.qgis.org/en/site/">a free and open source GIS software</a>.</p>
<p><a href = 'https://www.globalforestwatch.org/'>Global Forest Watch</a> recently released <a href = 'https://blog.globalforestwatch.org/data/new-plantations-map-sheds-light-on-complexities-of-deforestation?utm_campaign=gfw_map&utm_source=gfwtwitter&utm_medium=photo&utm_term=globalplantations_3_2019'>a plantations map</a>. You can use <a href='http://data.globalforestwatch.org/items/planted-forests'>their shapefile</a> to process the data. Below is an example of finding <a href='http://data.globalforestwatch.org/datasets/33451575fd3e440db27952ea456abb46_10'>a shapefile</a> from GFW.<p>

<p><a title="" href="https://www.geos.ed.ac.uk/homes/s1683747/gfw.png" target="_blank" rel="noopener"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://www.geos.ed.ac.uk/homes/s1683747/gfw.png" alt="step2" width="700" height="366" /></a></p>
<br></br>
Our code (written in <a href='https://www.python.org/'>Python</a>) allows you to define forests according to your definition (minimum area and canopy cover, but not tree height). How did we do it? It was difficult (see <a href="https://cdn.iopscience.com/images/1748-9326/14/2/024015/Full/erlaafc6bf1_lr.jpg">here</a> and <a href="sp.png">here</a>). Before running the code, you need to save <a href="https://earthenginepartners.appspot.com/science-2013-global-forest/download_v1.6.html">GFC data</a> of the region of your interest in the directory.</p>
<p>Below is a step-by-step example:</p>
<p style="padding-left: 30px;"><strong>Step 1</strong></p>
<p style="padding-left: 30px;">Go to <a href="https://bitbucket.org/nkeikon/erl/">https://bitbucket.org/nkeikon/erl/</a>&nbsp;</p>
<p style="padding-left: 30px;">Click 'Source' and 'process_gfw.py'</p>
<p style="padding-left: 30px;"><strong>Step 2</strong></p>
<p style="padding-left: 30px;">Scroll down to line 314</p>
<p><a title="Step 2" href="https://www.geos.ed.ac.uk/homes/s1683747/step2middle.png" target="_blank" rel="noopener"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://www.geos.ed.ac.uk/homes/s1683747/step2middle.png" alt="step2" width="700" height="366" /></a></p>
<p style="padding-left: 30px;"><strong>Step 3</strong></p>
<p style="padding-left: 30px;">Set parameters and file</p>
<p><a title="Step 3" href="https://www.geos.ed.ac.uk/homes/s1683747/lastStepRev.png" target="_blank" rel="noopener"><strong><img style="display: block; margin-left: auto; margin-right: auto;" src="https://www.geos.ed.ac.uk/homes/s1683747/lastStepRev.png" alt="step3" width="700" height="365" /></strong></a></p>
<p>&nbsp;</p>
<p><strong>Question 5</strong>: Why does the GFC data include plantations?&nbsp;</p>
<p><strong>Answer</strong>: Any data derived from <a href="https://www.usgs.gov/faqs/what-remote-sensing-and-what-it-used?qt-news_science_products=7#qt-news_science_products">remote sensing</a> uses photosynthetic activities in vegetation to detect their location. They don't discriminate trees based on the land use class we assign. Isn't it unreasoble to assume that trees know what their purpose is for humans? ;)&nbsp;</p> More discussions about plantation areas and the GFC data for our analysis are in the second paragraph of <a href="https://iopscience.iop.org/article/10.1088/1748-9326/aafc6b">Section 3.1.3.</a> &nbsp;</p>
<p>&nbsp;</p>
<p><strong>Question 6</strong>: Your analysis included all trees in all areas. Are the results relevant to conservation?</p>
<p><strong>Answer</strong>: Yes, because we looked at the changes and the trends in the long term. We are not simply comparing the data from GFC and from FREL/FREL and saying that they are different. Of course they are different. Not all areas with trees are forests.</p>
<p>However, when you see consistent differences in the trend of forest change between two data, over a long period of time, it indicates a risk that vulnerable forests are located outside of the planned areas or the government's definition of "forests".&nbsp;</p>
<p>&nbsp;</p>
