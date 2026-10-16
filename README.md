# Monarch Migration Case Study
<i>Analyzing Eastern monarch migration for years 2015-2020<br></i>
<b>Samantha Goodman - January, 2022</b>
<br> Updated October 2026

<img src="https://pixnio.com/free-images/2016/06/06/monarch-butterfly-close-macro-orange-bug-insect.jpg"  width="300" height="200">
<img src="https://sjegoodman.github.io/monarch-migration/GifMap/GifMap2019.gif"  width="300" height="200">
 <b>Summary/Presentation: </b><a href="https://github.com/sjegoodman/monarch-migration/blob/main/MonarchMigrationPresentation.pdf">View</a> or <a href="https://sjegoodman.github.io/monarch-migration/MonarchMigrationPresentation.pdf">Download</a><br><br> 
 <b>Visualizations:</b>
  <ul><li><a href="https://sjegoodman.github.io/monarch-migration/GifMap/GifMap2019.gif">Animated gif of monarch migration</a> - Fall 2019</li>
    <li><a href="https://sjegoodman.github.io/monarch-migration/MigrationLatitudes.html">Map showing median latitudes of fall migration</a></li>
  <li>Interactive maps of <a href="https://sjegoodman.github.io/monarch-migration/Aug2020.html">August 2020</a> and <a href="https://sjegoodman.github.io/monarch-migration/Sep2020.html">September 2020</a></li>
<li><a href="https://public.tableau.com/app/profile/sjegoodman/viz/MonarchMigration/Dashboard1">Tableau Dashboard</a></li></ul>
<b>Jupyter Notebook: </b><a href="https://github.com/sjegoodman/monarch-migration/blob/main/MonarchMigration.ipynb">MonarchMigration.ipynb</a> · <a href="https://colab.research.google.com/github/sjegoodman/monarch-migration/blob/main/MonarchMigration.ipynb">Run it in Google Colab</a> (no install needed)<br><br>
 <b>Updated October 2026:</b> refreshed to run on current library versions (see <code>requirements.txt</code>). The notebook now falls back to a cached copy of the data if the source is unavailable, the interactive maps show each observer's date, count, and comment (the original photo links no longer load), and a <code>dropna()</code> filter bug is fixed. Details are at the top of the notebook.<br><br>
 <b>Technologies Used:</b> Python, Tableau, Pandas, Folium maps, HTML, Selenium webdriver<br><br>
 <b>Data Source:</b> Journey North (https://journeynorth.org/) via <a href="https://portal.edirepository.org/nis/mapbrowse?packageid=edi.949.1">Environmental Data Initiative</a>
