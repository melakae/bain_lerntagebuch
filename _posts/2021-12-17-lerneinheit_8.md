---
title: "8. Lerneinheit: Suchmaschinen und Discovery-Systeme"
date: 2021-12-17
---

<h1>Discovery-System VuFind mit integrierter Suchmaschine Solr</h1>

<p>Im Vorfeld dieser Lerneinheit mussten wir VuFind installieren. Nach mehreren Anläufen hat es dann endlich geklappt. Im Unterricht haben wir uns intensiver mit der Applikation auseinandergesetzt. VuFind ist ein sogenanntes Discovery-System. Als Suchmaschine innerhalb des Systems wird Solr verwendet. Solr wird nicht nur in VuFind, sondern auch in anderen Branchen und Lösungen eingesetzt wie z.B. von Instagram, Netflix oder auch eBay.<sup>1</sup> <br></p>

<p>Solr nimmt das Relevanzranking vor, welches die Reihenfolge der Suchergebnisse bestimmt. Auch mitgegeben wird die Information, welche Bereiche hervorgehoben werden sollen bei den Suchresultaten. Die graphische Oberfläche von VuFind markiert dann diese Texte gelb und zeigt die Treffer in der Reihenfolge gemäss dem Relevanzranking von Solr an. Die Ansicht ist übersichtlich und kann einfach bedient und gelesen werden. Wenn die Suchergebnisse direkt in Solr aufgerufen werden, zeigt sich, dass diese nicht einfach verständlich sind, da die Treffer im JSON-Format ausgegeben werden.<br></p>

<p><img src="https://user-images.githubusercontent.com/83494929/146582606-e4bca8e7-6b5c-474d-9425-49b6464d24d5.png" alt=" Ansicht Solr Suchresultat" width="50%"><br>
  <i>Ansicht des Suchergebnisses in Solr <sup>3</sup></i><br></p>

<p>Das Relevanzranking funktioniert so, dass gewisse Parameter höher gewichtet werden als andere. Wenn z.B. der gesuchte Begriff im Titel vorkommt, hat dies einen höheren Faktor, als wenn ein ähnlicher Begriff als Verlag erscheint.<sup>2</sup> Kurz erklärt mit einer verständlichen Grafik wird dies auf der Webseite des Konkurrenten <a href="https://exlibrisgroup.com/de/produkte/primo/relevanzranking/">ExLibris Primo</a>. <br></p>

<p>Während des Unterrichts war die virtuelle Maschine sehr langsam und die Webexübertragung stockte immer wieder. Daher war es für mich nicht einfach der Übung zur Datenintegration zu folgen. Somit habe ich diese nach dem Unterricht gemacht und konnte erfolgreich die Daten aus DOAJ importieren. Bei den Beispieldaten für Koha hat bei einem Datensatz die ID für das Tag 001 gefehlt. Nachdem ich dieses eingefügt habe, konnte ich die beiden Koha-Datensätze ebenfalls importieren und habe nun insgesamt 12 Datensatze in VuFind.<br></p>

<p><img src="https://user-images.githubusercontent.com/83494929/146583302-bd31d257-6982-4d6c-8c37-a83d6816b557.png" alt=" Ansicht der Suchresultate auf VuFind" width="50%"><br>
  <i>Ansicht des Suchergebnisses in VuFind <sup>4</sup></i><br></p>

<p>Am Ende dieser Unterrichtseinheit haben wir nun alle Elemente des Schaubilds zu den Lehrinhalten behandelt. </p>

<p><img src="https://user-images.githubusercontent.com/83494929/146583725-d5f10130-b244-47de-8d20-11a9796ac6b8.png" alt="Grafische Darstellung des Lehrinhalts" width="100%"><br>
  <i>Schaubild Lehrinhalte BAIN <sup>5</sup> </i><br></p>

<p>Das Bibliothekssystem Koha (<a href="https://melakae.github.io/bain_lerntagebuch/2021/10/01/lerneinheit_2.html">Lerneinheit 2</a>) und das Archivinformationssystem ArchivesSpace (<a href="https://melakae.github.io/bain_lerntagebuch/2021/11/05/lerneinheit_4.html">Lerneinheit 4</a>) haben wir installiert und anschliessend Objekte erfasst. Bei der Repository-Software DSpace (<a href="https://melakae.github.io/bain_lerntagebuch/2021/11/19/lerneinheit_5.html">Lerneinheit 5</a>) konnten wir die Testumgebung nutzen und dort ein Dokument ins Repository hochladen. Diese Daten haben wir anschliessend aus der Schnittstelle kopiert und so exportiert. Bei Koha und ArchivesSpace konnten wir die Daten über die OAI-PMH-Schnittstelle (<a href="https://melakae.github.io/bain_lerntagebuch/2021/11/05/lerneinheit_4.html">Lerneinheit 4</a> und <a href="https://melakae.github.io/bain_lerntagebuch/2021/11/19/lerneinheit_5.html">Lerneinheit 5</a>) direkt mittels VuFindHarvest (<a href="https://melakae.github.io/bain_lerntagebuch/2021/12/02/lerneinheit_6.html">Lerneinheit 6</a>) aufrufen, um sie zu exportieren. Da die drei Datensätze unterschiedliche Metadaten-Standards aufwiesen, mussten sie in der Software marcEdit (<a href="https://melakae.github.io/bain_lerntagebuch/2021/12/02/lerneinheit_6.html">Lerneinheit 6</a>) in das Datenformat MARC21-XML transformiert werden. Dank dem Crosswalk standen dann die Daten in einem Metadaten-Standard zur Verfügung, in welchem sie anschliessen weiterverarbeitet werden konnten. Zusätzlich zu den drei erwähnten Systemen, wurden auch noch Tabellendaten im csv-Format in OpenRefine (<a href="https://melakae.github.io/bain_lerntagebuch/2021/12/03/lerneinheit_7.html">Lerneinheit 7</a>) behandelt und ebenfalls als MARC21-XML exportiert. In dieser Lerneinheit wurden die gesammelten Daten nun in die Suchmaschine Solr eingelesen, welche in VuFind integriert ist. In der grafischen Oberfläche von VuFind stehen nun die importierten Datensätze zur Verfügung und können genutzt werden. <br></p>

<h3>Quellennachweis</h3>
<ul style="list-style:none">
  <li><sup>1</sup> Apache Software Foundation. Solr.  <a href="https://solr.apache.org/community.html#powered-by">https://solr.apache.org/community.html#powered-by</a>, aufgerufen am 24.12.2021</li>
  <li><sup>2</sup> ExLibris Primo. Relevenzranking. <a href="https://exlibrisgroup.com/de/produkte/primo/relevanzranking/">https://exlibrisgroup.com/de/produkte/primo/relevanzranking</a>, aufgerufen am 24.12.2021</li>
  <li><sup>3</sup> Solr. <a href="http://localhost:8983/solr/#/biblio/query">http://localhost:8983/solr/#/biblio/query</a>, abgerufen am 17.12.2021</li>
  <li><sup>4</sup> VuFind. <a href="http://localhost/vufind">http://localhost/vufind</a>, abgerufen am 17.12.2021</li>
  <li><sup>5</sup> Lohmeier, Felix und Meyer, Sebastian (2021). Skript BAIN, 1. Technische Grundlagen. <a href="https://bain.felixlohmeier.de/#/01_technische-grundlagen">https://bain.felixlohmeier.de/#/01_technische-grundlagen</a>, abgerufen 20.09.2021</li>
  </ul>
