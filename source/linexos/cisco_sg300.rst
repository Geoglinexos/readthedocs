=============================
Pack Cisco SG300
=============================

***********
Description
***********

*Checks pour les commutateurs SG300 de Cisco*

.. note:: Ces checks ont été testé sur des SG300 10 Ports PoE, mais sont fonctionnel sur des gammes SG100 et SG500.

********
Services
********



Cisco SG300 - Interface Availability $KEY$
	- Vérification de la disponibilité d'une ou plusieurs interfaces
	- SNMP

~~~~

Cisco SG300 - CPU
	- Utilisation du CPU
	- SNMP

~~~~

Cisco SG300 - FANs
	- Vérification du fonctionnement des ventilateurs 
	- SNMP

.. note:: Ne renvoie pas d'erreur critique si un switch ne possède pas de ventilateurs.

~~~~


Cisco SG300 - Temperature
	- Vérification de la température du commutateur
	- SNMP

~~~~


Cisco SG300 - Uptime
	- Uptime du commutateur
	- SNMP

~~~~

Cisco SG300 - Interface Usage $KEY$
	- Utilisation d'une ou plusieurs interfaces du commutateur
	- SNMP
