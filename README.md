# KSN
KSN_Projekt

Das ist das KSN Projekt von Sascha Ensmann, kenan Hodzic und Xuxiang Chen über GNU Radio.

GNU Radio ermöglicht die Entwicklung von SDR-Anwendungen, bei denen Hardwarekomponenten eines Radios durch Software ersetzt werden. Diese Umstellung führt zu einer beträchtlichen Flexibilität und Anpassungsfähigkeit.

Obwohl Linux die optimale Umgebung für GNU Radio bietet, sind auch Versionen für MacOS und Windows verfügbar. GNU Radio ist Open Source und unterliegt einer fortlaufenden transparenten Weiterentwicklung.

Die Einsatzmöglichkeiten von GNU Radio sind äußerst vielfältig und umfassen Bereiche wie Wireless Communication, Bildverarbeitung, Radar und IoT (Internet of Things).

Eric Blossom rief GNU Radio ins Leben, seitdem ist es ein unverzichtbarer Bestandteil der Funktechnik.

In GNU Radio werden Blöcke verwendet, um Schaltungen aufzubauen. In unserem Projekt haben wir beispielsweise ein File eingelesen und die enthaltenen Frequenzen wiedergegeben bzw. dargestellt.



Signal Source: Der Block erzeugt ein Signal direkt in GNU Radio. Er kann verschiedene Arten von Signalen erzeugen, wie beispielsweise Sinuswellen, Rechteckwellen, etc.

Multiply: Dieser Block führt eine Multiplikation zwischen zwei Eingangssignalen durch. Er kann für verschiedene Zwecke verwendet werden, wie zum Beispiel die Amplitudenmodulation oder das Mischen von Signalen.

FM Demod: Dieser Block demoduliert ein FM (Frequenzmodulation) Signal und gibt das demodulierte Audiosignal aus. Er ist besonders nützlich, wenn man FM-Radiosignale empfangen und verarbeiten möchte.

QT GUI Frequency Sink: Dieser Block visualisiert die Frequenzkomponenten eines Signals. Er zeigt die spektrale Verteilung des Eingangssignals an und ermöglicht es dem Benutzer, Frequenzbereiche zu überwachen.

QT GUI Waterfall Sink: Ähnlich wie der QT GUI Frequency Sink visualisiert dieser Block die Frequenzkomponenten eines Signals. Der Unterschied besteht darin, dass der QT GUI Waterfall Sink eine zeitliche Dimension hinzufügt, indem er ein Spektrogramm des Eingangssignals darstellt.

Low Pass Filter: Dieser Block filtert Hochfrequenzkomponenten aus dem Signal heraus und lässt nur die niederfrequenten Komponenten passieren.

Audio Sink: Dieser Block gibt das Eingangssignal aus.

Bilder:

![image](https://github.com/mqnky/ksn/assets/95501683/66615fff-a626-42bd-be10-475863f6bcd6)

![image](https://github.com/mqnky/ksn/assets/95501683/9c28026c-96cc-4e9f-a608-acf6b176740d)
