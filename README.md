# OSI-Oil-Spill-Index
Show <a href="https://custom-scripts.sentinel-hub.com/sentinel-2/ndmi//">Script</a> or <a href="https://custom-scripts.sentinel-hub.com/custom-scripts/sentinel-2/ndmi/script.js">download</a> it.

<p>Oil spill Index (abbrv. OSI)</p>
<p>// General formula:</p> 
<p>// URL <a href="https://www.indexdatabase.de/db/si-single.php?sensor_id=96&rsindex_id=53">https://www.indexdatabase.de/db/si-single.php?sensor_id=96&rsindex_id=53</a></p>

 
<p>let OSI index = (B03 – B04) / B02;</p>
<p>return[index]</p>


<h2>General description of the script</h2>
<p>The OSI is an Oil spill Index uses visible bands of Sentinel-2 to display spilled oil over water in the costal/marine environment. The OSI is constructed by summing-up the bands representing the shoulders of absorption features of oil as numerator and the band located nearest to the absorption feature as denominator to discriminate oil spill as below.</p>
<p><b>OSI = (B03 + B04) / B02</b><p>

<h1>Author of the script</h1>
<b>Sankaran Rajendran</b>


<h2>Description of representative images</h2>
<p>‘Sentinele-2 Images developed using oil spill index (OSI) with other indices showing the occurrence and distribution of oil spill occurred off Mauritius located in the Indian ocean on August 06, 2020 (images acquired a. before (17 July, 2020), b. and c. during (01 and 06 August, 2020) and c. after (05 September, 2020) the oil spill). The results can be compared with the images of decorrelated the spectral bands 4, 3 and 2 given below (Rajendran et al., 2021b, c)’.</p>

<p>a. (R: (5+6)/7; G: (3+4)/2; B: (11+12)/8)</p>

![Sentinel-hub-page0001](https://user-images.githubusercontent.com/83344701/116521006-1a278080-a8dc-11eb-93aa-f3c7b62abe77.jpg)

<p>b. R: 3/2; G: (3+4)/2; B: (6+7)/5</p>

![Sentinel-hub-page0002](https://user-images.githubusercontent.com/83344701/116521066-2dd2e700-a8dc-11eb-88d5-af99356038fb.jpg)

<p>Decorrelated images of spectral bands 4, 3 and 2 of Sentinel-2 showing the occurrence and spatial distribution of oil spill (images acquired a. before (17 July, 2020), b. and c. during (01 and 06 August, 2020) and c. after (05 September, 2020) the oil spill).</p>

![Sentinel-hub-page0001 (1)](https://user-images.githubusercontent.com/83344701/116521231-5fe44900-a8dc-11eb-9ebc-451601306003.jpg)


<h1>References</h1>
<ol>
  <li>Rajendran, S, Sadooni, F.N, Hamad Al Saad, Anisimov Oleg, Govil, H., Nasir, S, Vethamony, P., 2021. Monitoring Oil Spill in Norilsk, Russia using satellite data. Scientific Reports. 11, 3817.</li>
  <li>Rajendran. S, Vethamony. P, Sadooni F.N, Hamad Al Saad, Jassim A. Al-Khayat, Govil. H, Nasir. S. 2021. Sentinel-2 image transformation methods for mapping oil spill - A case study with Wakashio oil spill in the Indian Ocean, off Mauritius. MethodsX 101327.</li>
  <li>Rajendran. S, Vethamony. P, Sadooni F.N, Hamad Al Saad, Jassim A. Al-Khayat, Vashist O Seegobin, Govil. H, Nasir. S. 2021. Detection of Wakashio oil spill off Mauritius using Sentinel-1 and 2 data: Capability of sensors, image transformation methods and mapping. Environmental Pollution. 274, 116618.</li>
</ol> 
