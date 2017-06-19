Pompei Inscriptions Corpus for CapiTainS
========================================

## Origin of the data and acknowledgment

The source of the data are : 

- http://db.edcs.eu/epigr/epi_ergebnis.php / http://manfredclauss.de/gb/index.html organized and created by Manfred Clauss

## Notes
### Pre-formatting needed for Epigraphik Datenbank compared to original :

- Remove Head and doc declaration
- Removed first content up to the first paragraph
- Replace `width="35">` with  `width="35"\>`
- Replace `align="bottom">` with  `align="bottom"\>`
- Replace `&nbsp;` with  ` `
- Replace `&provinz` by `&amp;provinz`
- Replace `&longitude` by `&amp;longitude`
- Replace `&latitude` by `&amp;latitude`
- Replace `br>` with  `br\>`
- Removed last `<p>` (`<p style="font-size:110%;"><a href="http://db.edcs.eu/epigr/epi.php?s_sprache=en"><img src="Epigraphik%20Datenbank_files/back.gif" alt="Link zurueck zur Suchseite" border="0" align="bottom"/></a><br/><br/></p>`)

### CHET-C

Developed by Hugh Cayless and Tom Elliott (University of North Carolina at Chapel Hill). Converts epigraphic texts using conventional editorial sigla into EpiDoc-compliant XML. 
