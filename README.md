# A/B Testanalyse voor Biedstrategieën

Dit project omvat het uitvoeren van A/B-testen om de effectiviteit van twee biedstrategieën te vergelijken: **Maximum Bieden** (Controle Groep) en **Gemiddeld Bieden** (Test Groep). Het doel is om te analyseren of er een statistisch significant verschil is in het aankoopgedrag tussen de twee strategieën.

## De volgende stappen werden uitgevoerd:

- **Gegevensanalyse**: De gegevens werden gecontroleerd op normaliteit en homogeniteit van de variantie voordat de tests werden uitgevoerd.
- **Statistische Tests**: Zowel parametrische (Onafhankelijke Twee-Groep t-test) als non-parametrische (Mann-Whitney U Test) tests werden gebruikt om te beoordelen of er een significant verschil is in de gemiddelde/mediaan aankoopwaarden.
- **Resultateninterpretatie**: Op basis van de p-waarden werden conclusies getrokken over de effectiviteit van de twee biedstrategieën.

## Belangrijkste Inzichten:
- Er werd geen significant verschil gevonden tussen de strategieën in termen van aankoopgedrag.
- Suggesties voor verdere analyse en verbetering van de A/B-testen omvatten het uitbreiden van de dataset, het verlengen van de testduur en het uitvoeren van segmentatie-gebaseerde tests.

## Gebruikte Technologieën:
- Python (Pandas, Scipy, Statsmodels)
- Jupyter Notebooks
