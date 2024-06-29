---
title: "Map Gallery"
page_header_bg: "images/background/page-title-bg.jpg"
date: 2024-02-29T16:52:24+06:00
image: "../images/posters/PrajwalParmar-FOSS4G.png"
draft: false
layout: "single"
---

#### Blue and Green cover around Tartu

Poster by: Prajwal Parmar, CEPT University

The map is created by using the overlay effect in QGIS. NDWI, NDVI and Urban False color composite were retrieved from Sentinel Hub (EO Browser). The base layer is the urban false color composite and the other two layers are on top of the base layer but using the overlay effect in the symbology I have tried to enhance the water bodies and green cover.

<!-- {{< figure
    src="../../images/posters/PrajwalPramar-FOSS4G.jpg"
    alttext="Plan of Tartu, Estonia. Probably 19 century"
    link="https://en.wikipedia.org/wiki/File:Plan_of_Tartu_19_century.jpg"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption="A cropped version of \"Plan of Tartu, Estonia. Probably 19 century\". Original via [**wikipedia.org**](https://et.wikipedia.org/wiki/Tartu_ajalugu) under [CC-BY-SA-2.5](https://creativecommons.org/licenses/by-sa/2.5)"
    >}} -->

{{< figure
    src="../images/posters/PrajwalParmar-FOSS4G.jpg"
    alttext="Blue and Green cover in Tartu"
    link="../images/posters/PrajwalParmar-FOSS4G.jpg"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

<br>
<br>

#### Building heights in Tartu

Poster by: Raúl García Estévez, University of Tartu

The following map is a 3D visualization of the urban landscape in Tartu, Estonia. The main dataset employed is the buildings from Estonian Land Board (Maa-amet). As background information roads (Maa-amet) and city districts (Tartu City Government) were used. The map was created in QGIS, combining 2.5D symbols and height classification using the height attribute from the original dataset to create a realistic representation of the urban environment.

{{< figure
    src="../images/posters/Raul_Garcia.jpg"
    alttext="Building heights in Tartu"
    link="../images/posters/Raul_Garcia.jpg"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

<br>
<br>

#### Word count for Tartu streets' article in Estonian Wikipedia

Poster by: Andres Kasekamp, Estonian Land Board

The following map's data is from the Estonian Wikipedia (Vikipeedia) and Estonian Land Board (Maa-amet). The streets' article was found using the MediaWiki Action API and street geometries are from the Estonian Topographic Database (ETAK). The In-ads gazetteer service was used to link these two data sources together. The API requests were done using Requests and Aiohttp libraries, data processing was handled with GeoPandas, and the visualization was created using QGIS 3.32.

{{< figure
    src="../images/posters/foss4g_AK - Andres Kasekamp.png"
    alttext="Word count for Tartu streets article in Estonian Wikipedia"
    link="../images/posters/foss4g_AK - Andres Kasekamp.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

<br>
<br>

#### Morphology of the Emajõgi river in Tartu City

Poster by: Lika Zhvania, University of Augsburg

"For the map creation, data was sourced from OpenStreetMap. The Tartu City boundary was obtained using the 'OSM place search' tool in QGIS, while the rest of the data was downloaded from Geofabrik. The entire process of data preparation, processing, and map creation was conducted using QGIS Desktop and Python scripting. QGIS's geoprocessing tools were utilized for data preparation, and Python scripts in QGIS's Python Console were used to create the connections between the river and buildings. Symbolization techniques in QGIS were applied for the final map.

The map is conceptual rather than analytical, with a minimalistic design and a color scheme inspired by blueberries."

{{< figure
    src="../images/posters/Emajogi-Tartu-Lika_Zhvania.png"
    alttext="Morphology of the Emajõgi river in Tartu City"
    link="../images/posters/Emajogi-Tartu-Lika_Zhvania.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}


<br>
<br>


#### Tartu Neighborhoods in English

Poster by: Connor Mahon, University of Tartu

The Estonian language is a beautiful and unique language. However, I thought it would be interesting to understand what each neighborhood in Tartu meant in English. I added a base map from ESRI Gray (light) in QGIS 3.28.12. For the neighborhood boundaries, I used Tartu Linna geohub. To find the translations, I posited the neighborhood names in Chat-GPT 3.5. The map is the result of this query.

{{< figure
    src="../images/posters/poster-Connor-Mahon.png"
    alttext="Tartu Neighborhoods in English"
    link="../images/posters/poster-Connor-Mahon.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

<br>
<br>


#### Pretty map Of Tartu City

Poster by: Hemed Lungo

The Map Was Generated using Google colab (Python codes Mainly) ,From Prettymap repository by Marcelo Prates with Openstreetmap dataset.

{{< figure
    src="../images/posters/Tartu_final-Hemed_Lungo.png"
    alttext="Pretty map Of Tartu City"
    link="../images/posters/Tartu_final-Hemed_Lungo.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}


<br>
<br>


#### Median Price Per Unit Area of Transactions with Residential Apartments in Tartu Districts on Time Period June 2023 - June 2024

Poster by: Kirke Narusk, Maa-amet (Estonian Land Board)

"This map compares the median prices per square meter in Euros of residential apartments by Tartu districts. The data is collected on time period June 2023-June 2024. Buildings and their construction years are included as background information as well as a 10 cm orthophoto.
All data used for the map is free open data from Estonian Land Board: [real property price statistics](https://www.maaamet.ee/kinnisvara/htraru/FilterUI.aspx), buildings and their construction years ([WFS of Estonian Topographic Database + Estonian Building Register](https://gsavalik.envir.ee/geoserver/etak_tuletis/wfs?service=WFS&version=1.0.0&request=Getcapabilities)), Tartu districts ([Place Name Register](https://xgis.maaamet.ee/xgis2/page/app/knravalik)), orthophotos ([WMS](https://kaart.maaamet.ee/wms/fotokaart?))."


{{< figure
    src="../images/posters/Median_price_Tartu_Maaamet - Kirke Narusk.png"
    alttext="Median price per unit area for residential apartments"
    link="../images/posters/Median_price_Tartu_Maaamet - Kirke Narusk.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}


<br>
<br>


#### Accessibility map of Tartu city

Poster by: Ayisha Yusibova

The map indicates the walking time from the city center of Tartu (Raekoja plats). The data used is from open-source datasets, including roads from OpenStreetMap (OSM) and city boundaries from the Estonian Land Board. Spatial data analysis was carried out using the Network Analysis tools in QGIS. The average pedestrian speed was considered to be 5 km/h, and based on this, four time intervals were calculated and merged together. As a final step, the network data was classified according to these time intervals and visualized. 

{{< figure
    src="../images/posters/accessibility_map_ayisha_yusibova.png"
    alttext="Accessibility map of Tartu city"
    link="../images/posters/accessibility_map_ayisha_yusibova.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}


<br>
<br>


#### Museums of Tartu

Poster by: Raul Garcia Estevez, Tartu University

The following map is a visualisation of the museums of Tartu, Estonia. The main dataset employed is a point dataset of museums extracted from OSM using OSMNX library in Python. As background information roads and city border (Maaamet) were used. The map was created in QGIS, using the street width attribute from the original road data and images from several data sources that were previously converted into svg. 


{{< figure
    src="../images/posters/Museums_map-Raúl_García_Estévez.png"
    alttext="Museums of Tartu"
    link="../images/posters/Museums_map-Raúl_García_Estévez.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

<br>
<br>

#### Tartu Pub Crawl

Poster by: Connor Mahon, University of Tartu

What better way to get acquainted with a city than a pub crawl? As a Tartu resident of almost three years, I chose the pubs based on my preferences. In QGIS 3.28.12, I added OSM as the base map in order to create a new vector layer (points) and selected each bar as well as the starting point, Vanemuise 46. After, I added road data from the Estonian Land Board. I ran snap geometries to layer from the processing toolbox. Then, I ran the "v.net.salesman" feature from the GRASS plugin to find the best route to hit each pub. I created another vector layer (points) and selected Vanemuise 46 to differentiate the starting point layer. Then, in the pubs layer, I used the "select feature" tool to choose the location of Vanemuise 46 and deleted it. After I performed the analysis, I used SVG Repo to upload the beer mug and starting point icons under symbology.


{{< figure
    src="../images/posters/tartu_pub_crawl - Connor_Mahon.png"
    alttext="Tartu Pub Crawl"
    link="../images/posters/tartu_pub_crawl - Connor_Mahon.png"
    width="100%"
    target="blank"
    rel="noopener noreferrer"
    caption=""
    >}}

