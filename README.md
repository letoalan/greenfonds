# greenfonds
Tool for cop simulations
🌍 Répartition des Fonds Verts pour le Climat

Ce projet propose une simulation interactive de la répartition des contributions internationales au Fonds Vert pour le Climat, en tenant compte de la population, de la pauvreté et de la vulnérabilité des pays. L'interface permet de tester des scénarios de redistribution en fonction des montants engagés par différents pays.
🚀 Fonctionnalités

    Interface responsive et intuitive 100% HTML/JS/CSS

    Entrée manuelle des contributions par pays

    Répartition automatique des fonds selon une logique de priorité :

        50% du total est réservé au "Reste du monde"

        Priorité donnée aux pays les plus pauvres et les plus vulnérables

        Les pays favorisés reçoivent au maximum 1% du fonds total proportionnellement à leur population

    Mise à jour en temps réel des allocations

    Tableau attractif et lisible sur tous types d’écrans

🧮 Logique de répartition

    50 % des fonds vont au "Reste du monde"

    Les 50 % restants sont répartis dans l’ordre de priorité suivant :

        Pays pauvres & très vulnérables

        Pays pauvres & moyennement vulnérables

        Pays émergents & très vulnérables

        Pays émergents & moyennement vulnérables

        Pays favorisés (plafond de 1 % selon population mondiale)

🛠️ Utilisation

    Ouvrez le fichier index.html dans un navigateur moderne.

    Entrez les montants de contribution pour chaque pays.

    Les allocations se mettent automatiquement à jour dans le tableau.

📁 Contenu du dépôt

    index.html : application web complète (HTML, CSS, JavaScript)

    README.md : ce fichier de présentation

📜 Licence

Ce projet est open source sous licence MIT. Vous pouvez le modifier, le redistribuer et l’adapter librement.
🙌 Auteurs

Projet conçu pour des activités de sensibilisation à la justice climatique et à la coopération internationale.
