Title: Discussions autour de la durée d'empâtage
Slug: empatage-duree-une-ou-deux-heures
Date: 2016-11-30
Accroche: Questionnement de brasseurs… pourquoi certains empâtent deux heures ?
image: /images/empatage/background.jpg
Author: Alexis
Status: draft

Une question me trotte dans la tête depuis quelques temps, à propos de la durée d'empâtage nécessaire dans la bière. Sans trop expliquer pourquoi, certains brasseurs empâtent pour une durée de 2h, voire un peu plus avec le temps de filtrage, alors que nous empâtons durant une heure avec une assez bonne efficacité.

J'ai donc commencé à chercher l'information, sans trouver tout de suite la réponse à mes questions. On m'avait conseillé la lecture du [Briggs "Brewing science and practice"](http://fars.itvhe.ac.ir/_fars/Documents/99ae7cc8-c9a8-4356-8d24-f6c208322cb7.pdf), j'ai donc commencé à y jeter un oeil.

Pouah, quel voyage ! Ceci est une tentative de déchiffrement du précieux savoir enfermé dans cette "bible".

## Sucres fermentescibles et résiduels

Lors de l'empâtage, l'action que nous connaissons la plus est celle des enzymes alpha et beta amylases, qui permettent de découper les chaînes d'amidon en sucres plus simples fermentescibles (transformés plus tard en alcool par les levures) et non fermentescibles (qui ajoutent du corps à la bière finale).

La question qui se pose alors est : quelle quantité de sucre (fermentescible ou non) est extraite par les enzymes en fonction de la durée et de la température ?

Après quelques recherches, j'ai trouvé deux tableaux qui nous donnent exactement ces informations :

![Potentiel d'extraction](/images/empatage/extraction-time.png)

Dans ce premier tableau, on voit la différence d'extraction en fonction des températures et des temps d'extraction.

Selon nos recettes, nous sommes soit aux alentours de 65°C soit aux alentours de 68°C (ce qui nous approcherait plus des 70°C présents sur le tableau).

La différence d'extraction entre 60mn et 120mn est alors de 0.6% pour les sucres fermentescibles et 0.5% pour les sucres résiduels, autant dire pas grand chose…

Encore plus frappant: la différence entre un empâtage d'une heure et un empâtage de 15mn, selon ce même tableau est quasiment négligeable !

Marshall Scott, de brulosophy, a fait [un test pour voir la différence entre un empâtage de 30mn et un empâtage de 60mn](http://brulosophy.com/2014/09/01/does-mash-length-matter-exbeeriment-results/) sans réellement trouver de différence entre les deux.

Il y a également eu [un test comparant un empatage d'une nuit VS un empatage de 60mn](http://brulosophy.com/2018/01/08/mash-length-overnight-vs-60-minutes-exbeeriment-results/) qui semble montrer qu'il est possible d'extraire plus de sucres en faisant un empâtage toute une nuit.

Certaines brasseries du coin font ça également, et semblent en tirer les mêmes résultats.

## L'impact du temps d’empâtage sur l'extraction des sucres

Il existe plusieurs types de sucres dans la bière, fermentescibles ou non par des saccharomyces cerevisiae:

- le glucose : une seule molécule, fermentescible
- le maltose : deux molécules de glucose liées ensemble, fermentescible
- le maltotriose : trois molécules de glucose liées ensemble, parfois fermentescible
- le maltotetraose : quatre molécules de glucose, non fermentescible
- les dextrines : de 4 à 25 molécules de glucose, non fermentescible
- l'amidon : des structures linéaires ou avec des branches, autour de 1000, non fermentescible

## Azote

Il semble que l'empatâge ait également d'autres vertus, et permette de rendre disponible de l'azote (*PSN: Permanently Soluble Nitrogen*), qui semble permettre la création d'acides aminés, utiles aux levures (qui créent des protéines pour leur survie).

![Potentiel d'extraction avec azote](/images/empatage/extraction-time-nitrogen.png)

On voit ici que la différence entre 60mn et 120mn est de 1.7 %. Sachant que les levures que l'on utilise sont maintenant d'assez bonne qualité et semblent supporter pas mal de conditions un peu *borderline*, je ne pense pas que ces 1.7% d'Azote disponibles en plus fassent toute la différence.

## Désactivation des enzymes

Jules, de la Brasserie Skumenn me disait qu'il était possible que les enzymes se *désactivent* après 2 heures de travail, ce qui pourrait également être une piste intéressante: effectivement si les enzymes se désactivent alors il ne sert à rien de continuer à empâter !

J'ai donc creusé un petit peu sur le sujet

## Ratio et finesse du grain

Il semblerait qu'en fonction du ratio eau/grain utilisé et de la finesse du concassage du grain, un empâtage de deux heures soit nécessaire pour être sûr de convertir tout le sucre disponible dans le malt.

Le plus simple pour en être sûr reste sûrement [le test à l'iode](http://www.braukaiser.com/wiki/index.php?title=Iodine_Test), qui permet de valider que l'ensemble des sucres ont été convertis.


## Ressources

http://howtobrew.com/book/section-3/how-the-mash-works/manipulating-the-starch-conversion-rest, traduction sur https://www.brassageamateur.com/wiki/How_to_brew/Section_3/Chap_14_:_Le_brassage,_comment_%C3%A7a_marche_%3F

> The grist/water ratio is another factor influencing the performance of the mash. A thinner mash of >2 quarts of water per pound of grain dilutes the relative concentration of the enzymes, slowing the conversion, but ultimately leads to a more fermentable mash because the enzymes are not inhibited by a high concentration of sugars. A stiff mash of <1.25 quarts of water per pound is better for protein breakdown, and results in a faster overall starch conversion, but the resultant sugars are less fermentable and will result in a sweeter, maltier beer. A thicker mash is more gentle to the enzymes because of the lower heat capacity of grain compared to water. A thick mash is better for multirest mashes because the enzymes are not denatured as quickly by a rise in temperature.

> As always, time changes everything; it is the final factor in the mash. Starch conversion may be complete in only 30 minutes, so that during the remainder of a 60 minute mash, the brewer is working the mash conditions to produce the desired profile of wort sugars. Depending on the mash pH, water ratio and temperature, the time required to complete the mash can vary from under 30 minutes to over 90. At a higher temperature, a stiffer mash and a higher pH, the alpha amylase is favored and starch conversion will be complete in 30 minutes or less. Longer times at these conditions will allow the beta amylase time to breakdown more of the longer sugars into shorter ones, resulting in a more fermentable wort, but these alpha-favoring conditions are deactivating the beta; such a mash is self-limiting.

> Le ratio grain/eau est un autre facteur influençant l'efficacité du brassage. Une maîsche moins dense, supérieure à 3,5 litres d'eau par kilo de grain, diluera la relative concentration des enzymes, ralentissant la transformation, mais au bout du compte peut mener à un moût plus fermentescible car les enzymes seront moins ralenties par la forte concentration en sucres. Une maîsche plus dense, inférieure à 2,5 litres d'eau par kilo de grain, est meilleure pour la cassure des protéines et résultera en une transformation plus rapide de l'amidon, mais les sucres obtenus sont moins fermentescibles et donneront une bière plus sucrée et maltée. Une maîsche plus épaisse est plus agréable pour les enzymes à cause de la la faible capacité calorifique du grain comparée à celle de l'eau. Une maîsche plus épaisse est mieux adaptée pour les brassages en multipalier car les enzymes ne sont pas si rapidement dénaturées par l'élévation de température.

> Comme toujours, le temps change tout ; c'est le dernier facteur influant sur le brassage. La conversion de l'amidon peut être finalisée en seulement 30 minutes, ainsi durant le temps restant sur un brassage de 60 minutes, le brasseur travaillera sur les conditions nécessaires à la production d'un profil particulier des sucres de son moût. Selon le pH du brassin, le ratio eau/grains et la température, la durée nécessaire pour finaliser le brassage varie entre 30 et plus de 90 minutes. 