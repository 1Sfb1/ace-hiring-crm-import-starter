# Partnerfeed naar CRM
Het bronpakket bevat drie opeenvolgende CSV-leveringen en één statusmapping. Start met een leeg lokaal CRM. Iedere rij is een volledige momentopname van één object. De bestandsvolgorde is de ontvangstvolgorde. Tijden zijn UTC. Lege prijzen zijn ontbrekende waarden. De kolom corrects verwijst naar een eerdere foutregel. De volledige opdracht en acceptatievoorbeelden staan in de PDF in het sollicitantenportaal.

## Herstelproef
Breek bij de eerste regel van batch-02.csv (E05) de verwerking af nadat de CRM-wijziging duurzaam is weggeschreven, maar voordat de bezorging is bevestigd. Start het proces opnieuw, bied batch-02.csv opnieuw aan en draai daarna batch-03.csv. Bewaar bewijs van de onderbreking en de herstart. Vergelijk de eindstand met een ononderbroken referentierun.

## Eigen oplevering
Voeg zelf README.md met start- en testinstructies en reconciliatie.csv met het resultaat per bronregel toe in de hoofdmap van je repository. Lever via het portaal je commit en Overdracht.pdf in. Code, low-code en een exporteerbare lokale workflow zijn toegelaten.
