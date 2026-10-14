# Le PIB fait-il vivre plus longtemps ? Six pays entre 2000 et 2015

L'argent fait-il la santé ? Pour le savoir, j'ai comparé le PIB et l'espérance de vie à la naissance de six pays entre 2000 et 2015 : le Chili, la Chine, l'Allemagne, le Mexique, les États-Unis et le Zimbabwe. Les données proviennent de l'Organisation mondiale de la santé et de la Banque mondiale.

## Tous les pays vivent plus longtemps

L'espérance de vie a augmenté dans les six pays. Le Zimbabwe est le cas le plus frappant : après une baisse jusqu'en 2004 (environ 44 ans), elle remonte à environ 61 ans en 2015, soit plus de 15 ans de gain. Le pays reste pourtant environ 20 ans sous les cinq autres, qui se situent entre 76 et 81 ans.

![Espérance de vie](images/esperance_vie.png)

## Le PIB, lui, évolue très différemment

Les États-Unis restent largement en tête (de 10 300 à 18 100 milliards de dollars). La Chine connaît la croissance la plus spectaculaire, de 1 200 à 11 000 milliards, et dépasse l'Allemagne vers 2007. La crise de 2009 se voit nettement sur plusieurs courbes.

![PIB](images/pib.png)

## Un lien réel, mais pas proportionnel

Un PIB plus élevé ne garantit pas une vie plus longue : les États-Unis, avec le PIB le plus haut, ont une espérance de vie inférieure à celle de l'Allemagne et du Chili.

![PIB et espérance de vie](images/nuage.png)

Pourtant, dans chaque pays, PIB et espérance de vie progressent ensemble (corrélation d'au moins 0,93). Sur l'ensemble des pays, la corrélation atteint 0,79 une fois le PIB passé en logarithme, contre 0,34 avec le PIB brut. La relation est donc forte mais courbe : pour un pays pauvre, un petit gain de richesse va de pair avec un grand gain d'espérance de vie, alors que pour un pays riche, l'effet est faible.

## Ce qu'il faut retenir

- Le PIB et l'espérance de vie évoluent dans le même sens, surtout à bas niveau de revenu.
- Au Zimbabwe, l'espérance de vie remonte avant le PIB : la richesse seule n'explique pas tout.
- **Corrélation n'est pas causalité.** D'autres facteurs, comme l'accès aux soins, la lutte contre les maladies ou l'éducation, n'ont pas été étudiés.
- Avec seulement six pays, ces résultats ne se généralisent pas. Le PIB par habitant serait plus pertinent pour une comparaison équitable.

*Analyse réalisée avec Python, pandas, seaborn et Matplotlib. Code et données : voir le notebook `life_expectancy_gdp.ipynb`.*