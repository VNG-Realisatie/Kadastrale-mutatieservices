---
layout: page-with-side-nav
title: Opdrachtgeverschap StUF-koppelvlak Kadastrale mutatieservices
---
# Opdrachtgeverschap StUF-koppelvlak Kadastrale mutatieservices

Het koppelvlak is toepasbaar voor meerdere referentiecomponenten (zie onder 'Overzicht' en 'Techniek') en daarmee voor meerdere softwarepakketten (zie onder 'ICT-aanbod'). Voor de van toepassing zijnde softwarepakketten dient de aanwezigheid en juiste werking van het koppelvlak geborgd te worden.

## Advies m.b.t opdrachtverstrekking/pakketselectie door gemeente
Voor het voldoen aan deze koppelvlakstandaard neemt een gemeente in haar programma van eisen of opdracht de volgende eisen op:
1. De aangeboden applicatie ondersteunt de services, zoals in het StUF-koppelvlak ‘Kadastrale mutatieservices’ beschreven, voor zover dat bij de rol van die applicatie binnen dit koppelvlak hoort. De leverancier onderbouwt dit door te vermelden welke [referentiecomponent(en)](./Overzicht#referentiecomponenten) door de applicatie word(t)(en) ingevuld en te verklaren dat de daarbij behorende services ondersteund worden.
2. De leverancier beschrijft expliciet of er beperkingen zijn t.a.v. de verstrekking en/of verwerking van de Kadastrale mutatieservices voor de aangeboden applicatie cq. voor de daardoor ondersteunde referentiecomponent(en).<br/<br/>
Indien de gewenste applicatie (ook) de component BRK-Adapter betreft (m.n. transformatie van BRK Levering naar Kadastrale mutatieservices), dan is tevens de volgende eis van toepassing:
3. De aangeboden applicatie ondersteunt de transformatie van BRK Levering naar Kadastrale mutatieservices overeenkomstig de specificaties in het StUF-koppelvlak ‘Kadastrale mutatieservices’.

## Borging dat het koppelvlak ook daadwerkelijk wordt geleverd
VNG Realisatie heeft de [Handreiking leverings- en acceptatievoorwaarden ICT](documenten/130131_Leverings_en_acceptatievoorwaarden_versie_2_Definitief.pdf) opgesteld. Dit document biedt u een set van artikelen die u geheel of gedeeltelijk kunt inweven in eigen inkoop- en acceptatievoorwaarden ICT. Hiermee borgt u dat in de uitvraag expliciet wordt gevraagd om het leveren van de standaard en het voldoen aan de compliancy. Meer informatie hierover leest u op de pagina's <span style="color:red">ICT-opdrachtgeverschap</span> op de VNG Realisatie-website en [Inkoopondersteuning](https://www.softwarecatalogus.nl/purchase-support) in de GEMMA Softwarecatalogus.

## Te maken afspraken bij implementatie
Voor een goede implementatie van de koppelvlakstandaard is het relevant te bepalen van welke services op welke wijze voor een desbetreffende applicatie gebruik gemaakt gaat worden. Over de volgende onderwerpen moeten voor de implementatie afspraken worden gemaakt. Deze lijst is niet limitatief.
* Worden door de applicatie alleen enkelvoudige berichten of alleen samengestelde ([gebeurtenis](./Overzicht#gebeurtenissen)) berichten verwerkt? De BRK-adapter-applicatie levert beide, in Gegevensdistributie moet per service-afnemende applicatie ingesteld worden welke van beide verwerkt wordt.
* Indien alle services-afnemende applicaties alleen enkelvoudige berichten of alleen samengestelde ([gebeurtenis](./Overzicht#gebeurtenissen)) berichten verwerken, kan dan de BRK-adapter-applicatie zo ingesteld worden dat deze alleen één van beide berichttypen levert?
* De BRK Levering en daarmee de Kadastrale mutatieservices bevatten natuurlijke en niet-natuurlijke personen, en gegevens daarvan, die in de gemeentelijke informatievoorziening of in de verwerkende applicatie wellicht al bekend zijn. Bepaald moet worden hoe om te gaan met door het Kadaster geleverde afwijkende waarden van gegevens van bij de gemeente reeds geregistreerde personen. Meest voor de hand liggend is een keuze tussen ‘negeren’ en ‘melden’. In het tweede geval is het aan de desbetreffende functioneel beheerder om per geval te beoordelen hoe daar mee om te gaan.
* De BRK Levering en daarmee de Kadastrale mutatieservices bevatten naast BAG-adressen ook niet-BAG-conforme adressen van de locaties van kadastrale objecten. Bepaald moet worden hoe om te gaan met, door het Kadaster geleverde, afwijkende adresgegevens van een BAG-object en met een niet in de BAG voor komend adres. Meest voor de hand liggend is een keuze tussen ‘negeren’ en ‘melden’. In het tweede geval is het aan de desbetreffende functioneel beheerder om per geval te beoordelen hoe daarmee om te gaan. Dat zou bijvoorbeeld kunnen leiden tot een terugmelding op de BRK.