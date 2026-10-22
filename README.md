# Base de données des pays du monde

Ce dépôt contient monde.db, une base SQLite destinée à la consultation et aux exercices SQL.

## Contenu

La base contient des informations sur 195 pays : capitales, continents, population, dirigeants, langues, monnaies, organisations internationales, superficies et indicateurs.

Tables : APPARTENANCES, DIRIGEANTS, INDICATEURS, LANGUES, MONNAIES, NATION_LANGUES, NATION_MONNAIES, NATIONS, ORGANISATIONS et SUPERFICIES.

Les précisions sur les sources sont conservées dans les colonnes source des tables INDICATEURS et SUPERFICIES.

## Sources

- Les données de superficie mentionnent mledoze/countries (https://github.com/mledoze/countries), sous licence ODbL 1.0.
- Certains indicateurs économiques et démographiques proviennent de la Banque mondiale, World Development Indicators (https://databank.worldbank.org/source/world-development-indicators), pour 2024. Les codes concernés incluent NY.GDP.MKTP.CD et SP.DYN.LE00.IN.
- Les autres sources sont précisées dans la base lorsque disponibles.

## Ouvrir la base

Télécharge monde.db puis ouvre-le avec SQLite, par exemple avec DB Browser for SQLite ou l’extension SQLite de VS Code.
