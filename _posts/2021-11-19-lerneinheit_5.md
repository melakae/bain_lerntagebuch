---
title: "5. Lerneinheit: Repository-Software für Publikationen und Forschungsdaten"
date: 2021-11-19
---

<h1>DSpace: Repository-Software für Publikations- und Forschungsdaten</h1>

<p>In dieser Lerneinheit haben wir uns mit DSpace beschäftigt. Dies ist eine Software für Repositories, worin Publikationen und Forschungsdaten abgelegt werden. Häufig handelt es sich dabei um Open Access Publikationen und Open Data. Führend ist DSpace für Publikations-Repositories. Aber auch für Forschungsdaten bieten sie eine Lösung an. Weiter bieten sie ein DSpace CRIS für Forschungsinformationen an. CRIS steht für Current Research Information System<sup>1</sup> und ist meist eine webbasierte Datenbank, welche einen Überblick über aktuelle Forschungsaktivitäten einer Institution liefert und Publikationen zu Projekten und Forschungsaktivitäten sammelt.<sup>2</sup> Forschungsinformationen sind Forschungs-Metadaten über Personen, Projekte, Patente u.ä., welche der Forschungsberichterstattung dienen. Wie das Datenmodell einer solchen Datenbank aussieht, erklärt folgende Webseite übersichtlich und verständlich: <a href="https://kerndatensatz-forschung.de/version1/technisches_datenmodell/ER-Modell.html" target="_blank">Kerndatensatz-Forschung, technisches Datenmodell</a>.<sup>3</sup> Die schematische Darstellung des Entity Relationship Modell zeigt die Verbindungen zwischen den Forschenden, deren Publikationen, Projekte, an welchen sie arbeiten und auch, über welche Patente diese Person verfügt. Es ist auch definiert, welche Attribute jedes Objekt besitzt. So werden neben dem Namen bspw. auch die Nationalität und das Geburtsdatum aber auch eine Altersgruppe zu einer Person erfasst.</p>

<p>DSpace verfügt über eine OPI PMH Schnittstelle. Dies ist ein REST API. Mit einer REST API wird die Schnittstelle über Parameter in der URL gesteuert. Die Rückmeldung erfolgt in Webformaten wie z.B. XML oder JSON. Es ist eine maschinenlesbare Schnittstelle, welche auf webbasierten Technologien aufbaut. REST API sind universell einsetzbar und stark verbreitet.</p>

<p>Der REST-Standard stellt sicher, dass jede Anfrage an die Schnittstelle ohne Kontext möglich ist, d.h. frühere Abfragen müssen nicht gespeichert werden. Jede Anfrage enthält alle Informationen, welche für die Abfrage benötigt werden. </p>

<p>DSpace verfügt über eine Testinstanz, welche frei zugänglich ist im Internet unter <a href="http://demo.dspace.org/" target="_blank">demo.dspcae.org</a>.<sup>4</sup> Im Unterricht haben wir eine Subcommunity und darin eine eigene Collection angelegt. Die Community bündelt Collections und stellt sicher, dass die Berechtigungsrollen nicht für jede Collection einzeln definiert werden müssen. D.h. erhält eine Rolle Administrationsrechte, so kann der User mit dieser Rolle alle darunterliegenden Collections verwalten.</p>

<p>Bei der Collection wird festgelegt, welchen Publikationsworkflow eine Publikation nehmen muss. So kann bspw. definiert werden, dass jede hinzugefügte Publikation durch eine definierte Rolle geprüft und freigegeben werden muss, bevor sie im Repository erscheint. </p>

<p><img src="https://user-images.githubusercontent.com/83494929/142767620-aa6d1ebf-d810-49a2-8aab-dfcf8cfc11fd.png" alt=" Ansicht: Konfiguration des Publikations-Workflows in DSpace" width="100%"><br>
  <i>Konfiguration des Publikations-Workflows in DSpace <sup>4</sup></i><br></p>
<br>  
<p><img src="https://user-images.githubusercontent.com/83494929/142767601-77d94bca-80e1-49d6-a011-a636a6b4014a.png" alt=" Ansicht: Freigabe des Publikations-Workflows in DSpace" width="100%"><br>
<i>In dieser Maske erfolgt die Freigabe der Publikation in DSpace, wenn ein Freigabe-Workflow konfiguriert wurde <sup>4</sup></i><br></p>

<p>In der Collection haben wir dann ein Werk hinzugefügt. Dabei kann auch die Lizenz hinterlegt werden, welche dem Nutzenden anzeigt, ob Sie die Publikation nutzen dürfen. Über die Creative Common Lizenz kann bestimmt werden, ob eine Weiterbearbeitung möglich ist und unter welchen Bedingungen. So kann bspw. festgelegt werden, dass die Datei verändert werden darf, dann aber mit der gleichen Lizenz wieder publiziert werden muss. Folgende Webseite erklärt die Creative Common Lizenzen einfach verständlich: <a href="https://www.bildersuche.org/creative-commons-infografik.php" target="_blank">Bildersuche.org, Creative Commons Lizenzen</a>.<sup>5</sup></p>

<p>Diese Lerneinheit war spannend. Ich konnte hier mein Wissen aus dem Seminar vom HS20-Semester verbinden, wo wir uns mit CRIS und dem Institutional Repository (IRF) einer Fachhochschulbibliothek auseinandergesetzt haben.</p>

<h2>Quellennachweis</h2>
<ul style="list-style:none">
  <li><sup>1</sup> The International Organisation for Research Information. EuroCRIS. <a href="https://dspacecris.eurocris.org/">https://dspacecris.eurocris.org</a>, abgerufen am 21.11.2021 </li>
<li><sup>2</sup> Azeroual, O., Saake, G., & Abuosba, M. (2018). Data Quality Measures and Data Cleansing for Research Information Systems. Journal of Digital Information Management, 16(1), S.12-21.</li>
  <li><sup>3</sup> Kerndatensatz-Forschung. Technisches Datenmodell. Entity-Relationship-Modell des Kerndatensatz Forschung. <a href="https://kerndatensatz-forschung.de/version1/technisches_datenmodell/ER-Modell.html">Kerndatensatz-Forschung, technisches Datenmodell</a>, abgerufen am 19.11.2021</li>
  <li><sup>4</sup> DSpace. DSpace 6.3 Demo Instance. <a href="http://demo.dspace.org/">http://demo.dspace.org</a>, abgerufen am 19.11.2021</li>
  <li><sup>5</sup> Mißfeldt, Martin. Creative Commons Lizenzen <a href="https://www.bildersuche.org/creative-commons-infografik.php">https://www.bildersuche.org/creative-commons-infografik.php</a>, abgerufen am 20.11.2021</li>
</ul>
