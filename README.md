# SNMP Zabbix Sender

Powershell script, kter� s vyu�it�m utility Zabbix Sender (https://www.zabbix.com/documentation/3.4/manual/concepts/sender) bude odes�lat SNMP informace v .json form�tu do Zabbix serveru.

* Podporovan� OS
  * Windows 10 Enterprise LTSB Upgrade 2016
  * Windows 10 IoT Enterprise 2016
  * Windows 10 Pro 1607 a vy���
  * Windows Server 2016

* Podrobn� zad�n�
  * konfigurace ve dvou .json souborech, v prvn�m monitorovan� ip adresy a adresa zabbix serveru, ve druh�m SNMP OID, kter� se sleduj�.
  * mo�nost soube�n�ho behu v�ce skriptu
  * krome bin�rn�ho souboru **zabbix_sender.exe** vyu��t **pouze** Powershell a jeho cmdlety. 
