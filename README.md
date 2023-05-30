# Python Map Plotting

<details open>
<summary>Contents</summary>

1. [About](#about)
2. [Methods](#methods)
3. [Requirements](#requirements)
4. [Transliteration System](#transliteration-system)
5. [Contact](#contact)
</details>

## About
Plotting maps using python. Coded roughly, as a quick and temporary substitution for Tableau, when creating a customized map of Maharashtra with relevant locations. For now, minus the terrain and rails/roads, just the state and district borders are of interest.

[Maharashtra map](https://www.bragitoff.com/wp-content/uploads/2016/04/maharashtra.jpg) just for reference.

## Methods
Have plot using two methods.
1. First using geopandas and cartopy, which produced a crude map which required shapefiles of Maharashtra, a good one of which was difficult to come by. Nevertheless, found some [here](https://mapcruzin.com/free-maharashtra-country-city-place-gis-shapefiles.htm).
2. Second, used folium for an interactive map. Much better and refined, location names come as pop-ups on clicks. Required geoJSON files of Maharashtra, got it (with district borders) quite easily from [here](https://nikhilvj.carto.com/tables/maharashtra_districts/public)

## Requirements

1. As stated earlier, shapefiles or geoJSON files depending on the method.
2. Latitude and Longitude of locations. Easily found from GoogleMaps

## Transliteration system

For the location names: To maintain vernacular pronunciation, while still preserving readability as per original script, I have used a self-tampered [Harvard-Kyoto transliteration](https://en.wikipedia.org/wiki/Harvard-Kyoto#:~:text=The%20Harvard%2DKyoto%20Convention%20is,mail%2C%20and%20for%20electronic%20texts.) - with the voiced retroflex lateral approximant ळ written as La, and the schwa as Ə.

## Contact

<a href="https://www.linkedin.com/in/aditya-a-p-507b1b239/" target="_blank"><img src="https://img.shields.io/badge/Linkedin-0078b7?style=flat-square&logo=linkedin&logoColor=white&link=https://www.linkedin.com/" alt="Linkedin" width="85" height="25"></a>
<a href="mailto:apaditya96@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-red?style=flat-square&logo=Gmail&logoColor=white" alt="Gmail" width="70" height="25"></a>

