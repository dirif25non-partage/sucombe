Analyse des données de l'application Sucombe
============================================

.. toctree::
   :hidden:
   :maxdepth: 3

   champsPresta
   preventifs

L'interface de l'application Sucombe permet d'extraire des tables au format CSV pour faire des analyses sur les données enregistrées depuis 2017.
Dans ce document, on se limitera cependant aux données enregistrées depuis l'année 2020 car la manière d'utiliser Sucombe a évolué et l'objectif est d'examiner la situation actuelle.

Il est également possible d'accéder aux tables de la base de données sous-jacente mais cela demande davantage d'effort et on essaiera autant que possible de l'éviter.

L'exploitation des données permet de fournir des analyses pertinentes pour la compréhension de l'activité du département DETT et en particulier sur la maintenance des équipements.
Elle éclaire aussi sur la manière dont l'application Sucombe est utilisée et permet de formuler des actions d'amélioration à ce niveau.

La première table analysée est celle des **prestations** car elle contient des informations assez riches sur l'ensemble des commandes.
Le tableau ci-dessous fournit les nombres de prestations sur la période 2020-23.

.. csv-table:: Nombre de prestations saisies par Service et par an depuis 2020
   :file: _static/servAn.csv
   :widths: 20,  20, 20, 20, 20
   :header-rows: 1


Les :doc:`champs de cette table <champSucombe>` sont les suivants :
``'Action', 'Libellé', 'Identifiant', 'Date création', 'Numméro OT','Ligne d'équipement', 'Type', 'Lieu','Date prév.', 
'Montant prestation HT', 'Montant Constaté HT', 'Marché', 'Agent', 'Service', 'État'``




