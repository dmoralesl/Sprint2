# Sprint 2: Maquetació amb Bootstrap i SASS

## Estructura del projecte

Aquest projecte es composa d'un fitxer html principal anomenat index.html situat a l'arrel del projecte. Aquest és el punt d'entrada i el que conté tota la maquetació de la web.

A la carpeta "public" podem trobar el favicon per a mostrar-se com a miniatura a la barra superior del navegador, i la carpeta "images" on estan tots els recursos visuals emprats.

A la carpeta "styles" tenim el fitxer SASS anomenat main.scss i la seua compilació css (main.min.css i main.min.css.map). Al fitxer .scss trobem l'estil personalitzar que s'ha fet servir per customitzar l'aspecte d'alguns dels components de Bootstrap i també la creació d'altres estils propis requerits per complir amb els dissenys.

Per últim, a la carpeta "bootstrap" está el framework Bootstrap 5 sense compilar. Podríem haver emprat el CDN per importar-lo directamente desde el host remot o haver arrancat un projecte de Node per instal·lar la llibreria com una dependencia del projecte. No s'ha fet cap canvi sobre el codi original d'aquesta carpeta.


## Notes

A un projecte real no s'hauria pujat ni la carpeta "bootstrap" ni el codi css compilat a partir dels fitxers .scss. Però per motiu d'estalviar temps de correcció, en aquest cas s'ha facilitat. Cal recordar que Git (i en especial GitHub per la limitació de tamany dels projectes) és un repositori de codi, i que totes aquelles dependencies i recursos que es puguin instal·lar via pipelines de desplegament o accions manuals del developer, no deuen estar versionades a Git.
