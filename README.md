# 📘 Simulation de la probabilité de ruine

## Objectif
Simuler la probabilité de ruine d’un assureur avec le modèle de Cramér–Lundberg et étudier l’effet de la réassurance.

## Contenu
- Implémentation du modèle de Cramér–Lundberg :
  R(t) = u + ct - Σ X_i
- Simulation Monte-Carlo de trajectoires de réserve.
- Estimation de la probabilité de ruine.
- Étude de scénarios avec réassurance (quota-share, stop-loss).
- Visualisations des trajectoires et probabilités.

## Technologies
- Python : numpy, matplotlib

## Résultats attendus
- Estimation de la probabilité de ruine selon capital initial et politique de primes.
- Illustration de l’impact de la réassurance.

## Compétences mises en avant
- Simulation stochastique
- Gestion du risque assurantiel
- Application de la théorie du risque

## Sources de données
- Projet basé sur simulation → données générées artificiellement
- Références théoriques : [ISFA – Modèle Collectif](http://www.ressources-actuarielles.net/EXT/ISFA/fp-isfa.nsf/34a14c286dfb0903c1256ffd00502d73/d084f3c15c3ea6fbc1256f15001f03fb/$FILE/ModeleCollectif.pdf)  
