===============================
Pack PaloAlto by API Rest
===============================

***********
Description
***********

*Checks pour l'API des équipements Palo Alto*

.. note:: Ces checks passe par l'API Rest des Palo Alto si celle-ci est active. Ils fonctionnent avec un login/password associé à cette API. Le mode "read-only" est préférable pour ce compte.

********
Services
********



Paloalto - Certificat
        - Disponibilité du certificat
        - via XML

~~~~~~

Paloalto - HA Sync
        - Vérification de la synchronisation entre les éléments d'un cluster HA
        - via XML

~~~~~

Paloalto - Health
        - Vérification de l'état du Hardware
        - via XML

~~~~~~

Paloalto - NTP
        - Vérification de la connexion au serveur NTP
        - via XML

~~~~~

Paloalto - VPN Status
        - Statut du VPN
        - via XML
