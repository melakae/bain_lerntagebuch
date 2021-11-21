---
title: "5. Lerneinheit: Repository-Software für Publikationen und Forschungsdaten"
date: 2021-11-19
---

<h1>DSpace: Repository-Software für Publikations- und Forschungsdaten</h1>

<p>In dieser Lerneinheit haben wir uns mit DSpace beschäftigt. Dies ist eine Software für Repositories, worin Publikationen und Forschungsdaten abgelegt werden. Häufig handelt es sich dabei um Open Access Publikationen und Open Data. Führend ist DSpace für Publikations-Repositories. Aber auch für Forschungsdaten bieten sie eine Lösung an. Weiter bieten sie ein DSpace CRIS für Forschungsinformationen an. CRIS steht für Current Research Information System. <a href="https://dspacecris.eurocris.org/">Eurocirs.org</a> und ist meist eine webbasierte Datenbank, welche einen Überblick über aktuelle Forschungsaktivitäten einer Institution liefert und Publikationen zu Projekten und Forschungsaktivitäten sammelt<sub>1</sub>. Forschungsinformationen sind Forschungs-Metadaten über Personen, Projekte, Patente u.ä., welche der Forschungsberichterstattung dienen. Wie das Datenmodell einer solchen Datenbank aussieht, erklärt folgende Webseite übersichtlich und verständlich: <a href="https://kerndatensatz-forschung.de/version1/technisches_datenmodell/ER-Modell.html">Kerndatensatz-Forschung, technisches Datenmodell</a>. Die schematische Darstellung des Entitiy Relationshop Modell zeigt die Verbindungen zwischen den Forschenden, deren Publikationen, Projekte, an welchen sie arbeiten und auch, über welche Patente diese Person verfügt. Es ist auch definiert, welche Attribute jedes Objekt besitzt. So wird neben dem Namen bspw. auch die Nationalität und das Geburtsdatum aber auch eine Altersgruppe zu einer Person erfasst.</p>

<p>DSpace verfügt über eine OPI PMH Schnittstelle. Dies ist ein REST API. Mit einer REST API wird die Schnittstelle über Parameter in der URL gesteuert. Die Rückmeldung erfolgt in Webformaten wie z.B. XML oder JSON. Es ist eine maschinenlesbare Schnittstelle, welche auf webbasierten Technologien aufbaut. REST API sind universell einsetzbar und stark verbreitet.</p>

<p>Der REST-Standard stellt sicher, dass jede Anfrage an die Schnittstelle ohne Kontext möglich ist, d.h. frühere Abfragen müssen nicht gespeichert werden. Jede Anfrage enthalten alle Informationen, welche für die Abfrage benötigt werden. </p>

<p>DSpace verfügt über eine Testinstanz, welche frei zugänglich ist im Internet unter <a href="http://demo.dspace.org/">demo.dspcae.org</a>. Im Unterricht haben wir eine Subcommunity und darin eine eigene Collection angelegt. Die Community bündelt Collections und stellt sicher, dass die Berechtigungsrollen nicht für jede Collection einzeln definiert werden müssen. D.h. erhält eine Rolle Administrationsrechte, so kann der User mit dieser Rolle alle darunterliegenden Collection administrieren.</p>

<p>Bei der Collection wird festgelegt, welchen Publikationsworkflow eine Publikation nehmen muss. So kann bspw. definiert werden, dass jede hinzugefügte Publikation durch eine definierte Rolle geprüft und freigegeben werden muss, bevor sie im Repository erscheint. </p>

<p><img src="https://github.com/melakae/bain_lerntagebuch/issues/3#issue-1059404312" alt=Ansicht: Konfiguration des Publikations-Workflows in DSpace" width=100%><br>
  <i>Konfiguration des Publikations-Workflows in DSpace, Bildquelle: demo.dspcae.org</i><br></p>
  
 <p><img src="https://github.com/melakae/bain_lerntagebuch/issues/2#issue-1059404223" alt=Ansicht: Freigabe des Publikations-Workflows in DSpace" width=100%><br>
  <i>In dieser Maske erfolgt die Freigabe der Publikation in DSpace, wenn ein Freigabe-Workflow konfiguriert wurde, Bildquelle: demo.dspcae.org</i><br></p>

<p>In der Collection haben wir dann ein Werk hinzugefügt. Dabei kann auch die Lizenz hinterlegt werden, welche dem Nutzenden anzeigt, ob Sie die Publikation nutzen dürfen. Über die Creative Common Lizenz kann bestimmt werden, ob eine Weiterbearbeitung möglich ist und unter welchen Bedingungen. So kann bspw. festgelegt werden, dass die Datei verändert werden darf, dann aber mit der gleichen Lizenz wieder publiziert werden muss. Folgende Webseite erklärt die Creative Common Lizenzen einfach verständlich: <a href="https://www.bildersuche.org/creative-commons-infografik.php">Bildersuche.org, Creative Commons Lizenzen</a>.</p>

<p>Diese Lerneinheit war spannend. Ich konnte hier mein Wissen aus dem Seminar vom HS20-Semester verbinden, wo wir uns mit CRIS und dem Institutional Repository (IRF) einer Fachhochschulbibliothek auseinandergesetzt haben.</p>

<h2>Literaturnachweis</h2>
<p><sub>1</sub> Azeroual, O., Saake, G., & Abuosba, M. (2018). Data Quality Measures and Data Cleansing for Research Information Systems. Journal of Digital Information Management, 16(1), S.12-21.</p>
