.. Shinken documentation master file, created by
   sphinx-quickstart on Thu Jul  6 11:09:05 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

###################################
Catalogue Linexos - Plugins Shinken 
###################################

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

.. Hyperlink pour les packs Linexos

.. .. _arkoon: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/arkoon.html
.. .. _dell_powerconnect54: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_powerconnect54XX.html
.. .. _dell_powerconnect62: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_powerconnect62XX.html
.. .. _aruba_ap: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/aruba_ap.html
.. .. _aruba_wlc: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/aruba_wlc.html
.. .. _cisco_catalyst: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_catalyst.html
.. .. _cisco_sg300: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_sg300.html
.. .. _cisco_wlc: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_wlc.html
.. .. _dell_force10: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_force10.html
.. .. _dell_force10_s: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_force10_s_series.html
.. .. _fortinet: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/fortinet.html
.. .. _hp_procurve: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/hp_procurve.html
.. .. _motorola_rfs6000: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/motorola_rfs6000.html
.. .. _palo_alto: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/palo_alto.html
.. .. _palo_alto_api: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/palo_alto_api.html
.. .. _stormshield_sn: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/stormshield_sn.html

.. Hyperlink pour les pack Shinken Solution
.. .. _aix: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/aix.html
.. .. _cisco: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/cisco.html
.. ..  _exchange: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/exchange.html
.. .. _hpux: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/hpux.html
.. .. _iis: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/iis.html
.. .. _ldap: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/ldap.html
.. .. _linux: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/linux.html
.. .. _mongodb: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mongodb.html
.. .. _mssql: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mssql.html
.. .. _mysql: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mysql.html
.. .. _oracle: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/oracle.html
.. .. _switch: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/switch.html
.. .. _vmware: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/vmware.html
.. .. _windows: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/windows.html


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
