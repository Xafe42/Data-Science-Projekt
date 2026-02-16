# 📊 Analyse der Einkommensentwicklung in Berlin-Brandenburg (2018–2025)

## 🎯 Projektziel
Dieses Data-Science-Projekt untersucht die Dynamik von Primär- und verfügbarem Einkommen in der Region Berlin-Brandenburg. Ein besonderer Fokus liegt auf der **Reallohnentwicklung** während der COVID-19-Pandemie und der darauffolgenden Inflationsphase, sowie dem spezifischen Gehaltsvergleich für **Informatiker:innen**.

> **Kontext:** Erstellt im Rahmen meines Studiums der Medieninformatik (BHT Berlin) als Teil meines Portfolios für die Praxisphase 2026.

---

## 🧐 Zentrale Forschungsfragen
1. **Trendanalyse:** Wie haben sich Primär- und verfügbares Einkommen pro Kopf seit 2018 entwickelt?
2. **Krisen-Impact:** Welchen messbaren Einfluss hatten die Pandemie und die Inflation auf die Kaufkraft?
3. **Branchen-Check:** Wie groß ist die Einkommenslücke zwischen dem allgemeinen Durchschnitt und IT-Fachgehältern?
4. **Reallohn-Check:** Konnten Gehaltssteigerungen in der IT die Inflation der Jahre 2022–2024 kompensieren?

---

## 🛠️ Tech-Stack & Datennutzung
- **Sprache:** Python 3.x
- **Bibliotheken:** Pandas (Datenverarbeitung), Matplotlib/Seaborn (Visualisierung), BeautifulSoup/Selenium (Webscraping)
- **Datenquellen:** - Amt für Statistik Berlin-Brandenburg (Primäreinkommen/Verfügbares Einkommen)
  - Destatis (Verbraucherpreisindex & Bruttomonatsverdienste)
  - Gehaltsdaten-Aggregatoren (Kununu, Indeed, Jobvector) via Scraping

---

## 📂 Projektstruktur & Notebooks
Das Repository enthält verschiedene Analyse-Module:
- `verfuegbares_einkommen.ipynb`: Aufbereitung und Visualisierung der amtlichen Haushaltsdaten.
- `Bruttomonatsverdienst_1991-2024.ipynb`: Langzeitanalyse der Verdienststrukturen.
- `gehaelter_scraping.ipynb`: Skripte zur Extraktion aktueller Marktdaten für IT-Berufe.
- `jahresgehaelter_nach_studiengang.ipynb`: Spezifischer Vergleich akademischer Einstiegsgehälter.

---

## 📈 Geplante Visualisierungen
- **Liniendiagramme:** Vergleich von nominalem vs. realem Einkommen (Inflationsbereinigt).
- **Index-Charts:** Wachstumstracker (Basisjahr 2018 = 100) für verschiedene Einkommensgruppen.
- **Balkendiagramme:** Visualisierung der "IT-Gehaltsschere" im regionalen Vergleich.

---
*Hinweis: Dieses Projekt dient akademischen Zwecken und der Veranschaulichung von Data-Science-Methodiken in einem wirtschaftlichen Kontext.*
