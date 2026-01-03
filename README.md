# Text Mining Analyse – Wire Solutions

Deze repository bevat het Jupyter Notebook dat is gebruikt voor de
text mining-analyse binnen het afstudeeronderzoek voor Wire Solutions.
De analyse is uitgevoerd ter ondersteuning van het onderzoeksrapport
en dient als inhoudelijke verdieping van de servicedeskanalyse.

De focus ligt op het verkennen van tekstuele patronen in
incidentbeschrijvingen per behandelgroep.

## Doel van de analyse

Het doel van deze analyse is om inzicht te krijgen in inhoudelijke
verschillen tussen incidenten binnen verschillende behandelgroepen.
Met behulp van eenvoudige text mining-technieken wordt onderzocht
welke woorden en thema’s kenmerkend zijn per categorie.

De resultaten worden gebruikt om:
- bestaande incidentcategorieën beter te duiden;
- verschillen in doorlooptijd en werkdruk te interpreteren;
- bevindingen uit de kwantitatieve analyses te verdiepen.

De analyse is verkennend van aard en vormt geen zelfstandig
beslissingsmodel.

---

## Inhoud van het notebook

Het notebook bevat onder andere:
- inladen en opschonen van incidentdata;
- verwijderen van standaard en domeinspecifieke stopwoorden;
- woordfrequentieanalyse per incidentcategorie;
- TF-IDF-analyse voor het identificeren van kenmerkende termen;
- inhoudelijke interpretatie van resultaten per behandelgroep.

---

## Dataset

De gebruikte dataset is geanonimiseerd en niet opgenomen in deze
repository in verband met vertrouwelijkheid. Het notebook toont
de volledige analysemethodiek en kan worden uitgevoerd met een
vergelijkbare datasetstructuur.

---

## Technische omgeving

De analyse is uitgevoerd met Python en gangbare bibliotheken,
waaronder pandas, scikit-learn en nltk.
