A cartography of violence against indigenous people in Brazil.

## How to build this map

Requirements:

* [Mapbox Studio](https://www.mapbox.com/mapbox-studio)

Download or clone this repository locally:

    git clone git@github.com:InfoAmazonia/cartografia-violencia-contra-indigenas.git

Run wget to download data from [Hansen/UMD/Google/USGS/NASA](http://earthenginepartners.appspot.com/science-2013-global-forest/download_v1.2.html), which is licensed under [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/):

    wget -i treecover-files.csv -P ./data/treecover -c
