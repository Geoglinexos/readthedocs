Pack Oracle
===========

***********
Description
***********

*Checks pour les bases de données Oracle*

********
Services
********


Oracle-$KEY$-connection-time 
        - Connexion à Oracle
        - SNMP

~~~~~~~~~

.. note:: Il existe de nombreux checks pour Oracle, regroupés en sous-ensemble sur différents templates d'hôte. Ci dessous sont listés les principaux.

oracle
	6 Checks élémentaires sur l'état et les performances d'Oracle

oracle-datafiles
	2 Checks sur l'existence et le traffic des fichiers de données

oracle-redo
	3 Checks sur les fichiers de log redo

oracle-rollback-segment
        5 Checks sur les objects Rollback Segment

oracle-sga
	7 Checks sur la partie mémoire System Global Area 

oracle-tablespace
	3 Checks sur les espaces de stockage "tablespace"

oracle-usage
	2 Checks sur les sessions et utilisateurs

.. note:: templates d'hôtes comprenant 1 check chacun.
	  Ils permettent la supervision des espaces de stockages FRA et PGA, l'utilitaire RMAN, les ratios de soft parse et statistiques d'erreur.

===============================
Template d'hôte
===============================
oracle-flash-recovery-area 
oracle-pga-in-memory-sort-ratio 
oracle-rman
oracle-soft-parse
oracle-stale-statistics
===============================

