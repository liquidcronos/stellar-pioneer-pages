---
title: SDMBot
date: 2023-04-01
links:
  - type: site
    url: https://www.km.kit.edu/lookkit-202301.pdf
tags:
---

{{< youtube rfCBXFJD1Gc >}}

In der Industrie werden Roboter immer häufiger eingesetzt, da sie
eine hohe Flexibilität bieten. Allerdings wird diese Flexibilität oft durch
umständliche Programmierungsprozesse eingeschränkt. Oft müssen
Roboter manuell durch alle Bewegungen geführt werden, was Zeit
und Ressourcen bindet. Stattdessen sollte es möglich sein, den Robotern grob zu sagen, welche Aufgabe sie erfüllen sollen, und sie dann
selbst planen lassen, wie sie diese Aufgabe erfüllen.
Im Bereich der Manipulation gibt es bereits große Fortschritte mithilfe
von Ansätzen wie Reinforcement Learning und Model Predictive
Control (MPC). Im Bereich der Fertigung hinken diese Systeme jedoch
hinterher. Das liegt vor allem daran, dass die Robotersimulationen, die
für diese Befähigung genutzt werden, nicht in der Lage sind, Prozesse
zu simulieren. So werden beim Schweißen die Qualität der Naht nicht
betrachtet und beim Fräsen wird die Prozesskraft ignoriert.
Prozessbewusste Simulationen in der Robotik
Nur durch die Betrachtung der Interaktionen zwischen Prozess
und Roboter können die notwendige Genauigkeit und die hohe
Flexibilität erreicht werden, die für die Anforderungen von kürzeren
Produktlebenszyklen und hochvolatilen Märkten erforderlich sind.
Für die softwareseitige Befähigung von Robotern werden deshalb
ganzheitliche Simulationslösungen benötigt. Derartige Simulationstools ermöglichen es, den gesamten Fertigungsprozess in
einer virtuellen Umgebung zu modellieren und zu simulieren. Dies
umfasst die Roboter, Werkzeuge und Materialien, die im Fertigungsprozess verwendet werden. Die virtuelle Umgebung erlaubt es
dann, verschiedene Szenarien zu testen und die Auswirkungen von
Änderungen an den Prozessen und Robotern zu analysieren. Mittels
gängiger Planungsalgorithmen ist so eine autonome Planung einer
gegebenen Fertigungsaufgabe möglich.
Lösung des KIT
Am wbk Institut für Produktionstechnik wurden offene Softwaretools entwickelt welche genau diese Simulation ermöglichen
sollen. Hier wurden Robotersimulationen um Prozessmodelle wie
Fräsen, Schweißen oder Lackieren erweitert.

Eine Beispielapplikation dieser Tools wird auf der Hannover Messe
dargestellt. Dabei wird ein Schweißprozess vorsimuliert, bevor ein
Roboter die endgültige Trajektorie abfährt. Hier brauchen wir eine
neue Formulierung, die direkt auf den potentiellen Anwender in
der Industrie gerichtet ist. Dadurch wird es möglich, den Roboter in
einer realitätsnahen Umgebung zu testen und zu programmieren,
ohne dass tatsächlich physischer Kontakt erforderlich ist. Durch die
Simulation können Probleme und Schwachstellen im Vorfeld identifiziert und behoben werden, was zu einer besseren Qualität des
finalen Prozesses beiträgt.


<!--more-->
