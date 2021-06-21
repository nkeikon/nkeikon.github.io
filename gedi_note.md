<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-151917115-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-151917115-1');
</script>


## Timeline

|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Date&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Annoucement|Keiko observation|
|:-------------------|:---------------|:------|
|||Looking forward to level 4 (biomass) products! 
| 16 Apr 2021 |[Version 2](https://lpdaac.usgs.gov/news/release-gedi-version-2-data-products/) data released for Level 1B Geolocated Waveform Data, Level 2A Elevation and Height Metrics Data, and Level 2B Canopy Cover and Vertical Profile Metrics Data for April 18, 2019 through October 16, 2019|Improved geolocation, reduced file size, etc.|
| 18 Mar 2021  | [Level 3 dataset](https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1865) now available |👏👏👏 |
| 20 Jan 2021  | 18 months of GEDI data now publicly available |👏👏👏 |
| 26 Oct 2020  | One full year of GEDI data are now available |👏👏👏 |
| 30 Sep 2020  | Two more months of GEDI data now available. A total of 10 months of data online|👏👏👏 |
| 26 Aug 2020  | "GEDI L2A has measured redwoods > 90m. GEDI will produce a gridded L3 product at coarser resolution  (1 km or finer) based solely on GEDI data"
| 14 May 2020  | A series of Jupyter Notebook Tutorials [“Getting Started with GEDI L1B, L2A, and L2B Data in Python”](https://git.earthdata.nasa.gov/projects/LPDUR/repos/gedi-tutorials/browse) released by the LP DAAC|👏👏👏 |
| 12 May 2020  | [GEDI introduction video](https://www.youtube.com/watch?v=wxgrxvAKpTo&feature=youtu.be) released by NASA EarthData
| 16 Apr 2020  | NASA Earth Data: [GEDI subsetter released](https://git.earthdata.nasa.gov/projects/LPDUR/repos/gedi-subsetter/browse)|Hmm you still have to download the entire h5 first|
| 26 Feb 2020  | GEDI: One more month of data became available  |👏👏👏 |
| 20 Feb 2020  | NASA Earth Data: [GEDI finder web service released](https://lpdaac.usgs.gov/news/release-gedi-finder-web-service/)|Extremely useful! Life saver|
| 25 Jan 2020  | Space Intelligence: [GEDI viz released on twitter](https://twitter.com/SpaceIntelli/status/1221051568549744642)      |👏👏👏
| 21 Jan 2020  | GEDI: First GEDI data products became available via LPDAAC|Tree height overestimated? See the tip above dated 27 Aug 2020 |

## Other coding tools
- [pyGEDI](https://github.com/EduinHSERNA/pyGEDI)
- [rGEDI](https://github.com/carlos-alberto-silva/rGEDI)

## Documentation
[Global Ecosystem Dynamics Investigation (GEDI) Level 1B User Guide](https://lpdaac.usgs.gov/documents/987/GEDI01B_User_Guide_V2.pdf), version 2, April 2021
[GLOBAL Ecosystem Dynamics Investigation (GEDI) Level 2 User Guide](https://lpdaac.usgs.gov/documents/986/GEDI02_UserGuide_V2.pdf), version 2, April 2021
[GLOBAL Ecosystem Dynamics Investigation (GEDI) Level 3 User Guide](https://daac.ornl.gov/GEDI/guides/GEDI_L3_Land_Surface_Metrics.html), Version 1, March 2021


## Relevant publications
Coming soon

## GEDI tips
<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/GEDI?src=hash&amp;ref_src=twsrc%5Etfw">#GEDI</a> tips: RH stands for &#39;relative height,&#39; shown in m or cm, calculated at the percentage of cumulative waveform energy. So, RH100 means elev_highestreturn - elev_lowestmode</p>&mdash; Keiko (@Keiko_geo) <a href="https://twitter.com/Keiko_geo/status/1298197311441588224?ref_src=twsrc%5Etfw">August 25, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/GEDI?src=hash&amp;ref_src=twsrc%5Etfw">#GEDI</a> tips: &quot;The lowest selected mode has triggered on noise, thus elev_lowestmode will be below the actual ground surface&quot; (Level 02 User Guide), indicating that RH100 would overestimate the height <a href="https://t.co/cUGSpUfhWv">https://t.co/cUGSpUfhWv</a></p>&mdash; Keiko (@Keiko_geo) <a href="https://twitter.com/Keiko_geo/status/1298902916946944000?ref_src=twsrc%5Etfw">August 27, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/GEDI?src=hash&amp;ref_src=twsrc%5Etfw">#GEDI</a> tips: GEDI produces 8 tracks of data. Half of them are by full power lasers. Use the data from these power beams if your area has dense forests. The power beam sensitivities are 2-3% higher than the coverage beam</p>&mdash; Keiko (@Keiko_geo) <a href="https://twitter.com/Keiko_geo/status/1299297192805576705?ref_src=twsrc%5Etfw">August 28, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Power beams = &#39;0101&#39;, &#39;0110&#39;, &#39;1000&#39;, &#39;1011&#39;</p>&mdash; Keiko (@Keiko_geo) <a href="https://twitter.com/Keiko_geo/status/1299298177330315264?ref_src=twsrc%5Etfw">August 28, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br/><br/>
 

