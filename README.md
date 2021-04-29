# OSI-Oil-Spill-Index
Show <a href="https://custom-scripts.sentinel-hub.com/sentinel-2/ndmi//">Script</a> or <a href="https://custom-scripts.sentinel-hub.com/custom-scripts/sentinel-2/ndmi/script.js">download</a> it.

<p>Oil spill Index (abbrv. OSI)</p>
<p>// General formula:</p> 
<p>// URL <a href="https://www.indexdatabase.de/db/si-single.php?sensor_id=96&rsindex_id=53">https://www.indexdatabase.de/db/si-single.php?sensor_id=96&rsindex_id=53</a></p>

 
<p>let OSI index = (B03 – B04) / B02;</p>
<p>return[index]</p>

<h2>Evaluate and visualize</h2>
<ul>
<li><a href="https://apps.sentinel-hub.com/eo-browser/?zoom=10&lat=42.8986&lng=11.0371&themeId=DEFAULT-THEME&datasetId=S2L1C&fromTime=2019-12-10T00%3A00%3A00.000Z&toTime=2019-12-10T23%3A59%3A59.999Z&visualizationUrl=https%3A%2F%2Fservices.sentinel-hub.com%2Fogc%2Fwms%2F42924c6c-257a-4d04-9b8e-36387513a99c&evalscript=aWYgKEI4QSA9PSAwIHx8IEIxMSA9PSAwKXsKICByZXR1cm4gWzAsMCwwXTsKfSBlbHNlIHsKICB2YXIgdmFsID0gKEI4QSAtIEIxMSkvKEI4QSArIEIxMSk7CiAgCiAgdmFyIHZtaW4gPSAtMC44OwogIHZhciB2bWF4ID0gMC44OwogIHZhciBkdiA9IHZtYXggLSB2bWluOwogIAogIHZhciByID0gMC4wOwogIHZhciBnID0gMC4wOwogIHZhciBiID0gMC4wOwoKICAKICB2YXIgdiA9IHZhbDsKCiAgaWYgKHYgPCB2bWluKXsKICAgIHYgPSB2bWluOwogIH0KICBpZiAodiA%2BIHZtYXgpewogICAgdiA9IHZtYXg7CiAgfQogIAogIHZhciBsMSA9IDAuMzU7CiAgdmFyIGwyID0gMC40ODsKICB2YXIgbDMgPSAwLjUyOwogIHZhciBsNCA9IDAuNjU7CiAgCiAgdmFyIGxldmVsMSA9ICh2bWluICsgbDEgKiBkdik7CiAgdmFyIGxldmVsMiA9ICh2bWluICsgbDIgKiBkdik7CiAgdmFyIGxldmVsMyA9ICh2bWluICsgbDMgKiBkdik7CiAgdmFyIGxldmVsNCA9ICh2bWluICsgbDQgKiBkdik7CgogIGlmICh2IDwgbGV2ZWwxKXsKICAgICByID0gMC41ICsgICh2IC0gdm1pbikgLyAobGV2ZWwxIC0gdm1pbikgLyAyOwogIH0gZWxzZSBpZiAodiA8IGxldmVsMikgewogICAgIHIgPSAxOwogICAgIGcgPSAodiAtIGxldmVsMSkgLyAobGV2ZWwyIC0gbGV2ZWwxKTsKICAgICBiID0gMDsKICB9IGVsc2UgaWYgKHYgPCBsZXZlbDMpIHsKICAgICByID0gMSArIChsZXZlbDIgLSB2KSAvIChsZXZlbDMgLSBsZXZlbDIpOwogICAgIGcgPSAxOwogICAgIGIgPSAodiAtIGxldmVsMikgLyAobGV2ZWwzIC0gbGV2ZWwyKTsKICB9IGVsc2UgaWYgKHYgPCBsZXZlbDQpIHsKICAgICByID0gMDsKICAgICBnID0gMSArIChsZXZlbDMgLSB2KSAvIChsZXZlbDQgLSBsZXZlbDMpOwogICAgIGIgPSAxOwogIH0gZWxzZSB7CiAgICAgYiA9IDEuMCArIChsZXZlbDQgLSB2KSAvICh2bWF4IC0gbGV2ZWw0KSAvIDI7CiAgfQoKICAgcmV0dXJuIFtyLCBnLCBiXTsKICAKfQo%3D#custom-script">EO Browser</a></li>
<li><a href="https://apps.sentinel-hub.com/sentinel-playground/?source=S2&lat=42.95617124218181&lng=11.052932739257812&zoom=11&preset=CUSTOM&layers=B01,B02,B03&maxcc=20&gain=1.0&gamma=1.0&time=2019-05-01%7C2019-11-21&atmFilter=&showDates=false&evalscript=aWYgKEI4QSA9PSAwIHx8IEIxMSA9PSAwKXsKICByZXR1cm4gWzAsMCwwXTsKfSBlbHNlIHsKICB2YXIgdmFsID0gKEI4QSAtIEIxMSkvKEI4QSArIEIxMSk7CiAgCiAgdmFyIHZtaW4gPSAtMC44OwogIHZhciB2bWF4ID0gMC44OwogIHZhciBkdiA9IHZtYXggLSB2bWluOwogIAogIHZhciByID0gMC4wOwogIHZhciBnID0gMC4wOwogIHZhciBiID0gMC4wOwoKICAKICB2YXIgdiA9IHZhbDsKCiAgaWYgKHYgPCB2bWluKXsKICAgIHYgPSB2bWluOwogIH0KICBpZiAodiA%2BIHZtYXgpewogICAgdiA9IHZtYXg7CiAgfQogIAogIHZhciBsMSA9IDAuMzU7CiAgdmFyIGwyID0gMC40ODsKICB2YXIgbDMgPSAwLjUyOwogIHZhciBsNCA9IDAuNjU7CiAgCiAgdmFyIGxldmVsMSA9ICh2bWluICsgbDEgKiBkdik7CiAgdmFyIGxldmVsMiA9ICh2bWluICsgbDIgKiBkdik7CiAgdmFyIGxldmVsMyA9ICh2bWluICsgbDMgKiBkdik7CiAgdmFyIGxldmVsNCA9ICh2bWluICsgbDQgKiBkdik7CgogIGlmICh2IDwgbGV2ZWwxKXsKICAgICByID0gMC41ICsgICh2IC0gdm1pbikgLyAobGV2ZWwxIC0gdm1pbikgLyAyOwogIH0gZWxzZSBpZiAodiA8IGxldmVsMikgewogICAgIHIgPSAxOwogICAgIGcgPSAodiAtIGxldmVsMSkgLyAobGV2ZWwyIC0gbGV2ZWwxKTsKICAgICBiID0gMDsKICB9IGVsc2UgaWYgKHYgPCBsZXZlbDMpIHsKICAgICByID0gMSArIChsZXZlbDIgLSB2KSAvIChsZXZlbDMgLSBsZXZlbDIpOwogICAgIGcgPSAxOwogICAgIGIgPSAodiAtIGxldmVsMikgLyAobGV2ZWwzIC0gbGV2ZWwyKTsKICB9IGVsc2UgaWYgKHYgPCBsZXZlbDQpIHsKICAgICByID0gMDsKICAgICBnID0gMSArIChsZXZlbDMgLSB2KSAvIChsZXZlbDQgLSBsZXZlbDMpOwogICAgIGIgPSAxOwogIH0gZWxzZSB7CiAgICAgYiA9IDEuMCArIChsZXZlbDQgLSB2KSAvICh2bWF4IC0gbGV2ZWw0KSAvIDI7CiAgfQoKICAgcmV0dXJuIFtyLCBnLCBiXTsKICAKfQo%3D">SH Playground</a></li>
</ul>

<h2>General description of the script</h2>
<p>The OSI is an Oil spill Index uses visible bands of Sentinel-2 to display spilled oil over water in the costal/marine environment. The OSI is constructed by summing-up the bands representing the shoulders of absorption features of oil as numerator and the band located nearest to the absorption feature as denominator to discriminate oil spill as below.</p>
<p><b>OSI = (B03 + B04) / B02</b><p>

<h2>Description of representative images</h2>

<p>Images developed using oil spill index (OSI) with other indices showing the occurrence and distribution of oil spill (images acquired a. before (17 July, 2020), b. and c. during (01 and 06 August, 2020) and c. after (05 September, 2020) the oil spill). The results can be compared with the decorrelated spectral bands 4, 3 and 2 of Sentinel-2 given below (Rajendran et al., 2021b, c)</p>
<p>a. (R: (5+6)/7; G: (3+4)/2; B: (11+12)/8)</p>


<h1>Author of the script</h1>
<b>Sankaran Rajendran</b>


<h2>Description of representative images</h2>
<p>Images developed using oil spill index (OSI) with other indices showing the occurrence and distribution of oil spill (images acquired a. before (17 July, 2020), b. and c. during (01 and 06 August, 2020) and c. after (05 September, 2020) the oil spill). The results can be compared with the decorrelated spectral bands 4, 3 and 2 of Sentinel-2 given below (Rajendran et al., 2021b, c)</p>

<p>a. (R: (5+6)/7; G: (3+4)/2; B: (11+12)/8)</p>

![Sentinel-hub-page0001](https://user-images.githubusercontent.com/83344701/116521006-1a278080-a8dc-11eb-93aa-f3c7b62abe77.jpg)

<p>b. R: 3/2; G: (3+4)/2; B: (6+7)/5</p>

![Sentinel-hub-page0002](https://user-images.githubusercontent.com/83344701/116521066-2dd2e700-a8dc-11eb-88d5-af99356038fb.jpg)

<p>Decorrelated images of spectral bands 4, 3 and 2 of Sentinel-2 showing the occurrence and spatial distribution of oil spill (images acquired a. before (17 July, 2020), b. and c. during (01 and 06 August, 2020) and c. after (05 September, 2020) the oil spill).</p>

![Sentinel-hub-page0001 (1)](https://user-images.githubusercontent.com/83344701/116521231-5fe44900-a8dc-11eb-9ebc-451601306003.jpg)


<h1>References</h1>
<ol>
  <li>1.	Rajendran, S, Sadooni, F.N, Hamad Al Saad, Anisimov Oleg, Govil, H., Nasir, S, Vethamony, P., 2021. Monitoring Oil Spill in Norilsk, Russia using satellite data. Scientific Reports. 11, 3817.</li>
  <li>2.	Rajendran. S, Vethamony. P, Sadooni F.N, Hamad Al Saad, Jassim A. Al-Khayat, Govil. H, Nasir. S. 2021. Sentinel-2 image transformation methods for mapping oil spill - A case study with Wakashio oil spill in the Indian Ocean, off Mauritius. MethodsX 101327.</li>
  <li>3.	Rajendran. S, Vethamony. P, Sadooni F.N, Hamad Al Saad, Jassim A. Al-Khayat, Vashist O Seegobin, Govil. H, Nasir. S. 2021. Detection of Wakashio oil spill off Mauritius using Sentinel-1 and 2 data: Capability of sensors, image transformation methods and mapping. Environmental Pollution. 274, 116618.</li>
</ol> 
