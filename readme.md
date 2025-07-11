# ResearchGrid-EU

## Übersicht

Dieses Projekt analysiert Forschungsoutput, Investitionen und Kooperationsmuster in EU-Ländern. Die Analyse ist um mehrere Hypothesen strukturiert, die jeweils in einem eigenen Jupyter-Notebook untersucht werden. Das Projekt verwendet Datenquellen wie Eurostat und OpenAlex, um den Zusammenhang zwischen Forschungsförderung, Publikationsoutput und institutioneller Zusammenarbeit zu untersuchen.

## Projektstruktur

- `Hypothese_1.ipynb` bis `Hypothese_7.ipynb`: Notebooks zu den einzelnen Hypothesen mit Datenanalysen, Visualisierungen und Ergebnissen.
- `data/input/`: Enthält Rohdaten (z.B. `Eurostat_Investitionen.csv`, `OpenAlex_Anzahl_Paper_Zeitraum.csv`).
- `data/output/`: Ausgabeverzeichnis für generierte Ergebnisse und Abbildungen.
- `data/cache/`: Zwischenspeicherung von Zwischenergebnissen.
- `requirements.txt`: Python-Abhängigkeiten.
- `settings.py`: Projektspezifische Einstellungen.
- `Ausarbeitung/`: Projektdokumentation und Präsentationen.

Die Multimediapräsentation kann aufgrund ihrer Dateigröße nicht in Git abgelegt werden und ist über den folgenden Link verfügbar: [Multimediapräsentation](https://drive.google.com/file/d/1oTOmZyGQf0pZ6E5H0CT43z1cRR6mQ7_g/view?usp=sharing)

## Datenquellen

- **Eurostat**: Investitionsdaten für EU-Länder.
- **OpenAlex**: Daten zu wissenschaftlichen Publikationen.

## Ausführung

1. Abhängigkeiten installieren:
   ```
   pip install -r requirements.txt
   ```
2. Parquet-Datei mit aufbereiteten Daten über folgenden Link herunterladen und im Ordner `data/input/` ablegen: [Data_OpenAlex.parquet](https://drive.google.com/file/d/1cDiPoDx_UZ0l6G_NLkQdk2EHphzEpqw7/view?usp=sharing)
3. Das gewünschte Hypothesen-Notebook (z.B. `Hypothese_1.ipynb`) in Jupyter oder VS Code öffnen.

## Hypothesen

Jedes Notebook untersucht eine spezifische Forschungsfrage, z.B.:
- Zusammenhang zwischen Forschungsinvestitionen und Publikationsoutput.
- Effizienz der Forschungsförderung in EU-Ländern.
- Kooperationsmuster zwischen Unternehmen und Forschungseinrichtungen.

Details zu jeder Hypothese und den jeweiligen Ergebnissen finden sich in den einzelnen Notebooks.

## Anforderungen

- Python 3.11
- Siehe `requirements.txt` für Paketabhängigkeiten.