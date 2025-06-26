# Overstromingen en Mensenrechten: Een Panelanalyse van China, India en Indonesië (2005–2022)
## Over dit project
Deze repository bevat de data, code en resultaten van mijn scriptie. De studie onderzoekt het effect van overstromingen op mensenrechtenschendingen in drie landen over een periode van 18 jaar. Aan de hand van panelregressie is gekeken naar de impact op korte (directe invloed) en middellange termijn (invloed na 1 of 2 jaar). De onderzoeksvraag die centraal staat is:   
_Welk verband hebben natuurrampen, specifiek overstromingen, op mensenrechtenschendingen op zowel korte als middellange termijn in China, India en Indonesië in de periode 2005–2022?_   
![](https://github.com/marleen101/Scriptie/blob/main/Visualisatie/Plot-animatie.gif)

### Conclusie

&nbsp;&nbsp;&nbsp;&nbsp;In India en China werden geen verband gevonden tussen overstromingen en de mensenrechtenindex.  Overstromingen zouden geen invloed hebben op mensenrechtenschendingen in het land. Daarentegen was voor Indonesië op middellang termijn wel een verband gevonden tussen overstromingen en mensenrechtenindex.Eén en twee jaar na het plaatsvinden van overstromingen zouden de mensenrechtenindex verlagen. De mensenrechten worden minder gerespecteerd en vinden er meer mensenrechten schendingen plaats. Welke rechten precies wordt geschonden is niet uit de index te halen, maar kijkend naar eerder gedaan onderzoek worden vrouwenrechten regelmatig geschonden na natuurrampen (Detraz & Peksen, 2017, p. 166). Het zou plausibel zijn dat het ook hier het geval is, maar het is niet uit de resultaten te halen. Kortom is er voor Indonesië een herhaaldelijk negatief effect te zien tussen overstromingen en de index, wat erop wijst dat overstromingen invloed hebben op mensenrechtenschendingen in Indonesië.  

&nbsp;&nbsp;&nbsp;&nbsp;Daarnaast bleek dat financiële hulp een verband heeft met de mensenrechtenindex. Wanneer China, India en Indonesië weinig of juist veel financiële hulp kreeg per hoofd, zou het zorgen voor meer mensenrechtenschendingen. Het toenemen van mensenrechtenschendingen wanneer de landen weinig hulp krijgen, kan komen uit het onvermogen van de overheid om de mensenrechten te beschermen. Zoals Guttmann en Voigt (2017) vermeldde dat weinig toegang tot de juiste middelen kan zorgen dat het handhaven van de mensenrechten wordt belemmerd en hierdoor mensenrechtenschendingen toenemen (pp. 3-4). Veel financiële hulp zou er dan voor kunnen zorgen dat er wel toegang is tot de goede middelen om mensenrechten te beschermen, integendeel komt uit de resultaten dat veel financiële hulp ervoor zou zorgen dat er meer schendingen van mensenrechten plaatsvinden. Een eenduidige interpretatie van dit resultaat ontbreekt vooralsnog.  

&nbsp;&nbsp;&nbsp;&nbsp;Ten slotte was er een verband tussen de corruptie index en de mensenrechtenindex. Een toename van corruptie in een land lijkt samen te gaan met een stijging van de mensenrechtenindex, wat duidt op een afname van mensenrechtenschendingen. Corruptie zou mogelijk kunnen zorgen voor in een tijd van crisis politici hun eigen beleid gaan uitvoeren onder het mom van een crisis management. Daarnaast kan het in sterk corrupte contexten voorkomen dat mensenrechtenschendingen niet systematisch worden geregistreerd of gerapporteerd, wat een vertekend beeld van de situatie kan geven. Of deze verklaringen daadwerkelijk van toepassing zijn in dit geval, blijft echter onduidelijk.

### Samenvatting van de bevindingen
- In Indonesië is er een negatief en significant verband van overstromingen op mensenrechten, zowel op korte als middelllange termijn.  
- In China en India werd er geen significant invloed gevonden.  
- De hoogte van ontvangen buitenlandse hulp en de mate van corruptie blijken van invloed op de mensenrechtenindex.



### Gebruikte Datasets
- CIRI/CIRIGHTS Human Rights Data[^1] 
  - mensenrechtenindex (0–100)  
- EM-DAT[^2]
  - geregistreerde overstromingen (2005–2022)
- V-Dem Dataset [^3]
  - corruptie- en verantwoordelijkheidsindex
- OECD/Our World in Data [^4] [^5] 
  - buitenlandse hulp per hoofd van de bevolking

 ### Bestanden in de repository
 * `Data/` - De gebruikte datasets
 * `Script/` - De script die is gebruikt om de analyse uit te voeren in R
 * `Visualisatie` - Visualisatie van de mensenrechten index en het aantal overstromingen


[^1]: Cingranelli, D. L., Richards, D. L. & Clay, K. C. (2021). The CIRI Human Rights Dataset [Dataset]. CIRIGTHS. https://doi.org/10.7910/DVN/UKCPXT   
[^2]: Delforge, D., Wathelet, V., Below, R., Lanfredi Sofia, C., Tonnelier, M., Loenhout, J. A. F. van & Speybroeck, N. (2025). EM-DAT: The Emergency Events Database [Dataset]. International Journal of Disaster Risk Reduction, 124, 105509, https://doi.org/10.1016/j.ijdrr.2025.105509  
[^3]: Coppedge, M., Gerring, J., Knutsen, C. H., Lindberg, S. I., Teorell, J., Altman, D., Angiolillo, F., Bernhard, M., Cornell, A., Fish, M. S., Fox, L., Gastaldi, L., Gjerløw, H., Glynn, A., Good God, A., Grahn, S., Hicken, A., Kinzelbach, K., Krusell, J., Marquardt, K. L., McMann, K., Mechkova, V., Medzihorsky, J., Natsika, N., Neundorf, A., Paxton, P., Pemstein, D., von Römer, J., Seim, B., Sigman, R., Skaaning, S.-E., Staton, J., Sundström, A., Tannenberg, M., Tzelgov, E., Wang, Y., Wiebrecht, F., Wig, T., Wilson, S., & Ziblatt, D. (2025). V-Dem Country-Year Dataset v15 [Dataset]. Varieties of Democracy (V-Dem) Project. https://doi.org/10.23696/vdemds25  
[^4]: OECD (2025) – met kleine veranderingen aangebracht door Our World in Data (2025). Foreign aid received – Official donors [Dataset]. Our World in Data. 
[^5]: World Bank Group (2025). World Development Indicators - Population Total [Dataset]. https://databank.worldbank.org/source/world-development-indicators#
 
