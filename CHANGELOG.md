# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed

- BodemEnOndergrond AP/VOC: PascalCase and CamelCase
- BodemEnOndergrond AP/VOC: Replace abbreviations
- BodemEnOndergrond AP/VOC: Add missing dot at end of sentences
- BodemEnOndergrond AP/VOC: Replace http://schema.org with https://schema.org
- BodemEnOndergrond AP/VOC: Remove empty `ap-usage-note` values
- BodemEnOndergrond AP/VOC: Capitalise sentences
- SensorenEnBemonstering AP/VOC: PascalCase and CamelCase
- SensorenEnBemonstering AP/VOC: Replace abbreviations
- SensorenEnBemonstering AP/VOC: Add missing dot at end of sentences
- SensorenEnBemonstering AP/VOC: Replace http://schema.org with https://schema.org
- SensorenEnBemonstering AP/VOC: Remove empty `ap-usage-note` values
- SensorenEnBemonstering AP/VOC: Capitalise sentences
- ObservatiesEnMetingen AP/VOC: PascalCase and CamelCase
- ObservatiesEnMetingen AP/VOC: Replace abbreviations
- ObservatiesEnMetingen AP/VOC: Add missing dot at end of sentences
- ObservatiesEnMetingen AP/VOC: Replace http://schema.org with https://schema.org
- ObservatiesEnMetingen AP/VOC: Remove empty `ap-usage-note` values
- ObservatiesEnMetingen AP/VOC: Capitalise sentences
- Interpretaties AP/VOC: PascalCase and CamelCase
- Interpretaties AP/VOC: Replace abbreviations
- Interpretaties AP/VOC: Add missing dot at end of sentences
- Interpretaties AP/VOC: Replace http://schema.org with https://schema.org
- Interpretaties AP/VOC: Remove empty `ap-usage-note` values
- Interpretaties AP/VOC: Capitalise sentences
- Observaties AP/VOC: PascalCase and CamelCase
- Observaties AP/VOC: Replace abbreviations
- Observaties AP/VOC: Add missing dot at end of sentences
- Observaties AP/VOC: Replace http://schema.org with https://schema.org
- Observaties AP/VOC: Remove empty `ap-usage-note` values
- Observaties AP/VOC: Capitalise sentences
- Bodem AP/VOC: PascalCase and CamelCase
- Bodem AP/VOC: Replace abbreviations
- Bodem AP/VOC: Add missing dot at end of sentences
- Bodem AP/VOC: Replace http://schema.org with https://schema.org
- Bodem AP/VOC: Remove empty `ap-usage-note` values
- Bodem AP/VOC: Capitalise sentences
- Grondboringen AP/VOC: PascalCase and CamelCase
- Grondboringen AP/VOC: Replace abbreviations
- Grondboringen AP/VOC: Add missing dot at end of sentences
- Grondboringen AP/VOC: Replace http://schema.org with https://schema.org
- Grondboringen AP/VOC: Remove empty `ap-usage-note` values
- Grondboringen AP/VOC: Capitalise sentences
- Grondwatermeetnet AP/VOC: diagram name
- Grondwatermeetnet AP/VOC: PascalCase and CamelCase
- Grondwatermeetnet AP/VOC: Replace abbreviations
- Grondwatermeetnet AP/VOC: Add missing dot at end of sentences
- Grondwatermeetnet AP/VOC: Replace http://schema.org with https://schema.org
- Grondwatermeetnet AP/VOC: Remove empty `ap-usage-note` values
- Grondwatermeetnet AP/VOC: Capitalise sentences
- RuimtelijkeBereiken AP/VOC: PascalCase and CamelCase
- RuimtelijkeBereiken AP/VOC: Replace abbreviations
- RuimtelijkeBereiken AP/VOC: Add missing dot at end of sentences
- RuimtelijkeBereiken AP/VOC: Replace http://schema.org with https://schema.org
- RuimtelijkeBereiken AP/VOC: Remove empty `ap-usage-note` values
- RuimtelijkeBereiken AP/VOC: Capitalise sentences
- Sonderingen AP/VOC: diagram name
- Sonderingen AP/VOC: PascalCase and CamelCase
- Sonderingen AP/VOC: Replace abbreviations
- Sonderingen AP/VOC: Add missing dot at end of sentences
- Sonderingen AP/VOC: Replace http://schema.org with https://schema.org
- Sonderingen AP/VOC: Remove empty `ap-usage-note` values
- Sonderingen AP/VOC: Capitalise sentences

### Removed

- `ignore` tag of Model:Domain Model:OSLO-Grondboringen:Grondboring
- `ignore` tag of Model:Domain Model:OSLO-Sonderingen:CPT

### Fixed

- Unable to determine the range for attribute Model:Domain Model:OSLO-ObservatiesEnMetingen:RuimtelijkBemonsteringsobject:geometrie.
- Unable to determine the range for attribute Model:Domain Model:OSLO-Generiek:Identificator:toegekendDoor.
- Unable to determine the range for attribute Model:Domain Model:OSLO-Grondwatermeetnet:GrondWaterMonster:aanzuring.

### Added

- Enum Erkenningtype: `ap-definition-nl`
- Enum Bemonsteringsobjecttype: `ap-definition-nl`
- Enum Maaiveldtype: `ap-definition-nl`
- Enum Platformtype: `ap-definition-nl`
- Enum Systeemtype: `ap-definition-nl`
- Enum OutputType: `ap-definition-nl`
- Enum InputType: `ap-definition-nl`
- Enum Bemonsteringsproceduretype: `ap-definition-nl`
- Enum Bemonsteringsdoel: `ap-definition-nl`
- Enum Bemonsteringstype: `ap-definition-nl`
- Enum Observatieproceduretype: `ap-definition-nl`
- Enum Domeinobjecttype: `ap-definition-nl`
- Enum Observatietype: `ap-definition-nl`
- Enum Materiaalklasse: `ap-definition-nl`
- Enum Taalcode: `ap-definition-nl`
- Enum Informatietype: `ap-definition-nl`
- Enum Observatiecontexttype: `ap-definition-nl`
- Enum Monstertype: `ap-definition-nl`
- Enum Classificatie: `ap-definition-nl`
- Enum RelatieLedenType: `ap-definition-nl`
- Enum BetrouwbaarheidType: `ap-definition-nl`
- Enum Adertype: `ap-definition-nl`
- Enum Fossielaard: `ap-definition-nl`
- Enum Fossieltype: `ap-definition-nl`
- Enum GecodeerdeBijmenginghoeveelheid: `ap-definition-nl`
- Enum GecodeerdeHoofdnaamcode: `ap-definition-nl`
- Enum GecodeerdeKleur: `ap-definition-nl`
- Enum SecundairKenmerkType: `ap-definition-nl`
- Enum SedimentaireStructuurType: `ap-definition-nl`
- Enum Tektoniektype: `ap-definition-nl`
- Enum AquiferType: `ap-definition-nl`
- Enum RegimeType: `ap-definition-nl`
- Enum GeotechnischeCoderingBijmengingHoeveelheidType: `ap-definition-nl`
- Enum GeotechnischeCoderingHoofdnaamCodeType: `ap-definition-nl`
- Enum Antropogeenkenmerktype: `ap-definition-nl`
- Enum LithostratigrafischeEenheidtype: `ap-definition-nl`
- Enum Observatietype: `ap-definition-nl`
- Enum Breukcriterium: `ap-definition-nl`
- Enum Bodemmonstertype: `ap-definition-nl` and `definition-nl`
- Enum DiepteIntervalGrensDuidelijkheid: `ap-definition-nl` and `definition-nl`
- Enum DiepteIntervalGrensregelmatigheid: `ap-definition-nl` and `definition-nl`
- Enum DrainageKlasse: `ap-definition-nl` and `definition-nl`
- Enum WrbVersie: `ap-definition-nl` and `definition-nl`
- Enum ExtraClassificatieType: `ap-definition-nl` and `definition-nl`
- Enum WrbReferenceSoilGroup: `ap-definition-nl` and `definition-nl`
- Enum ExtraClassificatieAfgeleidType: `ap-definition-nl` and `definition-nl`
- Enum Fase: `ap-definition-nl` and `definition-nl`
- Enum ClassificatieKunstmatigeGronden: `ap-definition-nl` and `definition-nl`
- Enum Profielontwikkelingsgroep: `ap-definition-nl` and `definition-nl`
- Enum Textuurklasse: `ap-definition-nl` and `definition-nl`
- Enum VarianteProfielontwikkeling: `ap-definition-nl` and `definition-nl`
- Enum Bemonsteringsproceduretype: `ap-definition-nl`
- Enum WrbQualifierType: `ap-definition-nl` and `definition-nl`
- Enum VarianteMoedermateriaal: `ap-definition-nl` and `definition-nl`
- Enum Substraat: `ap-definition-nl` and `definition-nl`
- Enum Bemonsteringsobjecttype: `ap-definition-nl`
- Enum Bemonsteringsdoel: `ap-definition-nl`
- Enum Bemonsteringstype: `ap-definition-nl`
- Enum Bemonsteraartype: `ap-definition-nl`
- Enum Bodemobjecttype: `ap-definition-nl` and `definition-nl`
- Enum MateriaalBekistingtype: `ap-definition-nl` and `definition-nl`
- Enum BoormethodeType: `ap-definition-nl` and `definition-nl`
- Enum Boringdoeltype: `ap-definition-nl` and `definition-nl`
- Enum Grondmonstertype: `ap-definition-nl` and `definition-nl`
- Enum Boringstartpunttype: `ap-definition-nl` and `definition-nl`
- Enum Boringinclinatietype: `ap-definition-nl` and `definition-nl`
- Enum Grondobjecttype: `ap-definition-nl` and `definition-nl`
- Enum LegaleVerschijingsvormtype: `ap-definition-nl`
- Enum Boortype: `ap-definition-nl`
- Enum Materiaalklasse: `ap-definition-nl`
- Enum Opmetingmethode: `ap-definition-nl`
- Enum Piëzometertype: `ap-definition-nl` and `definition-nl`
- Enum Meetnettype: `ap-definition-nl` and `definition-nl`
- Enum PutNaBestemming: `ap-definition-nl` and `definition-nl`
- Enum PutSoort: `ap-definition-nl` and `definition-nl`
- Enum Putsleutel: `ap-definition-nl` and `definition-nl`
- Enum Pompstatus: `ap-definition-nl` and `definition-nl`
- Enum Piëzometertoestand: `ap-definition-nl` and `definition-nl`
- Enum Materiaal: `ap-definition-nl` and `definition-nl`
- Enum Peilputafwerkingmateriaaltype: `ap-definition-nl` and `definition-nl`
- Enum Referentiepunttype: `ap-definition-nl` and `definition-nl`
- Enum Piëzometeronderdeeltype: `ap-definition-nl` and `definition-nl`
- Enum Opvulling: `ap-definition-nl` and `definition-nl`
- Enum Grondwaterobjecttype: `ap-definition-nl`

## 2025-09-19

Algemeen
Aanpassingen AP+VOC RuimtelijkeBereiken versie 2024-04-15
AP+VOC Observaties en Metingen versie 2022-04-28,
AP+VOC Sensoren en Bemonstering versie 2022-04-28,
AP+VOC Bodem en Ondergrond versie 2022-04-28,
AP+VOC Grondboringen versie 2023-04-01,
AP+VOC BO_Observaties versie 2023-04-01
 en AP BO_Interpretaties versie 2023-04-01:
- KwantitatieveWaarde werd vervangen door Maat.
- Verwijzingen naar het AP RuimtelijkeBereiken zijn toegevoegd.
- Literal vervangt GetypeerdeString als datatype.
- Er wordt nu duidelijk onderscheid tussen redefine & subset gemaakt.
- De uri van het oorspronkelijk attribuut of rol wordt behouden bij een redefine.
- Typo's in samenvattingen, definities, gebruiksnota's verbeterd.
- LangString vervangt Taalstring als datatype.
- GeneriekeNaam als datatype van specifieke attributen vervangen door skos:Concept of Literal al naargelang.
- NaamInNaamRuimte is als datatype van specifieke attributen vervangen door skos:Concept.
Specifieke aanpassingen:
Aanpassingen AP+VOC RuimtelijkeBereiken versie 2024-04-15:
- Ontbrekende onderdelen aan de specificatie toegevoegd: samenvattingen, definities, uri's.
- Aanpassingen AP+VOC Observaties en Metingen versie 2022-04-28:
- Klasse Domeinobject toegevoegd
- Attribuut Opmeting.opnamedatum toegevoegd aan het AP+VOC Generiek.
Aanpassingen AP+VOC Observaties en Metingen versie 2022-04-28:
Aanpassingen AP+VOC Sensoren en Bemonstering versie 2022-04-28:
- Formaat en Dimensie nu in het AP+VOC Generiek gedefinieerd.
Aanpassingen AP+VOC Bodem en Ondergrond versie 2022-04-28:
- Fractiemeting.meetpunt geschrapt, overbodig want bvb cummulatieve Korrelverdeling kan ook met Fractiemetingwaarde.meetpuntOndergrens/bovengrens worden beschreven.
- Interval toegevoegd als subklasse van ProfielElement + Laag is nu subklasse van Interval.
- Definitie van Laag verduidelijkt.
- Associatie Profiel->Profielelement is veranderd van composiet naar aggregaat.
- Datatype van BO_RuimtelijkBemonsteringsobject.diepte vervangen door Maat.
Aanpassingen AP+VOC Grondboringen versie 2023-04-01:
- Kardinaliteit Grondmonster.type vaar 0..* ipv 0..1 om meerdere classificaties toe te laten.
- Domeinobject en Object terug aan het diagram toegevoegd.
- Bemonstering.bemonsterdObject terug naar Object ipv Grondobject.
- Beperking van Grondboringen tot boringen voor Bemonstering toegevoegd aan gebruiksnota.
- Datatype van Boorgat.diepte vervangen door Maat.
Aanpassingen AP+VOC BO_Observaties versie 2023-04-01:
- Ontbrekende definities aan de specificatie toegevoegd.
- Korrelverdeling.onderbrekingVan en Korrelverdeling.onderbrekingTot geschrapt, gedekt door Fractiemeting.meetpuntOndergrens/bovenGrens.
- Korrelverdeling.humusKalkVerwijderd omdat er ook nog andere parameters zijn en ze allemaal dmv Observatie/Observatieprocedure.parameter kunnen worden beschreven.
- Samendrukbaarheidstrap.hoogte vervangen door Samendrukbaarheidstrap.samendrukking omdat er nog andere maten voor samendrukking bestaan dan hoogte (vh Monster na uitgeoefende druk).
- Samendrukbaarheidsproef.diameter/initiëleHoogte/massa verwijderd omdat er ook nog andere parameters zijn en ze allemaal dmv Observatie/Observatieprocedure.parameter kunnen worden beschreven.
- Schuifweerstandsproef en Schuifweerstandskarakteristieken zijn nu gemodelleerd als Meting ipv als Meetreeks.
- Ipv associaties tussen de Schuifweerstandskarakteristieken en de Schuifweerstandsproeven waarop deze gebaseerd zijn de proeven nu verzameld in een observatieverzameling Schuifweerstandsproefreeks.
- Deze reeks vormt de input van de observatieprocedure Schuifweerstandskarakteristiekenprocedure.
Aanpassingen AP+VOC BO_Interpretaties versie 2023-04-01:
- AntrogeneKenmerkenInterpretatie generiek uitgewerkt.

2024-11-07 - Aliginatie met toolchain 4.0
Context: toolchain 4.0 stelt bijkomende eisen aan het UML model.
De wijzigingen die hieronder zijn opgenomen zijn technische wijzigingen die geen invloed op de semantische inhoud van de specificaties.
Echter deze wijzigingen zorgen wel voor een kwaliteitsverbetering van het master data model.

De volgende aanpassingen zijn gebeurd:
- verwijder template files die niet gebruikt worden
- verwijder configfiles met duplicate informatie
- opsplitsing vocabularium en applicatieprofile EAPs: 2 nieuwe afgeleide EAPs zijn gemaakt.
- verwijder sonderingen van beide (bij overstap naar master moeten we de oorsprokelijke versie blijven gebruiken voor sonderingen)
- range geometrie in PuntWaardePaar connecteer met datatype Punt uit generiek (link was broken)
- verwijder uit grondboringen dubbele klasse grondboring en copies van klassen.
- RDF file generator gaf een definitie tekort aan voor eigenschap coordinaatreferentiesysteem van Bereik
- SHACL file generator gaf een definitie tekort aan voor eigenschap coordinaatreferentiesysteem van Bereik
- typo fix in definitie eigenschap domeinOmvang van klasse Bereik.
- verwijder eigenschap coordinatiereferentiesysteem tussen de klasse Bereik en CRS. Deze was niet correct gedefinieerd en kwam niet voor in toolchain 3 outcome.
- herlinken van range Geometrie van verschillende eigenschappen.
- herlinken van range locatie in verschillende eigenschappen.
- herlinken van range Agent in eigenschap toegekendDoor
- herlinken van range Punt in verschillende eigenschappen
- eigenschap metadata verwijderd omdat die niet bestaat in html (bestaat wel als rol)
- verwijder benoemde eigenschappen die als algemene associatie zijn opgenomen om de overeenkomst met ISO te documenteren maar niet uitgewerkt zijn.
  De eigenschappen zijn beschikbaar door hun rol, die wel opgenomen zijn in de html. Het zijn Ontwerp, Domein, Fenonmeen, Intentie
- verwijder de hulppakket referenties op de diagramma van Sensoren en Bemonstering. Dit zorgt voor duplicaten.
  De enige toevoeging is een verwijzing naar het AP observaties en metingen in de usage note.
  Deze referentie kan terug toegevoegd worden indien men de hulppakket klassen gebruikt voor alle referenties in het model.
  Bemonsteringsvlak, Bemonsteringspunt, Bemonsteringscurve, proces, procedure, Bemonsterings3Dobject, Bemonsteringsproces, Bereik
- voeg een definitie toe aan Opmetingmethode

Todo bij een rollout toolchain 4.0: het verwijderen van de verborgen relatie Intentie. Deze komt niet in het model voor maar zit achterliggend nog in de file.

2024-11-07 - Aliginatie met erkenningsvraag WG Datastandaarden 7/11/2024
- aanpassing datums naar datum finale webinar 1/10/2024.
