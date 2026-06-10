---
layout: project-example
title: "Prüfstand für fluiddurchströmte Bauteile | GetPEC mbH"
description: "Vollautomatisierter Prüfstand zur thermischen und hydraulischen Charakterisierung fluiddurchströmter Bauteile mit Wasser-Glykol-Gemischen im Bereich -30 °C bis 90 °C."
hero_title: "Projektbeispiel: Prüfstand für fluiddurchströmte Bauteile"
hero_subtitle: "Vollautomatisierter Prüfstand zur thermischen und hydraulischen Charakterisierung von Bauteilen mit Wasser-Glykol-Gemischen – entwickelt und gebaut von GetPEC mbH."
hero_image: "/assets/images/Teststand.jpg"
permalink: /projektbeispiele/pruefstand-fluiddurchstroemte-bauteile/
competences:
  - Prüfstandsentwicklung
  - Automatisierung
  - Datenerfassung
  - Thermodynamische Analyse
---

## Aufgabenstellung und Kontext

Für die Charakterisierung fluiddurchströmter Bauteile – beispielsweise Wärmetauscher-Prototypen, gekühlte Elektronikkomponenten oder Fahrzeugbauteile mit Kühlkanälen – wurde ein universell einsetzbarer Prüfstand benötigt. Dieser sollte eine breite Palette an Betriebsbedingungen abdecken, vollautomatisch betrieben werden können und aussagekräftige, reproduzierbare Messergebnisse liefern.

GetPEC hat diesen Prüfstand konzipiert, gebaut und in Betrieb genommen.

## Technische Eckdaten

| Parameter | Spezifikation |
|-----------|---------------|
| Prüfmedium | Wasser-Glykol-Gemisch, bis 60 % Glykol |
| Temperaturbereich | ca. −30 °C bis +90 °C |
| Volumenstrom | ca. 2–20 l/min |
| Druckdifferenz am Prüfling | 0–400 mbar |
| Betrieb | Vollautomatisch |
| Visualisierung / HMI | Integriert |
| Datenerfassung | Kontinuierlich, automatisch gespeichert |
{: .tech-specs-table}

## Aufbau und Systemkomponenten

### Fluidkreislauf

Der Prüfstand verfügt über einen geschlossenen Fluidkreislauf mit temperierbarem Reservoir, Kreiselpumpe mit Frequenzumrichter für stufenlose Volumenstromregelung, Bypassventilen und einem Plattenwärmeübertrager zur Temperaturkonditionierung. Ein Durchflussmesser (magnetisch-induktiv) misst den Volumenstrom präzise im gesamten Betriebsbereich.

### Temperierung

Für Temperaturen bis ca. +90 °C erfolgt die Beheizung elektrisch. Temperaturen unter Raumtemperatur werden durch ein angeschlossenes Kältegerät erreicht. Die Regelung hält die Einlauftemperatur des Prüflings auf ±0,5 K genau.

### Sensorik

An Ein- und Austritt des Prüflings werden Temperatur (Thermoelemente Typ K, kalibriert) und statischer Druck (piezoresistive Druckaufnehmer) gemessen. Aus diesen Messwerten werden automatisch Wärmedurchgangskoeffizient, Druckverlustbeiwert und hydraulischer Widerstand berechnet.

### Automatisierung und HMI

Die Steuerung erfolgt über ein LabVIEW-basiertes System mit einer übersichtlichen grafischen Bedienoberfläche. Messprogramme können vorprogrammiert und automatisch abgefahren werden. Alle Messdaten werden kontinuierlich in strukturierten Dateien gespeichert. Alarm- und Sicherheitsfunktionen überwachen kritische Parameter.

## Erweiterungsmöglichkeiten

Der Prüfstand wurde modular aufgebaut und lässt folgende Erweiterungen zu:

- **Elektrische Beheizung des Prüflings:** Zusätzliche Leistungsversorgung für Prüflinge mit elektrischen Heizelementen (z. B. zur Simulation definierter Wärmeströme)
- **Erhöhter Betriebsdruck:** Aufrüstung auf höhere Systemdrücke durch druckfestere Komponenten
- **Weitere Messgrößen:** Integration zusätzlicher Sensoren (z. B. Vibration, Leckage-Überwachung)
- **Fernzugriff:** Steuerung und Monitoring über Netzwerk

## Kompetenzdarstellung

Dieses Projekt illustriert folgende Kernkompetenzen von GetPEC:

- **Ganzheitliche Prüfstandsentwicklung:** Von der Anforderungsanalyse über Konzept, Konstruktion und Beschaffung bis zur Inbetriebnahme aus einer Hand
- **Fluidische und thermodynamische Auslegung:** Korrektes Dimensionieren von Pumpen, Wärmeübertragern, Regelventilen und Sicherheitskomponenten
- **Mess- und Automatisierungstechnik:** Integration von Sensorik, DAQ-Hardware und Steuerungssoftware zu einem funktionsfähigen System
- **Breites Anwendungsspektrum:** Der Prüfstand ist für Automotive-Kühlbauteile ebenso geeignet wie für Forschungsexperimente

## Weiterführende Informationen

- [Leistung: Prüfstandsentwicklung](/leistungen/pruefstandsentwicklung/)
- [Leistung: Messtechnik und Sensorintegration](/leistungen/messtechnik-und-sensorintegration/)
- [Kontakt für Prüfstandsanfragen](/kontakt/)
