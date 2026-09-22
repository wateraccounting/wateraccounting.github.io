# Dashboards
Welcome to IHE Delft Water Accounting team's dashboard overview. Since 2020, IHE Delft has been working on utilising WaPOR data to support agricultural and water management. Various results and products are presented in dashboards. This webpages provides an overview of a number of these dashboards.

for more information contact wateraccounting_project@un-ihe.org or check our [website](https://wateraccounting.un-ihe.org)


# Co-developed water management tools using WaPOR data

*FAO WaPOR · Country activities*

WaPOR supports countries in co-developing practical digital tools that turn satellite-based water data into actionable information: irrigation performance, irrigation scheduling, drought monitoring, water accounting and groundwater management.

Each tool is designed jointly with ministries, water authorities, research institutes and local partners, which is what makes long-term ownership and uptake possible.

[![Open the FAO tools page][FAO]](https://www.fao.org/in-action/remote-sensing-for-water-productivity/country-activities/tools-in-co-development/en)

![Map of the 10 WaPOR partner countries](https://www.fao.org/media/images/waporlibraries/default-album/10wapor-countries465d624e10fd4610a52302ea16dbc931.png?sfvrsn=54a0246f_0)

*Tools are being co-developed across the 10 WaPOR partner countries.*

## In this page

1. [Irrigation performance](#1-irrigation-performance-tools)
2. [Irrigation scheduling](#2-irrigation-scheduling-tools)
3. [Drought monitoring](#3-drought-monitoring-tools)
4. [National water information systems](#4-wapor-data-in-national-water-information-systems)
5. [Groundwater abstraction](#5-groundwater-abstraction-tools)
6. [Applications and web tools](#6-applications-story-maps-and-web-tools)

---

## 1. Irrigation performance tools

These tools analyse how effectively and equitably irrigation water is used. They deliver indicators such as water productivity, adequacy, equity and crop water deficit, so managers can improve irrigation service delivery.

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/sdn.svg?sfvrsn=df94ef36_1" alt="Sudan" height="14"> <b>Sudan</b> · Gezira irrigation performance dashboard (GIS-IPA-DS)</summary>

<img src="img/sudan.png" alt="Gezira irrigation performance dashboard" width="800">

Leaflet and Streamlit dashboard with performance indicators per irrigation block and main crop, for winter and summer seasons, built on WaPOR Level 2 data.

**Partners:** Ministry of Irrigation and Water Resources, Hydraulic Research Center and Gezira Scheme Management, with IHE Delft and IWMI.

**Scheme:** Gezira, ~890 000 ha and 4 300 km of canals, Africa's largest.

[![Button]](https://gezira-sudan-ipa.streamlit.app/)

</details>

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/ken.svg?sfvrsn=8eb5eb35_1" alt="Kenya" height="14"> <b>Kenya</b> · Performance of irrigation assessment tool (PIA)</summary>

<img src="img/kenya.png" alt="Performance of irrigation assessment tool" width="800">

Dashboards with optimal irrigation plans, crop water productivity indicators and downloadable reports. WaPOR 20 m data are combined with in situ soil moisture sensors.

**Partners:** National Irrigation Authority, Ministry of Water, Sanitation and Irrigation, JKUAT, FAO Kenya and IHE Delft.

**Schemes:** Mwea, Tana and Bura, over 29 000 acres.

[![Button]](https://mwea-ipa.streamlit.app/)

</details>

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/egy.svg?sfvrsn=4d85e36c_1" alt="Egypt" height="14"> <b>Egypt</b> · Irrigation assessment tool for Egypt (IPAT)</summary>

<img src="img/egypt.png" alt="Irrigation assessment tool for Egypt" width="800">

![Operational pilot][OperationalPilot]

Web tool hosted by the Ministry of Water Resources and Irrigation. It analyses water use and locates high and low productivity areas using WaPOR v3 Level 3 (20 m) data.

**Partners:** Ministry of Water Resources and Irrigation, scheme managers, policy makers and IWMI, with IHE Delft and FAO.

**Area:** Middle and West Delta, ~1.5 million ha, three irrigation systems.

[![Button]](https://zemamipa.streamlit.app/)

</details>

---

## 2. Irrigation scheduling tools

These tools turn WaPOR evapotranspiration and biomass into practical advice for farmers and irrigation managers: how much water the crop needs, and when to apply it.

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/col.svg?sfvrsn=c2740759_1" alt="Colombia" height="14"> <b>Colombia</b> · Irrigation assessment tool (IPA)</summary>

<img src="img/Colombia.png" alt="Irrigation assessment tool Colombia" width="800">

![Under development][UnderDev]

Dashboard combining irrigation performance and scheduling metrics. It joins ASBAMA local datasets with WaPOR Level 3 data to map water use, irrigation efficiency, crop water deficit and scheduling needs.

**Partners:** Ministry of Agriculture of Colombia, ASBAMA, the Río Frío, Sevilla, Tucurinca and Aracataca irrigation districts, and IWMI.

**Area:** Magdalena department, ~84 000 ha, around 900 000 t of bananas a year.

[![Button]](https://pi-advisor-v02-viewer.streamlit.app/?lang=en)

</details>

---

## 3. Global monitoring tools

These tools track agricultural drought, vegetation stress and water deficits over time, with spatially explicit indices and, in some cases, early warning information.

<details markdown="1">
<summary><b>Web map · Africa</b> · Drought Observe</summary>

<img src="img/droughtobservedash.jpg" alt="Drought Observe" width="800">

A drought monitoring system from the WaterPIP project, with near real-time drought intensity maps for Africa at 250 m and monthly steps, piloted in Kenya, Ethiopia and Mozambique.

**Method:** SPAEI from long-term dekadal water surplus and deficit (P − RET) fitted to a log-logistic distribution, then a decision-tree model regressing SPAEI against WaPOR phenology, land cover, precipitation, NDVI and temperature. Runs in Google Earth Engine.

[![Button]](https://waterpiporg.users.earthengine.app/view/dms)

</details>

---

## 4. WaPOR data in national water information systems

Here WaPOR data are embedded directly into existing institutional platforms, so ministries and water authorities can monitor irrigation, water use and water budgets as part of their routine work.

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/pse.svg?sfvrsn=299efced_1" alt="Palestine" height="14"> <b>Palestine</b> · WaPOR in the national water information system (WaPOR-NWIS)</summary>

<img src="img/palestine-nwis.png" alt="Illustrative raster thumbnail: national scale parcels" width="800">

Integration of WaPOR data with the digital National Water Information System to improve water budget reporting, agricultural water use monitoring, domestic supply planning and allocation.

**Partners:** Water Authority, Ministry of Agriculture, technical teams and FAO, with IHE Delft.

[![Button]][fao-palestine]

</details>

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/jor.svg?sfvrsn=fb64da4_1" alt="Jordan" height="14"> <b>Jordan</b> · WaPOR in the national water information system (WaPOR-NWIS)</summary>

<img src="img/jordan-nwis.png" alt="Illustrative raster thumbnail: national scale parcels" width="800">

Integration of WaPOR data with Jordan's digital National Water Information System to strengthen water budget reporting and support decisions on allocation, irrigation efficiency and sustainable use.

**Partners:** Ministry of Water and Irrigation, Jordan Valley Authority, University of Jordan and FAO, with IHE Delft and IWMI.

[![Button]][fao-jordan]

</details>

---

## 5. Groundwater abstraction tools

These tools estimate groundwater consumption and compare abstraction against crop water requirements, helping institutions spot over-abstraction and assess risks to aquifer sustainability.

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/pse.svg?sfvrsn=299efced_1" alt="Palestine" height="14"> <b>Palestine</b> · Groundwater abstraction monitoring tool (GAM)</summary>

<img src="img/Palestine.png" alt="Illustrative raster thumbnail: groundwater-irrigated parcels" width="800">

![Planned][Planned]

Will track groundwater extraction against crop water requirements, assess cropping patterns and monitor water use in a region that depends entirely on groundwater, with about 166 mm of rainfall a year.

**Partners:** Water Authority and Ministry of Agriculture, with IWMI and FAO.

**Area:** Jericho, southern Jordan Valley: date palm and vegetables.

[![Button]][fao-palestine]

</details>

<details markdown="1">
<summary><img src="https://www.fao.org/images/corporatelibraries/flags/jor.svg?sfvrsn=fb64da4_1" alt="Jordan" height="14"> <b>Jordan</b> · Groundwater abstraction monitoring tool (GAM)</summary>

<img src="img/Jordan.png" alt="Illustrative raster thumbnail: groundwater-irrigated parcels" width="800">

![Design phase][DesignPhase]

Will estimate water consumption in millimetres and cubic metres at farm and area level, and compare it with abstracted groundwater to support sustainable management.

**Partners:** Ministry of Water and Irrigation, Jordan Water Authority and University of Jordan, with IWMI.

**Area:** Jafer, southern Jordan, under 50 mm of rainfall a year.

[![Button]][fao-jordan]

</details>

---

## 6. Applications, story maps and web tools

Beyond the tools co-developed with national institutions, WaPOR data feed a wider set of applications built by universities, projects and hackathon teams. Use these as inspiration for your own work.

<details markdown="1">
<summary><b>Story map · Sudan</b> · Cultivated cropland extent in Sudan</summary>

<img src="img/sudan-storymap.png" alt="Cultivated cropland extent in Sudan" width="800">

An ArcGIS StoryMaps example covering July to September 2023, showing how WaPOR data can be turned into a narrative map for a wider audience.

[![Button]](https://storymaps.arcgis.com/stories/6a54ed0c923d489e91b318fee15b8cf9)

</details>

<details markdown="1">
<summary><b>Video</b> · Bringing WaPOR data to the field with QGIS and Mergin Maps</summary>

[![Bringing WaPOR data to the field with QGIS and Mergin Maps](https://img.youtube.com/vi/fm3ltKHz-dk/hqdefault.jpg)](https://www.youtube.com/watch?v=fm3ltKHz-dk)

How to take WaPOR layers from the desktop to field data collection on a mobile device.

[![Watch on YouTube][Watch]](https://www.youtube.com/watch?v=fm3ltKHz-dk)

</details>

<details markdown="1">
<summary><b>Video · Hackathon 2020</b> · PlantVillage and the WaPOR database</summary>

[![PlantVillage and the WaPOR database](https://img.youtube.com/vi/tQtca4a4X8A/hqdefault.jpg)](https://www.youtube.com/watch?v=tQtca4a4X8A)

The PlantVillage presentation from the 2020 WaPOR Hackathon, a good example of what a hackathon team can build with the database.

[![Watch on YouTube][Watch]](https://www.youtube.com/watch?v=tQtca4a4X8A)

</details>

<details markdown="1">
<summary><b>Project · Lebanon</b> · Time-series ET mapping for irrigation management (ITSET)</summary>

<img src="img/lebanon.png" alt="Time-series ET mapping for irrigation management" width="800">

ITSET fuses several remote sensing missions across different spatial and temporal resolutions to map daily water use, vegetation indices and, eventually, yield and water productivity at field scale. Outputs are delivered through an online platform and a smartphone app. The project is ongoing.

[![Button]](https://sites.aub.edu.lb/etmap/)

</details>

<details markdown="1">
<summary><b>Impact story · Kenya</b> · More crops per drop for food security</summary>

<img src="img/kenya-crops.png" alt="More crops per drop for food security" width="800">

A geostory from the IHE Delft Water and Development Partnership Programme repository, on the application of digital innovations in the Galana Kulalu Irrigation Scheme, Kenya. It shows how remote sensing and digital tools translate into on-the-ground irrigation decisions.

[![Button]](https://wdpprepository.org/catalogue/#/geostory/255)

</details>

---

> **Source:** FAO WaPOR, [Tools in co-development](https://www.fao.org/in-action/remote-sensing-for-water-productivity/country-activities/tools-in-co-development/en). Content summarised for teaching purposes; check the FAO page for the current status of each tool. The card thumbnails are illustrative raster patterns, not outputs of the tools themselves.

<!-- ========== BUTTONS AND STATUS BADGES ========== -->
[FAO]: https://img.shields.io/badge/Open_the_FAO_tools_page-F2C14E?style=for-the-badge
[Watch]: https://img.shields.io/badge/Watch_on_YouTube-C9A227?style=for-the-badge
[OperationalPilot]: https://img.shields.io/badge/Operational_pilot-1e6b4c?style=flat-square
[UnderDev]: https://img.shields.io/badge/Under_development-96602a?style=flat-square
[Planned]: https://img.shields.io/badge/Planned-4a5d74?style=flat-square
[DesignPhase]: https://img.shields.io/badge/Design_phase-4a5d74?style=flat-square
[Button]: https://img.shields.io/badge/Open_the_tool-17607A?style=for-the-badge
[FAOCountry]: https://img.shields.io/badge/Open_the_FAO_country_page-17607A?style=for-the-badge

<!-- ========== FAO COUNTRY PAGES ========== -->
[fao-jordan]: https://www.fao.org/in-action/remote-sensing-for-water-productivity/country-activities/jordan/en
[fao-palestine]: https://www.fao.org/in-action/remote-sensing-for-water-productivity/country-activities/palestine/en