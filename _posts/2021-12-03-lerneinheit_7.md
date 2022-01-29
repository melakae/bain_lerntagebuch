---
title: "7. Lerneinheit: Metadaten modellieren und Schnittstellen nutzen 2/2"
date: 2021-12-03
---

<h1>OpenRefine</h1>

<p>Diese Lerneinheit stand ganz im Zeichen des OpenSource Tools von OpenRefine. Mit diesem Tool können Metadaten transformiert und editiert werden.<br></p>

<p>Die Oberfläche zeigt in Tabellenform die geladenen Metadaten, welche nun gesamthaft oder auch spaltenweise geprüft, bereinigt und auch angereichert werden können. Wo sinnvoll können Ähnlichkeiten gefunden und Daten entsprechend geclustert werden. Dies ist bspw. bei Autoren sinnvoll. Gibt es mehrere Schreibweisen, kann diese mit wenig Aufwand vereinheitlicht werden. Dazu wird die Funktion Cluster in der entsprechenden Spalte aufgerufen. Das Tool macht Vorschläge, wo Ähnlichkeiten gefunden wurden. Der User entscheidet, ob er diese annimmt und wenn ja mit welcher der gefunden Schreibweisen.<br></p>

<p><img src="https://user-images.githubusercontent.com/83494929/144718420-d13e81ba-2a02-4d62-bce1-bc1278c543b0.png" alt=" Ansicht: Cluster-Funktion in OpenRefine" width="100%"><br>
  <i>Cluster-Funktion in der Spalte Authors in OpenRefine <sup>1</sup></i><br></p>

<p>Ebenfalls spannend ist die Funktion Reconsiliation. Damit können die Metadaten mit Daten aus anderen Datenbanken wie z.B. Wikidata angereichert werden. Dies macht bspw. für Journals Sinn. Über die ISSN können die entsprechenden Einträge gefunden und zugeordnet werden. Die Journals können in eine neu erstellte Spalte den Einträgen zugeordnet werden. Im Unterricht verwenden wir dazu die Datenbank Wikidata. Es handelt sich dabei um eine frei verfügbare Datenbank mit 96'093'698 Datenelemente (Stand 4.12.2021). Die Wissensdatenbank kann von Maschinen wie auch von Menschen genutzt werden. Der Inhalt ist über eine freie Lizenz verfügbar und die Inhalte können über Standardformate exportiert werden. Die Datenbank enthält strukturierte, mehrsprachige Daten von den Schwesterprojekten Wikipedia, Wikivoyage, Wikionary, Wikisource und weiteren (s. <a href="https://www.wikidata.org/wiki/Wikidata:Main_Page" target="_blank">Wikidata MainPage</a>).<sup>2</sup> <br></p>

<p>Die Inhalte von Wikidata werden kollaborativ gesammelt.<sup>3</sup> Jede/r – auch Organisationen –  können mit machen und die Datenbank weiter anreichern. Die Daten können bspw. über ein SPARQL Endpoint oder auch über URL-Schnittstellen in Formaten wie z.B. Jason, RDF genutzt werden. Weitere Informationen sind auf <a href="https://www.wikidata.org/wiki/Wikidata:Data_access" target="_blank">Wikidata: Data access</a> verfügbar.<sup>4</sup><br></p>

<p><img src="https://user-images.githubusercontent.com/83494929/144718443-8583a7d2-5d83-4da6-868f-c34edaf8be77.png" alt=" Ansicht: Neue Spalte hinzufügen in OpenRefine" width="100%"><br>
<i>Neue Spalte hinzufügen für Journals in OpenRefine. <sup>1</sup></i><br></p>

<p>Weiter kann über die Scriptsprache GREL ein Mapping vorgenommen werden, welche Spalte wo und wie im Export ausgegeben werden soll. So können nicht benötigte Daten weggeschnitten oder auch Inhalte gesplittet werden. Es ist auch möglich, die Reihenfolge zu ändern, so dass der Hauptautor am Anfang des Records erscheint und weitere Autoren aber am Ende des Datensatzes zu dem Werk. <br></p>

<p>GREL steht für General Refine Expression Language und ist ähnlich wie Javascript konzipiert.<sup>5</sup> Die Syntax kann zwei Formen aufweisen – entweder functionName (arg0, arg2, …) oder arg0.funktionName(arg1, …), wobei arg für Argument steht. Zweitere Form ist die Kurzfrom (dot notation), wohingegen die erstere die volle Notation (full notation) ist. So können die Ausdrücke unterschiedlich aussehen – je nachdem, ob jemand die dot oder full Notation verwendet. Es sind auch Steuerelemente (controls) verfügbar, womit Schleifenabfragen mit if und for möglich sind.<sup>5</sup> Es sind auch Funktionen verfügbar, bspw. für Boolean, Strings aber auch format-based Funktionen. Die Scriptsprache verfügt auch über Arrays, Datums-, Mathematik- und weitere Funktionen.<sup>6</sup> <br></p>

<p>Weiterführende Infos zu OpenRefine sind in der Dokumentation verfügbar unter <a href="https://docs.openrefine.org/" target="_blank">https://docs.openrefine.org</a>.<sup>7</sup><br></p>

<h3>Quellennachweis</h3>
<ul style="list-style:none">
  <li><sup>1</sup> OpenRefine. Testinstanz. <a href="https://openrefine.org/" target="_blank">https://openrefine.org</a>, abgerufen am 03.12.2021 </li>
  <li><sup>2</sup> Wikidata. Welcome to Wikidata. <a href="https://www.wikidata.org/wiki/Wikidata:Main_Page" target="_blank">https://www.wikidata.org/wiki/Wikidata:Main_Page</a>, abgerufen am 03.12.2021 </li>
  <li><sup>3</sup> Wikidata. Instroduction. <a href="https://www.wikidata.org/wiki/Wikidata:Introduction" target="_blank">https://www.wikidata.org/wiki/Wikidata:Introduction</a>, abgerufen am 03.12.2021</li>
  <li><sup>4</sup> Wikidata. Data access. <a href="https://www.wikidata.org/wiki/Wikidata:Data_access" target="_blank">https://www.wikidata.org/wiki/Wikidata:Data_access</a>, abgerufen am 03.12.2021</li>
   <li><sup>5</sup> OpenRefine. Manual, Grel. <a href="https://docs.openrefine.org/manual/grel" target="_blank">https://docs.openrefine.org/manual/grel</a>, abgerufen am 03.12.2021</li>
  <li><sup>6</sup> OpenRefine. Manual, Grelfunctions. <a href="https://docs.openrefine.org/manual/grelfunctions" target="_blank">https://docs.openrefine.org/manual/grelfunctions</a>, abgerufen am 03.12.2021 </li>
   <li><sup>7</sup> OpenRefine. Manual. <a href="https://docs.openrefine.org/" target="_blank">https://docs.openrefine.org</a>, abgerufen am 03.12.2021</li>
</ul>

