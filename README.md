# Loans data exploration
## by HAJI Wissal


## Dataset

> Le dataset contient 113937 observations sur les crédits issus de la platforme Prosper, parmi les informations présentes on trouve le statut, le taux d'intérêt et la date d'initiation du crédit, ainsi que des détails sur les créditeurs comme le score de crédit, le salaire et le type d'emploie.
Le dataset peut être trouvé [ici](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv) et la documentation de chaque colonne peut être consulté [ici](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) 


## Summary of Findings

> Lors de l'exploration, on a remarqué d'abord une forte décroissance du taux d'intérêt pour les meilleurs `CreditGrade`, et une décroissance languissante selon les salaires. Ensuite on a trouvé qu' il y avait une différence d'évolution du taux d'intérêt avant et après l'année 2011 et que ceci est dû à la différence entre le nombre des demandes de crédit. On avait aussi une relation avec la durée du crédit tel que plus cette durée est longue plus le taux d'intérêt est important.
On a aussi observé qu'au niveau de la plupart des statuts d'emploiement, à l'exception de `Self-employed`, le taux de crédit diminue pour les salaires élevé, et que pour les entrepreneurs particulièrement les taux de crédits sont plus faible par rapport aux taux des autres statuts sans une une grande différence entre un revenu faible ou élevé.
En ce qui concerne la relation entre les variables, on a remarqué que plus le salaire est élevé plus la proportion des notes faibles diminue. On a aussi une très forte corrélation entre le montant du crédit et le montant payé chaque mois. Finalement on observe aussi que plus le montant est grand plus la période du crédit est plus longue.
On termine avec la relation des variables avec le statut du crédit, les résultats sont les suivants : d'abord plus le salaire est élevé plus la proportion du statut `Completed` augmente et se distingue clairement des proportions des autres statuts. Pour les emploies full-time on a une proportion plus elevé du statut `Defaulted`, en investiguant encore ce cas on s'apperçoit que le statut dans ce cas est aussi influencé par le montant du crédit. On remarque aussi que le statut `Completed` est lié aussi à un score de crédit élevé et un pourcentage de crédits en retard faible.


## Key Insights for Presentation

> Pour la présentation, je me concentrerais sur l'influence de la note du créditeur et le salaire sur le taux d'intérêt, ainsi que le cas du taux d'intérêt pour les entrepreneurs. Pour les relations avec le statut du crédit j'ai choisis de se concentrer sur l'impacte du salaire et du montant de crédit.
Je commence d'abord par introduire les variables taux d'intérêt, statut d'emploiement, note du créditeur, salaire annuel et montant du crédit.Puis, j'utiliserais le diagramme de boite en moustache pour la visualisation de l'impacte de la note du créditeur et le facetage selon les statuts d'emploiement pour illustrer l'impacte du salaire et le cas des entrepreneurs.
Ensuite, je passerais aux relation avec le statut du crédit, et je commencerais par un pie chart des differentes proportions des statuts, ensuite je passerais à l'illustration de l'impacte du salaire avec le diagramme en bar, et l'impacte du montant de crédit avec le diagramme des points.
J'ai changé les couleurs pour quelques graphes, et ajouté le style 'dark-grid' pour améliorer le style des graphes.
