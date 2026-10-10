# Simulateur de devis d'entretien

Application web pour chiffrer l'entretien de climatisation, pompes à chaleur, panneaux solaires et ballons thermodynamiques.

## Règles métier
- Entretien **annuel** pour toutes les clim et PAC (offre commerciale).
- Au-delà de 4 kW, le minimum légal est tous les 2 ans — affiché comme information, mais l'offre reste annuelle.
- Panneaux solaires : annuel avec nettoyage, tarif au panneau.
- Ballon thermodynamique : tous les 2 ans pour le contrôle d'anode.
- Mode invité : devis sans données client.
- Mode client : le visiteur remplit le formulaire sur le site, le devis revient par email.

## Tarifs milieu de marché (TTC)
- Clim monosplit : 130 €
- Clim multisplit : 180 €
- PAC air-air : 175 €
- PAC air-eau : 225 €
- Panneaux solaires : 15 € / panneau
- Ballon thermodynamique : 175 €

## TVA
- Entretien courant (clim, PAC, ballon) : 20 %
- Panneaux solaires : 5,5 %

## Automatisations
- Rappel quotidien à 8h : appareils dont l'entretien tombe dans les 30 prochains jours.
- Envoi automatique du devis finalisé à contact@pyrenees-energie-solution.fr.