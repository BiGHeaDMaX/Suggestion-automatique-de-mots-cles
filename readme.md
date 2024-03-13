# **Introduction**
Ce projet vise à élaborer un modèle qui permet de prédire des tags définissant le contenu d'un document textuel, dans le contexte de publications sur le site Stack Overflow.<br>
Ce travail est basé sur 50 000 messages et leurs tags associés provenant de Stack Overflow. Les messages ont été récupérés sur le [*StackExchange Data Explorer*](https://data.stackexchange.com/stackoverflow/query/new).

> **Note**<br>
Une API contenant le modèle le plus performant a été développée et déployée sur Azure, le code et le workflow se trouvent dans [ce repository](https://github.com/BiGHeaDMaX/Suggestion-automatique-de-mots-cles-API)

# **Contenu de ce repository**
- **01 - Pré-traitements et Exploration.ipynb** : modalités de récupération des messages, préparation des données et exploration.
- **02 - StackAPI.ipynb** : test de l'API proposée par Stack Overflow pour la récupération des messages.
- **03 - Approche non supervisée.ipynb** : test et évaluation de modèles non supervisés.
- **04 - Approche supervisée.ipynb** : test et évaluation de modèles supervisés.
- **05 - Accès à l'API.ipynb** : exemple d'accès à l'API déployée dans le cloud.
- **06 - Note technique.pdf** : une note technique concernant les approches et outils pour une démarche orienté MLOPS.
- **07 - Présentation.pptx** : support de présentation.