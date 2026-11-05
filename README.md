# Lernlandschaft Informatik – interaktiver Atlas

Eigenständiger Prototyp von Ibtissam Hommada für die Hochschule Niederrhein. **Kein offizielles Produkt der Hochschule Niederrhein.**

## Starten

`index.html` doppelt anklicken und in einem aktuellen Browser öffnen. Die Anwendung benötigt weder Server noch zusätzliche Bibliotheken und funktioniert auch offline.

## Funktionen

- Schematische geografische Lernlandschaft mit fünf Modulregionen (MA1, GDI, PE1, WIN, DR1)
- Anklickbare und per Tastatur erreichbare Lernstationen
- Didaktisch vorgeschlagene Wege zwischen Modulen
- Suche in Modulbeschreibungen, Lernzielen und Themen
- Semesterfilter und Filter für erkundete Module
- Zoom per Mausrad oder Buttons, Verschieben durch Ziehen, Zurücksetzen
- Detailansicht mit Themen, Lernzielen und fachlichen Beziehungen
- Lokal gespeicherte Erkundungsmarkierungen und JSON-Export
- Responsive Darstellung ohne externe Abhängigkeiten

## Veröffentlichung über GitHub Pages

1. Repository `https://github.com/HI-work-2024/HSNR` öffnen.
2. Die bestehende `index.html` im **Hauptverzeichnis** durch diese neue `index.html` ersetzen und committen. `README.md` kann ebenfalls ersetzt werden.
3. Unter `Settings > Pages` `Deploy from a branch`, `main`, `/(root)` beibehalten.
4. Nach erfolgreicher Bereitstellung `https://hi-work-2024.github.io/HSNR/` öffnen.
5. Falls die alte Version erscheint: Browser-Cache mit Strg+F5 neu laden.

## Fachlicher und rechtlicher Hinweis

Die Modulinhalte basieren auf bereitgestellten Modulbeschreibungen; die Texte wurden für die Darstellung gekürzt. Fachliche Wege sind **didaktische Interpretationen**, keine formalen Voraussetzungen. Vor einer offiziellen Nutzung aktuelle Modulhandbücher, Links, Barrierefreiheit, Datenschutz und Veröffentlichungsfreigabe prüfen.

## Weiterentwicklung

- Unterkarten mit einzelnen Konzeptknoten pro Modul
- Redaktioneller Dateneditor (Module, Lernziele, Wege)
- Verknüpfungen zu freigegebenen Lehrmaterialien
- Lernpfad-Algorithmus mit validierten Voraussetzungen
- Automatisierte Tests, vollständiger Accessibility-Audit und TYPO3-Integration
