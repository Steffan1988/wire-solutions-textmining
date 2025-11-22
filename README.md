📘 README – Text Mining Analyse Incidentbeschrijvingen (Wire Solutions)
Dit repository bevat de Python-code, dataset en notebook die zijn gebruikt voor de text mining-analyse binnen het afstudeeronderzoek voor Wire Solutions.

🎯 Doel van de analyse
Tijdens het hoofdonderzoek is onderzocht hoe incidenten binnen verschillende behandelgroepen inhoudelijk van elkaar verschillen.
Met behulp van eenvoudige text mining (woordfrequentie & TF-IDF) is bepaald welke thema’s kenmerkend zijn per categorie.

De resultaten worden gebruikt om:
- de categorisatie van incidentgroepen te valideren,
- trends en doorlooptijden beter te interpreteren,
- en structurele verbetermogelijkheden te identificeren (bijv. 2e → 1e lijn).

📂 Repository-structuur
/data
    textmining_beschrijving-Incident.csv   # gebruikte dataset

/notebook
    textmining_analysis.ipynb              # volledige analyse

🧪 Inhoud van de notebook

De notebook bevat onder andere:
Data-inladen en opschonen
Verwijderen van standaard- én domeinspecifieke stopwoorden
Woordfrequentieanalyse per incidentcategorie
TF-IDF hottopics per incidentcategorie
Interpretatie van thema’s per behandelgroep

Export van resultaten
⚙️ Benodigde libraries

De code draait met:
pip install pandas numpy scikit-learn nltk

🔒 Privacy & datagebruik
De dataset bevat geen persoonsgegevens en is geanonimiseerd voor onderzoeksdoeleinden.

🧑‍💻 Auteur
Steffan Boer – Bootcamp Data Engineer – 2025
