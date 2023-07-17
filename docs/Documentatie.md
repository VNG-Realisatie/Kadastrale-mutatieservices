---
layout: page-with-side-nav
title: Documentatie StUF-koppelvlak Jeugdzorg (CORV)
folder_files:
  - title: Kadastrale mutatieservices - Koppelvlakspecificatie 1.0 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v1.0.0_20160601.pdf
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: Kadastrale mutatieservices - Voorbeeldberichten 
    path: documenten/Voorbeeldberichten-bg-brk.zip
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: Kadastrale mutatieservices 1.0.0 - Berichtschemas 
    path: documenten/15-07-2016Berichtschema_brk.zip
    group: 100
    versie: 1.0.0
    status: Definitief
    omschrijving: 
  - title: StUF familiecriteria conformiteit kadastrale mutatie-services
    path: documenten/StUF_familiecriteria_conformiteit_kadastrale_mutatie-services_0.2.pdf
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: Kadastrale mutatieservices - Koppelvlakspecificatie 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9.1_20160518.pdf
    group: 091
    versie: 0.9.1
    status: In bewerking
    omschrijving: 
  - title: Kadastrale mutatieservices - Koppelvlakspecificatie - met wijzigingen tov versie 0.9
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9.1_20160518_met_renvooi_tov_9.0.pdf
    group: 091
    versie: 0.9.1
    status: In bewerking
    omschrijving: 
  - title: Kadastrale mutatieservices 0.9.1 - Berichtschemas 
    path: documenten/18-05-2016Berichtschema_brk.zip
    group: 091
    versie: 0.9.1
    status: Ter vaststelling
    omschrijving: 
  - title: Koppelvlak Kadastrale mutatieservices - Reacties en verwerking consultatie op v0.9
    path: documenten/Koppelvlak_Kadastrale_mutatieservices_-_Reacties_en_verwerking_consultatie_v0.9_20160518.pdf
    group: 091
    versie: 
    status: Definitief
    omschrijving: 
  - title: Kadastrale mutatieservices - Berichtschema's
    path: documenten/Berichtschema_brk.zip
    group: 090
    versie: 0.9
    status: In bewerking
    omschrijving: 
  - title: Kadastrale mutatieservices - Koppelvlakspecificatie 0.9 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9_20160201.pdf
    group: 090
    versie: 0.9
    status: In bewerking
    omschrijving: 
  - title: Kadastrale mutatieservices - Reviewformulier 
    path: documenten/Reactie-formulier_openbare_consultatie_Kadastrale_Mutaties.zip
    group: 090
    versie: 1.0
    status: Definitief
    omschrijving: 
---
# Documentatie StUF-koppelvlak Kadastrale mutatieservices

De actuele versie van het koppelvlak betreft de 1.0.0-versie. Documentatie van eerdere versies en van de wijzigingen die hebben geleid tot de actuele versie zijn verderop onder 'Archief' vermeld.

## Versie 1.0.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 100 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## Versie 0.9.1

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 091 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## Versie 0.9.0

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 090 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>