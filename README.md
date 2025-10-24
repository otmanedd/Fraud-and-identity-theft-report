# Interactive Map Dashboard with Python and Streamlit
A python streamlit dashboard app which visualizes data in an interactive folium map. The dashboard demonstrates *Fraud and Identity Theft Report* published by [Federal Trade Commission](https://public.tableau.com/app/profile/federal.trade.commission/viz/FraudandIDTheftMaps/AllReportsbyState).

## This project was developed locally

## Screenshot
![(screenshot)](./screenshot.png?raw=true)

## Streamlit Map Dashboard
Ein interaktives Datenvisualisierungs-Dashboard, das geografische Daten mit Streamlit und Folium anzeigt.
Das Projekt zeigt, wie man Karten, Marker und DataFrames kombiniert, um datengetriebene Insights übersichtlich darzustellen.

## Features
- nteraktive Karte mit Folium
- Darstellung von Datenpunkten und Clustern
- Dynamische UI mit Streamlit
- Integration von Streamlit-Folium für Map-Rendering
- Anpassbare Datenquellen (CSV / API)

## Tech Stack
- Python : Hauptsprache
- Streamlit : Frontend Dashboard
- Folium : Kartenvisualisierung
- Pandas : Datenverarbeitung
- Streamlit-Folium : Einbettung der Karte in Streamlit

## How to run this app
```
git clone https://github.com/otmanedd/Fraud-and-identity-theft-report.git
   cd ~/streamlit-map-dashboard/Fraud-and-identity-theft-report/Fraud-and-identity-theft-report

```
## Virtuelle Umgebung erstellen und aktivieren:
```
python -m venv .venv
source .venv/bin/activate  # Auf Windows: .venv\Scripts\activate
python3 -m venv .venv
source .venv/bin/activate


```

## Abhängigkeiten installieren:
```
pip install --upgrade pip setuptools wheel
pip install pandas==2.2.2

pip install streamlit folium streamlit_folium pandas
pip install -r requirements.txt

```
## Anwendung starten:
```
streamlit run streamlit_app.py


```

## Lizenz
MIT License

Copyright (c) 2025 Otmane Dyaf

Permission is hereby granted, free of charge, to use, copy, modify, and distribute this software, without warranty, with the above copyright notice included.

## Further information

The project was developed locally and carefully structured.
The commit history on GitHub reflects the most important development steps;
some micro-commits have been combined for clarity.

## Autor
Otmane Dyaf



