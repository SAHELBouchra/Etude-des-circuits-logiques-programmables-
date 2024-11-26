# Étude des Circuits Logiques Programmables 💡

Ce projet explore et compare les technologies des **CPLD** (Complex Programmable Logic Device) et des **FPGA** (Field Programmable Gate Array), tout en étudiant leurs architectures, leurs avantages, leurs inconvénients, et leurs applications pratiques.

## Plan 📋
1. **Introduction**
2. **CPLD** : Définition, architecture, avantages et inconvénients
3. **FPGA** : Définition, architecture, et utilisation sur le marché
4. **Comparaison** :
   - CPLD vs FPGA
   - Microprocesseur, Microcontrôleur, et FPGA
5. **Langage VHDL**
6. **Étapes d’implémentation d’un circuit sur un FPGA**

## Technologies étudiées 🛠️
- **CPLD** :
  - **Composants** : Portes logiques programmables
  - **Avantages** : Faible consommation, robustesse
  - **Inconvénients** : Limites dans les traitements complexes
- **FPGA** :
  - **Composants** : LUT, CLB, blocs d’I/O, interconnexions
  - **Utilisation** : Matrices logiques configurables pour des tâches parallèles
  - **Avantages** : Flexibilité et reprogrammabilité
  - **Inconvénients** : Consommation énergétique élevée et coût plus important

## Comparaison des technologies 🔍
| **Aspect**            | **CPLD**                      | **FPGA**                       |
|------------------------|-------------------------------|---------------------------------|
| Nombre de portes      | Quelques milliers            | Plusieurs millions             |
| Mémoire               | Non volatile                 | Volatile                       |
| Consommation          | Faible                       | Élevée                         |
| Coût                  | Moins cher                   | Plus coûteux                   |
| Applications          | Petits systèmes logiques     | Systèmes complexes et adaptatifs |

## Étapes d'implémentation sur FPGA 🚀
1. **Écriture du code source** (VHDL ou Verilog)
2. **Compilation et simulation** pour valider le modèle logique
3. **Synthèse** : Traduction du code en configuration matérielle
4. **Placement** : Assignation des blocs logiques sur la puce
5. **Routage** : Définition des connexions entre blocs logiques
6. **Génération du bitstream** : Fichier pour configurer le FPGA
7. **Chargement** sur le FPGA et test final


## Auteurs ✨
- **Imane El Midaoui**
- **Tasnime Amrani Nejjar**
- **Bouchra Sahel**

## Remerciements 💐
Merci à **Dr. Ammour Alae** pour son encadrement et ses conseils tout au long de ce projet.
