# THÈSE PROFESSIONNELLE MS X-HEC ENTREPRENEURS 2025

**L'implémentation de l'IA en France : paradoxes, résistances et stratégies entrepreneuriales**  
*Le cas Luwai*

---

**Auteur :** Samir Fernando FLORIDO POKA  
**Programme :** MS X-HEC Entrepreneurs 2025  
**Directeur de thèse :** À définir  
**Date :** 23/09/2025

---

# I. ÉLÉMENTS PRÉLIMINAIRES

## Préface

> *"Il y a deux types d'entreprises : celles qui s'adaptent à l'IA et celles qui disparaissent."*  
> — Jensen Huang, CEO de NVIDIA

L'intelligence artificielle représente aujourd'hui l'une des transformations technologiques les plus profondes de notre époque. Pourtant, en France, cette révolution semble avancer à deux vitesses : d'un côté, un écosystème startup dynamique et des avancées réglementaires pionnières avec l'IA Act européen ; de l'autre, des PME-ETI qui peinent à concrétiser le potentiel de ces technologies dans leur quotidien opérationnel.

Cette thèse prend racine dans un **choc culturel personnel** vécu lors d'un échange de trois mois à San Francisco. En tant qu'ingénieur polytechnicien immergé dans l'écosystème de la Silicon Valley, j'ai été témoin d'une adoption massive et naturelle de l'IA dans tous les secteurs. Appels d'offres automatisés, due diligences accélérées, créations de contenu optimisées : l'IA était omniprésente, pas comme une technologie futuriste, mais comme un outil de productivité aussi banal qu'Excel.

Le contraste a été saisissant à mon retour en France. Malgré notre excellence technologique et notre écosystème d'innovation reconnu, j'ai découvert un gap considérable entre le **potentiel théorique** de l'IA et son **adoption effective** dans le tissu économique français. Cette observation m'a conduit à créer Luwai en 2025, avec pour mission de transformer les entreprises françaises d'*"AI-curious"* à *"AI-productive"*.

Cette thèse documente ce parcours entrepreneurial tout en analysant les mécanismes profonds qui expliquent les résistances à l'adoption de l'IA en France. Elle s'appuie sur **63 entretiens** menés avec des prospects et clients, **5 propositions commerciales** réelles, et l'expérience concrète de construction d'un modèle d'affaires dans ce secteur émergent.

L'angle adopté est résolument **entrepreneurial** : comment transformer les résistances identifiées en opportunités de création de valeur ? Comment construire un pont entre l'innovation technologique et les besoins opérationnels des dirigeants français ?

Au-delà de l'analyse académique, cette thèse se veut un guide pratique pour les entrepreneurs souhaitant s'engager dans l'accompagnement à la transformation par l'IA, ainsi qu'un outil de réflexion pour les dirigeants de PME-ETI confrontés à ces enjeux.

## Remerciements

Cette thèse n'aurait pas pu voir le jour sans le soutien et la contribution de nombreuses personnes que je tiens à remercier chaleureusement.

**À l'équipe Luwai,** mes cofondateurs et collaborateurs qui partagent cette vision de démocratisation de l'IA en France. Merci en particulier à Miguel Adolf Torres pour son expertise technique complémentaire et sa vision stratégique.

**Aux 63 prospects et clients** qui ont accepté de partager leur temps et leur vision lors des entretiens qui constituent le cœur empirique de cette recherche. Votre franchise et votre ouverture ont permis de dresser un diagnostic précis des enjeux d'adoption de l'IA dans le tissu économique français.

**À la communauté MS X-HEC Entrepreneurs,** promotions 2024 et 2025, pour les échanges enrichissants et les remises en question constructives tout au long de ce parcours. L'émulation collective a été un moteur essentiel de cette réflexion.

**À nos premiers clients et partenaires** - Aesio, Antilogy, Intégrhale, Carecall, Tectona - qui nous ont fait confiance pour les accompagner dans leur transformation et ont validé par leurs résultats la pertinence de notre approche.

**Aux mentors et advisors** qui ont contribué à affiner la vision stratégique de Luwai et ont nourri les réflexions présentées dans cette thèse.

**À l'École Polytechnique et HEC Paris** pour la richesse de leurs enseignements et l'ouverture sur l'écosystème entrepreneurial qui ont rendu possible ce projet.

Cette thèse est le fruit d'un apprentissage collectif autant qu'individuel. Elle témoigne de la puissance de l'écosystème français d'innovation quand il sait combiner excellence académique et pragmatisme entrepreneurial.

---

# II. INTRODUCTION

## Contexte et enjeux

La France se trouve aujourd'hui dans une position paradoxale face à l'intelligence artificielle. D'un côté, notre pays dispose d'atouts indéniables : un écosystème de recherche reconnu mondialement avec l'INRIA et des laboratoires d'excellence, un tissu de startups dynamique qui a produit des pépites comme Mistral AI ou Hugging Face, et une position de leadership européen dans l'encadrement éthique de l'IA avec l'IA Act.

D'un autre côté, l'adoption effective de l'IA dans le tissu économique français reste contrastée. Selon le baromètre du numérique 2024, si 33% des Français ont utilisé des outils d'IA générative, cette adoption demeure principalement personnelle et sporadique. Dans le monde professionnel, l'écart se creuse entre les grandes entreprises et les PME-ETI qui constituent pourtant l'épine dorsale de notre économie.

Cette situation interpelle d'autant plus que les enjeux sont considérables. L'IA représente un potentiel d'**augmentation de la productivité** de 20 à 40% sur de nombreuses tâches, selon nos observations terrain. Pour une économie française en quête de compétitivité, ces gains de performance ne peuvent être ignorés.

Le **paradoxe français** de l'IA se manifeste à plusieurs niveaux :

**Au niveau technologique :** Nous disposons d'un écosystème d'innovation de premier plan mais peinent à diffuser ces innovations dans le tissu économique.

**Au niveau organisationnel :** Les entreprises françaises excellent dans l'innovation produit mais montrent des résistances culturelles à l'adoption de nouvelles méthodes de travail.

**Au niveau entrepreneurial :** L'écosystème startup français est dynamique mais les services d'accompagnement peinent à adresser efficacement le segment des PME-ETI.

C'est dans ce contexte que s'inscrit la création de Luwai et l'expérience entrepreneuriale qui nourrit cette thèse. En tant qu'ingénieur polytechnicien ayant vécu l'adoption naturelle de l'IA dans la Silicon Valley puis confronté aux résistances françaises, j'ai identifié une opportunité de création de valeur dans l'accompagnement des entreprises françaises vers une utilisation productive de l'IA.

## Problématique centrale

Cette thèse s'articule autour d'une question fondamentale :

> **Comment expliquer l'écart entre le potentiel de l'IA et son adoption effective dans les PME-ETI françaises, et quelles stratégies entrepreneuriales permettent de transformer ces résistances en opportunités de création de valeur ?**

Cette problématique centrale se décline en trois sous-questions opérationnelles :

1. **Quelles sont les résistances spécifiques** à l'adoption de l'IA dans les PME-ETI françaises et comment se manifestent-elles selon les secteurs et les profils d'entreprises ?

2. **Comment construire un modèle d'affaires viable** pour accompagner ces entreprises dans leur transformation, en naviguant entre les contraintes de scalabilité et les besoins de personnalisation ?

3. **Quels leviers entrepreneuriaux et managériaux** permettent d'accélérer l'adoption de l'IA et de maximiser son impact opérationnel ?

L'angle entrepreneurial adopté dans cette thèse permet d'aborder ces questions sous un prisme résolument pratique, alimenté par l'expérience concrète de construction et de développement de Luwai.

## Objectifs de recherche

Cette recherche vise quatre objectifs principaux :

### 1. Cartographier l'écosystème et la chaîne de valeur IA en France
Identifier les acteurs clés, analyser leurs interactions et comprendre les flux de valeur dans l'accompagnement à l'adoption de l'IA, en particulier pour les PME-ETI.

### 2. Identifier les résistances organisationnelles et culturelles spécifiques
Développer une taxonomie opérationnelle des freins à l'adoption de l'IA, en distinguant les résistances techniques, organisationnelles, culturelles et économiques propres au contexte français.

### 3. Analyser le modèle entrepreneurial Luwai comme cas d'étude
Documenter et analyser l'évolution du modèle d'affaires Luwai, de sa génèse à ses pivots stratégiques, pour en extraire des apprentissages généralisables sur l'entrepreneurship dans ce secteur.

### 4. Formuler des recommandations pour entrepreneurs et décideurs
Proposer des frameworks pratiques et des recommandations actionnables pour les entrepreneurs souhaitant se positionner sur ce marché et les dirigeants de PME-ETI engagés dans leur transformation IA.

## Méthodologie

Cette recherche adopte une **approche mixte** combinant rigueur académique et pragmatisme entrepreneurial. Elle s'appuie sur trois piliers méthodologiques complémentaires :

### Revue de littérature académique et professionnelle
- Modèles classiques d'adoption technologique (TAM, UTAUT)
- Littérature sur l'innovation disruptive et l'entrepreneurship technologique  
- Analyses sectorielles et rapports professionnels sur l'IA en France

### Étude de cas entrepreneurial
- Documentation de la genèse et du développement de Luwai
- Analyse de l'évolution du modèle d'affaires et des pivots stratégiques
- Observation participante en tant que CEO-fondateur

### Collecte de données primaires
La richesse empirique de cette recherche repose sur une collecte de données extensives menée entre juin et août 2025 :

**63 entretiens prospects** menés via cold calling avec un taux de conversion de 20,6% (13 rendez-vous obtenus). Les secteurs représentés sont diversifiés : conseil (32%), industrie (25%), services (21%), tech (15%), finance (7%).

**5 propositions commerciales réelles** analysées en détail : Aesio (focus productivité créative, 3200€), Antilogy (gouvernance et alignement équipe, 3500€), Intégrhale (automatisation métier recrutement, 2600€), Carecall (lead generation automatisée, 2500€), Tectona (audit vertical + formation, 3500€).

**Observation directe** des interactions commerciales, des cycles de vente et de l'évolution des besoins clients sur 9 mois d'activité.

La méthode d'analyse combine codage thématique des entretiens, identification des patterns récurrents et mapping des cas d'usage émergents. Cette approche permet de lier observations terrain et cadres théoriques pour produire des insights actionnables.

## Plan et contributions attendues

Cette thèse s'organise en quatre parties principales :

**Partie III :** Revue de littérature et cadre théorique (10-15 pages) - Fondements académiques de l'adoption technologique et spécificités du contexte français

**Partie IV :** Diagnostic terrain - résistances et opportunités (15-20 pages) - Analyse empirique des freins et leviers identifiés via les 63 entretiens

**Partie V :** Cas d'étude Luwai (15-20 pages) - Documentation du modèle entrepreneurial et de son évolution

**Partie VI :** Recommandations et perspectives (10-12 pages) - Frameworks pratiques et implications pour l'écosystème

Les **contributions attendues** se situent à trois niveaux :

**Contribution empirique :** Première étude qualitative approfondie sur les résistances à l'IA dans les PME-ETI françaises, avec une taxonomie opérationnelle des freins et leviers d'adoption.

**Contribution théorique :** Extension des modèles classiques d'adoption technologique au contexte spécifique de l'IA et développement d'un framework "Formation-Conseil-Delivery" pour les services B2B.

**Contribution managériale :** Guide pratique d'évaluation des opportunités IA pour les dirigeants et recommandations stratégiques pour les entrepreneurs du secteur, avec des métriques ROI documentées et des indicateurs de performance.

Cette approche vise à combler le gap entre la recherche académique sur l'adoption technologique et les besoins concrets des praticiens confrontés aux enjeux d'implémentation de l'IA dans leurs organisations.

---

*Cette introduction pose les bases d'une recherche qui se veut autant académique que pratique, nourrie par l'expérience entrepreneuriale concrète et orientée vers la production d'insights actionnables pour l'écosystème français de l'IA.*
