Ligne d'équipements
-----------------------
Ce champs prend des valeurs qui sont imposées par l'application et qui sont présentées dans une liste de choix. 

Les nombres de prestations depuis 2020 par ligne et par les principaux services sont présentés dans le tableau ci-dessous.

.. csv-table:: Nombre de prestations saisies par Service et par ligne d'équipements
   :file: _static/lgnServ.csv
   :widths: 19,  9, 9, 9, 9, 9, 9, 9, 9, 9
   :header-rows: 1

On a choisi d'ajouter des valeurs du champs **Ligne d'Equipements** qui ne sont pas des lignes d'Equipements comme :
``Controle règlementaire, Sécurité Tunnel, Propreté, Evenementiel`` .

Cela crée une ambiguité sur ce qu'il faut choisir quand on fait le contrôle d'un tableau électrique, par exemple. 
On risque de choisir le champ en lien avec le marché spécifique mais ce n'est alors pas très utile puisque le marché 
utilisé est aussi renseigné dans Sucombe.

Il faudrait donc expliciter la manière d'utiliser ces champs.


