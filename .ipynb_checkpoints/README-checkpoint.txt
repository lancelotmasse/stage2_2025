Données et scripts permettant de compléter le TP3 du cours de Stage 2 2025!

Le dossier TP3 contient des CSV correspondant aux données météorologiques des stations du Parc de la Gaspésie. Le CSV dummyData comprend des données de température de l'air et du sol sur un site en parois en Colombie-Britannique. Il sert à illustrer le type de figure et de code attendu de vous dans la cadre du TP! 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Quelques infos pertinentes pour les stations météo :

Tous les datetime sont en UTC-5.
Le pluviomètre d’Ernest-Laforce avait des petits problèmes entre le 14-01-2025 et le 22-06-2025. Il fonctionnait, mais bcp d’oscillations. Alors les données de precip pour cette période sont à prendre avec un grain de sel.
Définition des accronymes :
Tam : Température (°C) moyenne de l’heure (une donnée par minute)
TAx : température (°C) max de l’heure
Tan : Température (°C) minimum de l’heure
Tai : température (°C) instantanée (moyenne 2 dernières minutes de l’heure)
Hai : Humidité relative (%)
NSi : Hauteur de neige (cm) = HS
PT : Précipitation totale dans l’heure (pluie ou neige)
Pai : Pression atmosphérique (hPa)
VVi : vitesse vent instantané (km/h)
Vdi : vent direction instantanée (en degrés…0° = Nord, 90° = E, 180° = S, 270° = O)
VVxi : vitesse vent max instantané (km/h)

---------------------------------------------------------------------
Pour dummydata.

Les datetimes sont en UTC-0.
Les colonnes sont nommées par tt_eee_dd_ii ou:
tt = type de mesure
eee = environnement ou la mesure est prise
dd = profondeur du capteur en cm (positif dans le sol, négatif hauteur à partir du sol)
ii = ID unique de la mesure

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Le script desc_climatique permet de produire un graphique de la température de l'air, une rose des vents et un graphique des précipitations horaires\journalières avec les précipitations cumulées.

Le script desc_thermique permet de produire un graphique de la température de l'air et une matrice de la température du sol à partir des données du CSV dummydata

Le script interac_grad permet de produire un graphique de la température de l'air et de calculer le lapse rate aux 3 stations météorologiques ainsi que de changer interactivement la période d'analyse, l'intervalle de resampling et les quantiles utilisées. 

