---
layout: page-with-side-nav
title: Documentatie StUF-koppelvlak Jeugdzorg (CORV)
folder_files:
  - title: 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v1.0.0_20160601.pdf
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: 
    path: documenten/Voorbeeldberichten-bg-brk.zip
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: 
    path: documenten/15-07-2016Berichtschema_brk.zip
    group: 100
    versie: 1.0.0
    status: Definitief
    omschrijving: 
  - title: 
    path: documenten/StUF_familiecriteria_conformiteit_kadastrale_mutatie-services_0.2.pdf
    group: 100
    versie: 1.0
    status: Definitief
    omschrijving: 
  - title: 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9.1_20160518.pdf
    group: 091
    versie: 0.9.1
    status: In bewerking
    omschrijving: 
  - title: 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9.1_20160518_met_renvooi_tov_9.0.pdf
    group: 091
    versie: 0.9.1
    status: In bewerking
    omschrijving: 
  - title: 
    path: documenten/18-05-2016Berichtschema_brk.zip
    group: 091
    versie: 0.9.1
    status: Ter vaststelling
    omschrijving: 
  - title: 
    path: documenten/Koppelvlak_Kadastrale_mutatieservices_-_Reacties_en_verwerking_consultatie_v0.9_20160518.pdf
    group: 091
    versie: 
    status: Definitief
    omschrijving: 
  - title: 
    path: documenten/Berichtschema_brk.zip
    group: 090
    versie: 0.9
    status: In bewerking
    omschrijving: 
  - title: 
    path: documenten/Koppelvlakspecificatie_Kadastrale_mutatieservices_v0.9_20160201.pdf
    group: 090
    versie: 0.9
    status: In bewerking
    omschrijving: 
  - title: 
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