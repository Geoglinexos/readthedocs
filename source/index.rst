.. Shinken documentation master file, created by
   sphinx-quickstart on Thu Jul  6 11:09:05 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


caliSE
======

catalogue linexos - Shinken Enterprise 
**************************************

Qu'est ce qu'un plugin ?
************************

C'est un exécutable, script ou binaire, qui est interprété par le système d'exploitation en
vu de vérifier l'état d'un élément et de relever des métriques.

Qu'est ce qu'un pack ?
**********************

Un pack sert à regrouper un ensemble de checks spécifiques à un type d'élément supervisable.

Liste des différents packs
**************************

+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|                Packs Shinken Solution         |       |                Packs Linexox                  |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| Nom du pack           | Nombre de checks      |       |Nom du pack            | Nombre de checks      |
+=======================+=======================+=======+=======================+=======================+
| aix                   |            6          |       | arkoon                |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| cisco                 |            6          |       |  aruba_ap             |            3          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| exchange              |            5          |       |  aruba_wlc            |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| hpux                  |            6          |       |  cisco_catalyst       |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  iis                  |            5          |       |  cisco_sg300          |            6          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| ldap                  |            4          |       |  cisco_wlc            |            9          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| linux                 |            8          |       |  dell_force10         |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| mongodb               |            6          |       |  dell_force10_s       |            10         |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  mssql                |            5          |       | dell_powerconnect54xx |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  mysql                |            5          |       | dell_powerconnect62xx |           10          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  oracle               |           34          |       |  fortinet             |            8          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  switch               |            3          |       |  hp_procurve          |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  vmware               |           10          |       |  motorola_rfs6000     |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|  windows              |            8          |       |  palo_alto            |           15          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|                       |                       |       |  palo_alto_api        |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|                       |                       |       |  stormshield_sn       |            9          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+




.. note:: Les noms de check qui comportent "$KEY$" changent en fonction de l'argument correspondant (les "$KEY$" seront remplacés par l'argument, voir  `duplicate_foreach`_).
.. _duplicate_foreach: http://151.80.162.119:8090/pages/releaseview.action?pageId=80120248 


.. toctree::
   :maxdepth: 5
   :caption: Table of Contents
   :titlesonly:
   :hidden:

   self
   shinken_solution/shinken_solution
   linexos/linexos   



.. Indices and tables
   ==================

   * :ref:`genindex`
   * :ref:`modindex`
   * :ref:`search`
