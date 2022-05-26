# Washington-covid-vaccine-distribution
## La recherche des données :
Suite à mes recherches j’ai uniquement pu trouver des données concernant les vaccins sur les liens https://data.wa.gov/browse.
J’ai fait d’autres recherches personnelles mais je n’ai pas pu trouver d’autres données sur chaque comté qui pourraient intéresser ce cas d’utilisation.
J’ai donc pu baser mon modèle uniquement sur l'âge des personnes et les doses de vaccins prises.
J’aurais souhaité faire mon modèle en me basant non seulement sur l'âge des personnes mais aussi sur les maladies graves (comme le diabète, etc.) afin de produire un modèle plus pertinent. 
## Analyse :
Dans mon modèle, la priorité est pour les personnes qui ont plus de 65 ans et qui ont reçu moins de doses de vaccin (d’abord ceux qui ont eu 1 seule dose et qui devaient faire la deuxième dose, puis ceux qui ont eu 2 doses de vaccin et qui devaient avoir la dose de booster). Ensuite des personnes entre 18 et 65 ans de la même manière.
## Résultat :
Au total sur 1 million de vaccins à distribuer, 319 086 doses sont à distribuer pour des personnes de plus de 65 ans et le reste (680 914 doses) pour des personnes entre 18 et 65 ans.
Je n’ai utilisé aucune technique de Machine Learning mais on pourrait utiliser des algorithmes de plus court chemin afin de trouver un moyen plus rapide pour distribuer les vaccins aux comtés qui ont besoin de plus de doses.
## Modèle :
Vous pouvez constater le modèle obtenu sur une page HTML généré par l’outil Plotly sur lequel vous voyez la carte de l’état Washington et ces comtés. En allant sur chaque comté le nombres de doses de vaccins vont s’afficher en indiquant les 4 paramètres de calcules :
 - Personnes de plus de 65 ans qui doivent avoir la deuxième dose
 - Personnes de plus de 65 ans qui doivent avoir la dose booster
 - Personnes entre 18 et 65 ans qui doivent avoir la deuxième dose
 - Personnes entre 18 et 65 ans qui doivent avoir la dose booster
