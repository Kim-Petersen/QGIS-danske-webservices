# Danske webservices til QGIS
En samling af danske WMS, WMTS, WCS og WFS geodata der udstilles uden brug af autentifikation:globe_with_meridians:.

Data fra Datafordeleren og Kortforsyningen medtages ikke da disse kræver adgang ved brug af [*tjenestebruger*](https://datafordeler.dk/vejledning/brugeradgang/) eller [*token*](https://apps2.kortforsyningen.dk/qgis_knap_config/QGIS3/About/qgis3about.html#brugeroprettelse) henholdsvis.

Indeholder en *.qlr* fil der kan indlæses i QGIS.
Det anbefales at ligge filen ind som en *.qlr* fil til brug sammen med [Kortforsyningens plugin til QGIS](https://apps2.kortforsyningen.dk/qgis_knap_config/QGIS3/About/qgis3about.html#tilfoejegnelag).

# Formål
Formålet er at samle frit tilgængelige geodata i en løsning der er enkel for brugeren at anvende.

# Datakilder

Beskrivelse | WMS | WMTS | WFS | REST Map | REST Feature
------------|-----|------|-----|----------|-------------
[Danmarks Arealinformation - DAIdb](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :white_large_square: | :white_large_square:
[Danmarks Arealinformation - DAI - Natur](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :white_large_square: | :white_large_square:
[Danmarks Arealinformation - DAI - Landbrugsdrift](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :white_large_square: | :white_large_square:
[Danmarks Arealinformation - DAI - Husdyr](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :white_large_square: | :white_large_square:
[DKJORD](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :white_large_square: | :white_large_square:
[PULS](https://support.miljoeportal.dk/hc/da/articles/360010519438-Webservices-PULS-data-tilg%C3%A6ngelig-p%C3%A5-nye-services-) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :heavy_division_sign: | :heavy_division_sign:
[Amter](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign: | :white_large_square: | :white_large_square:
[Miljøportalen Overfladevand og Luft](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :heavy_division_sign: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[Fortidsminder fra SKS](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :heavy_division_sign: | :heavy_division_sign:
[Plandata fra Erhvervsstyrelsen](https://support.miljoeportal.dk/hc/da/articles/206950129-Webservices-Arealinformation-Arealinformation-og-Webservices) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Natura 2000-Basisanalyse 2022-27](https://mst.dk/service/miljoegis/hent-data/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Basisanalyse vandområdeplane 2021-27](https://mst.dk/service/miljoegis/hent-data/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Naturmæssigt særlig værdifuld skov](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Kilmatilpasningsplaner](https://mst.dk/service/miljoegis/hent-data/) | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Støjkortlægning](https://mst.dk/service/miljoegis/) | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Husdyrregulering](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Program for naturovervågning og 2017-21](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Biodiversitet](https://mst.dk/service/miljoegis/) | :white_large_square: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Råstofindvinding på havet](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Blandede data](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS GIS til Natura2000](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Grundvandsdata](https://miljoegis.mim.dk/fagtekster/grundvand/miljoestyrelsens_udstilling_af_grundvandsdata.pdf) | :white_check_mark: | :white_check_mark: | :white_check_mark: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Støjkortet](https://mst.dk/service/miljoegis/hent-data/) | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign: | :heavy_division_sign:
[MiljøGIS Geologi](https://mst.dk/service/miljoegis/) | :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[Jordbrugsanalyser](https://lbst.dk/landbrug/kort-og-markblokke/jordbrugsanalyser/#c39828) | :white_large_square: | :white_large_square: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[Landbrugsstyrelsen](https://lbst.dk/landbrug/kort-og-markblokke/hvordan-faar-du-adgang-til-data/#c6647) |  :white_large_square: | :heavy_division_sign: | :white_large_square: | :heavy_division_sign: | :heavy_division_sign:
[GEUS Jupiter](https://www.geus.dk/produkter-ydelser-og-faciliteter/data-og-kort/national-boringsdatabase-jupiter) |  :white_check_mark: | :heavy_division_sign: | :white_check_mark: | :heavy_division_sign: | :heavy_division_sign:


# Bidrag
Har du forslag til forbedringer
* Flere datakilder?
* Links som ikke længere er i drift?
* Forkert tematisering?

Du er velkommen til at bidrage til at gøre denne samling så god som mulig.
Åbn et Issue, hvis du har forslag.