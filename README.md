# Analyse globaler Videospielverkäufe (1980–2016)

## Projektüberblick
Dieses Projekt analysiert globale Videospielverkäufe über einen Zeitraum von 36 Jahren (1980–2016). Ziel ist es, datenbasierte Einblicke in Marktstrukturen, Publisher-Strategien sowie regionale und genrebezogene Präferenzen im Gaming-Markt zu gewinnen.

Die Analyse wurde im Rahmen eines Abschlussprojekts zur Datenanalyse mit Python durchgeführt.

---

## Datensatz
- Quelle: Kaggle (Video Game Sales with Ratings)
- Zeitraum: 1980–2016
- Inhalte:
  - Regionale Verkaufszahlen (Nordamerika, Europa, Japan, Other)
  - Globale Verkaufszahlen
  - Publisher, Genre, Plattform
  - Erscheinungsjahr
  - Kritiker- und Nutzerbewertungen
  - ESRB-Altersfreigaben

---

## Analyseziele
- Identifikation der weltweit erfolgreichsten Videospiele
- Untersuchung von Publisher-Strategien (Hit-orientiert vs. Volumenstrategie)
- Analyse regionaler Genre-Präferenzen
- Bewertung des Einflusses von Plattformen auf Verkaufserfolge
- Vergleich von Nutzer- und Kritikerbewertungen

---

## Vorgehen
- Datenbereinigung (Typkonvertierungen, Entfernen fehlerhafter Einträge)
- Analyse und Visualisierung fehlender Werte
- Feature Engineering (Plausibilitätsprüfung globaler vs. regionaler Sales)
- Deskriptive Statistik und Gruppierungen
- Visualisierung zentraler Ergebnisse

---

## Zentrale Erkenntnisse
- Nintendo dominiert die globalen Bestseller durch starke First-Party-Franchises
- EA und Activision verfolgen eine Volumenstrategie mit vielen Veröffentlichungen
- Deutliche regionale Unterschiede in Genre-Präferenzen
  - Action & Shooter dominieren westliche Märkte
  - RPGs sind besonders stark in Japan
- Plattformen prägen Verkaufsdynamiken maßgeblich (z. B. PS2, Wii, DS)
- Nutzerbewertungen sind im Durchschnitt höher und variabler als Kritikerbewertungen

---

## Verwendete Technologien
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Projektstruktur
- `*.ipynb` – Jupyter Notebook mit vollständigem Analyseprozess
- `README.md` – Projektbeschreibung

---

## Hinweise
Das Notebook ist vollständig dokumentiert und kann ohne zusätzliche Konfiguration ausgeführt werden, sofern die verwendeten Python-Bibliotheken installiert sind.
