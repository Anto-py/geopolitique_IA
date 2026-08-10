# Géopolitique de l'IA : qui fabrique ces machines

**En ligne : https://anto-py.github.io/geopolitique_IA/**

Carte interactive des assistants d'intelligence artificielle, pour la formation. Elle répond à trois questions, dans cet ordre : d'où vient l'outil, sur quel modèle il repose, et ce qu'il advient des données qu'on lui confie.

Seize acteurs, rangés en deux listes.

- **Les dominants**, dix outils qu'on rencontre partout, six américains, un français, trois chinois.
- **Les alternatives européennes**, six entrées dont chacune porte son statut réel : accessible à tous, modèle sans interface grand public, réservé aux organisations, passé sous contrôle étranger, ou simple aiguilleur vers des modèles tiers.

Chaque fiche porte une pastille disant ce que l'outil fait de vos échanges. Trois régimes : ils entraînent le modèle, ils ne l'entraînent pas, ou ils sont chiffrés au point que l'éditeur lui-même ne peut pas les lire.

## Ce que la carte donne à voir

Deux choses qu'un classement par puissance masque.

La souveraineté se joue à deux étages qu'on confond. Lumo est suisse, chiffré, et l'éditeur ne peut pas lire vos conversations ; mais les modèles qui tournent sur ses serveurs sont chinois. Choisir un outil européen ne garantit pas un modèle européen, cela garantit qui détient vos données.

Une souveraineté s'achète et se ferme. Aleph Alpha, longtemps l'espoir allemand, appartient à une entreprise canadienne depuis avril 2026. HuggingChat a fermé en juillet 2025 avant de revenir en aiguilleur vers cent quinze modèles.

## Utilisation

Aucune installation, un seul fichier. Ouvrir `index.html`, ou servir le dossier :

```bash
python3 -m http.server 8901
```

Un clic sur une entrée de liste, ou sur un marqueur de la carte, ouvre la fiche et déplace la carte sur la ville concernée. Le fond de carte et la bibliothèque Leaflet sont chargés depuis le réseau : prévoir une connexion, ou tester avant la séance.

## Sources

Chaque fiche cite ses sources en bas, sous forme de liens cliquables vers le document d'origine, en privilégiant l'éditeur lui-même pour tout ce qui concerne les données. Le détail de la vérification, son rang de source et ce qui reste à confirmer sont dans `SOURCES.md`.

Les chiffres d'audience ont été retirés : ils n'étaient pas sourçables, vieillissaient en quelques mois, et plusieurs acteurs n'en publient aucun. À leur place, des données stables et vérifiables.

Données vérifiées en août 2026. Ce domaine bouge vite : à revérifier avant chaque séance. Un seul endroit à modifier, le tableau `chatbots` dans `index.html`.
