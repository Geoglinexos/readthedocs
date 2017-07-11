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
| `aix`_                |            7          |       | `arkoon`_             |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `cisco`_              |            6          |       | `aruba_ap`_           |            3          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `exchange`_           |            5          |       | `aruba_wlc`_          |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| hp                    |            2          |       | `cisco_catalyst`_     |            8          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `hpux`_               |            6          |       | `cisco_sg300`_        |            6          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `iis`_                |            6          |       | `cisco_wlc`_          |            9          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `ldap`_               |            4          |       | `dell_force10`_       |            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `linux`_              |           15          |       | `dell_force10_s`_     |            9          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `mongodb`_            |           13          |       | `dell_powerconnect54`_|            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `mssql`_              |           23          |       | `dell_powerconnect62`_|           10          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `mysql`_              |           19          |       | `fortinet`_           |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `oracle`_             |           35          |       | `hp_procurve`_        |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `switch`_             |            3          |       | `motorola_rfs6000`_   |            7          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `vmware`_             |           11          |       | `palo_alto`_       	|           15          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
| `windows`_            |           10          |       | `palo_alto_api`_    	|            5          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+
|                       |                       |       | `stormshield_sn`_     |            8          |
+-----------------------+-----------------------+-------+-----------------------+-----------------------+


.. Hyperlink pour les packs Linexos

.. _arkoon: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/arkoon.html
.. _dell_powerconnect54: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_powerconnect54XX.html
.. _dell_powerconnect62: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_powerconnect62XX.html
.. _aruba_ap: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/aruba_ap.html
.. _aruba_wlc: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/aruba_wlc.html
.. _cisco_catalyst: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_catalyst.html
.. _cisco_sg300: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_sg300.html
.. _cisco_wlc: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/cisco_wlc.html
.. _dell_force10: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_force10.html
.. _dell_force10_s: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/dell_force10_s_series.html
.. _fortinet: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/fortinet.html
.. _hp_procurve: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/hp_procurve.html
.. _motorola_rfs6000: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/motorola_rfs6000.html
.. _palo_alto: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/palo_alto.html
.. _palo_alto_api: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/palo_alto_api.html
.. _stormshield_sn: http://192.168.1.214:8000/docs/shinken/fr/latest/linexos/stormshield_sn.html

.. Hyperlink pour les pack Shinken Solution
.. _aix: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/aix.html
.. _cisco: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/cisco.html
.. _exchange: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/exchange.html
.. _hpux: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/hpux.html
.. _iis: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/iis.html
.. _ldap: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/ldap.html
.. _linux: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/linux.html
.. _mongodb: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mongodb.html
.. _mssql: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mssql.html
.. _mysql: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/mysql.html
.. _oracle: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/oracle.html
.. _switch: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/switch.html
.. _vmware: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/vmware.html
.. _windows: http://192.168.1.214:8000/docs/shinken/fr/latest/shinken_solution/windows.html


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
