---
title: "9. Lerneinheit: Linked Data"
date: 2022-01-14
---

<h1>Linked Data & letzte Vorlesung</h1>

<p>In der letzten Unterrichtseinheit haben wir uns mit Linked Data auseinandergesetzt. Doch was ist Linked Data überhaupt? Das W3C Konsortium beschreibt es als «Sammlung von miteinander verknüpften Datensätzen im Web».<sup>1</sup> Im semantischen Web können mittels Abfragen Daten abgefragt und mit Vokabularen Schlussfolgerungen gezogen werden. Dazu benötigt es aber Standardformate.<sup>1</sup>
<br></p>

<p>Informationsschnipsel werden einzeln beschrieben und diese dann miteinander in Beziehung gesetzt. Bei einem Buch wird z.B. der Autor in einen Datensatz geschrieben, das Werk in einen anderen. Danach werden beide verknüpft. Hat der Autor mehrere Werke, so kann bei jedem Werk auf den einen Datensatz des Autors zurückgegriffen werden und man muss ihn nicht immer wieder neu erfassen bzw. anlegen.<br></p>

<p>Auf der Basis der Linked Data Technologie wurde von der Library of Congress BIBFRAME gestartet zur Aufbereitung bibliografischer Daten.<sup>2</sup>
 <br></p>

<p>Mit BIBFRAME sollen die Daten in den Bibliothekskatalogen bessere Suchergebnisse liefern und den Zugang zu den Bibliotheksdaten zu senken. So sollen z.B. die Daten auch im World Wide Web (z.B. via Suchmaschinen wie Google) zu finden sein und auch für Personen verständlich sein, welche sich in der Bibliothekswelt nicht auskennen.<sup>3</sup> <br></p>

<p>BIBFRAME soll das heute Metadaten-Format MARC 21 ablösen. Die Deutsche Nationalbibliothek (DNB) ist an dem Pilotprojekt der BIBFRAME-Initative der Library of Congress beteiligt und beschreibt es wie folgt: «BIBFRAME ist ein Rahmenwerk, in dem bibliografische Daten mit Hilfe von Linked-Data- und Semantic-Web-Technologien angelegt, gespeichert, transportiert und bereitgestellt werden können.»<sup>4</sup> <br> </p>

<p>Bei der Recherche hat mich die Frage beschäftigt, warum MARC 21 abgelöst werden soll bzw. welchen Mehrwert man sich genau von BIBFRAME verspricht. Eine Antwort habe ich in der Projektbeschreibung der DNB gefunden. MARC 21 kann die heutigen Anforderungen, welche durch die starke digitale Vernetzung entstehen, nicht mehr erfüllen. Daher wurde die Initiative «Bibliographic Framework Initative (BIBFRAME)» von der Library of Congress gestartet. Ihr Ziel ist es, ein einheitliches Format zu entwickeln, welches die neuen technologischen Möglichkeiten wie Linked-Data und Semantic-Web nutzt und die bisherigen Formate ablösen kann.<sup>5</sup>  <br></p>

<p>Damit dies möglich ist, wird bei der Initiative darauf geachtet, dass die Überführung für Daten aus dem MARC 21 ins neue BIBFRAME-Format definiert wird. Der robuste Datenaustausch zwischen verschiedenen Institutionen soll weiterhin gewährleistet werden, da damit Kosteneinsparungen bei der Katalogisierung einhergehen.<sup>2</sup> Es macht keinen Sinn, dass jede Institution die Medien jeweils neu katalogisiert, das wurde in der Branche schon länger erkannt, weshalb auch mit einheitlichen Metadatenstandards gearbeitet wird, um so den Austausch der Daten zu erleichtern. Diesen Vorteil will man mit BIBFRAME bewahren. Es sind daher also Crosswalks nötig, um die Marc 21 Felder mit den Feldern aus BIBFRAME zu mappen.<sup>6</sup> Crosswalks haben wir in der <a href="https://melakae.github.io/bain_lerntagebuch/2021/09/15/lerneinheit_1.html">Lerneinheit 1</a> bereits behandelt, weshalb ich hier nicht weiter darauf eingehe. Auf der Website der Library of Congress<sup>2</sup> ist eine Vergleichstabelle verlinkt, womit die XML-Dateien in den beiden Formaten MARC und BIBFRAME anhand eines Beispiels direkt verglichen werden können.<sup>7</sup> Darin ist ersichtlich, dass das MARC-Format als Laie nur schwer verständlich ist. Man muss die Codes alle kennen, um den Eintrag als Mensch lesen bzw. verstehen zu können. Bei BIBFRAME kann aus dem XML-Schema bereits mehr herausgelesen werden. So ist z.B. ersichtlich, dass das aufgeführte Werk in Englisch ist. <br> </p>
  
<p><img src="https://user-images.githubusercontent.com/83494929/150636217-236912a7-252c-4636-9e82-da1767a9579c.png" alt="Vergleichsansicht MARC XML und BIBFRAME XML" width="100%"><br>
  <i>Vergleich MARC XML und BIBFRAME RDFXML <sup>7</sup> </i><br></p>

<p>Im Unterricht haben wir das Datenmodell von BIBFRAME angeschaut. Es wird zwischen Work, Instance und Item unterschieden. Jede «Bubble» in der Darstellung unten ist ein eigenständiger Datensatz. Diese Datensätze werden dann miteinander verknüpft (bspw. Verlag mit Instance). So muss ein Autor nur einmal erfasst werden, kann aber mit mehreren Werken und Formaten verknüpft werden. Damit erhält man auch Beziehungen zwischen den Datensätzen, die nicht explizit angegeben werden müssen. Es ergibt sich aus dem Datenmodell (bspw. Verlag x hat 10 Manifeste herausgegeben).<br></p>
  
<p><img src="https://user-images.githubusercontent.com/83494929/150636228-68297778-e00a-4ee6-af33-f8d75bdca066.png" alt="BIBFRAME Datenmodell" width="50%"><br>
  <i>Datenmodell BIBFRAME <sup>8</sup> </i><br></p>
  
<p>Zum heutigen Thema könnte noch viel mehr gesagt werden. Es ist ein sehr spannendes Thema und ich bin sehr gespannt auf die kommenden Entwicklungen.<br></p>

  
<h3>Quellennachweis</h3>
<ul style="list-style:none">
  <li><sup>1</sup> W3C, Standards Semanticweb. <a href="https://www.w3.org/standards/semanticweb/data">https://www.w3.org/standards/semanticweb/data</a>, aufgerufen am 21.01.2022 </li>
  <li><sup>2</sup> Library of Congress. BIBFRAME. <a href="https://www.loc.gov/bibframe/">https://www.loc.gov/bibframe</a>, abgerufen am 21.01.2022</li>
  <li><sup>3</sup> Library of Congress. BIBFRAME Manual. <a href="https://guides.loc.gov/bibframe-manual/bibframe-and-linked-data">https://guides.loc.gov/bibframe-manual/bibframe-and-linked-data</a>, abgerufen am 21.02.2022</li>
  <li><sup>4</sup> Deutsche Nationalbibliothekt. BIBFRAME. <a href="https://www.dnb.de/DE/Professionell/Standardisierung/Standards/_content/bibframe_akk.html">https://www.dnb.de/DE/Professionell/Standardisierung/Standards/_content/bibframe_akk.html</a>, abgerufen am 21.02.2022</li>
  <li><sup>5</sup> Deutsche Nationalbibliothek. BIBFRAME Projekt. <a href="https://www.dnb.de/DE/Professionell/ProjekteKooperationen/Projekte/BIBFRAME/bibframe_node.html;jsessionid=596FEA020C4572C04D3B1E35D7EE51D8.internet561">https://www.dnb.de/DE/Professionell/ProjekteKooperationen/Projekte/BIBFRAME/bibframe_node.html;jsessionid=596FEA020C4572C04D3B1E35D7EE51D8.internet561</a>, aufgerufen am 22.01.2022</li>
  <li><sup>6</sup> Xu A., Hess K., Akerman L. (2017). From MARC to BIBFRAME 2.0: Crosswalks. <a href="https://doi-org.ezproxy.fhgr.ch/10.1080/01639374.2017.1388326">https://doi-org.ezproxy.fhgr.ch/10.1080/01639374.2017.1388326</a>, aufgerufen am 22.01.2022</li>
  <li><sup>7</sup> Library of Congress. Compare MARC converted to BIBFRAME. <a href="https://id.loc.gov/tools/bibframe/compare-id/full-rdf">https://id.loc.gov/tools/bibframe/compare-id/full-rdf</a>, aufgerufen am 22.01.2021</li>
  <li><sup>8</sup> Library of Congress. Overview of the BIBFRAME 2.0 Model. <a href="https://www.loc.gov/bibframe/docs/bibframe2-model.html">https://www.loc.gov/bibframe/docs/bibframe2-model.html</a>, aufgerufen am 14.01.2022</li>
</ul>
