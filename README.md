# SNMP Zabbix Sender

Powershell script, který s využitím utility Zabbix Sender (https://www.zabbix.com/documentation/3.4/manual/concepts/sender) bude odesílat SNMP informace v .json formátu do Zabbix serveru.

* Podporované OS
  * Windows 10 Enterprise LTSB Upgrade 2016
  * Windows 10 IoT Enterprise 2016
  * Windows 10 Pro 1607 a vyšší
  * Windows Server 2016

* Podrobné zadání
  * konfigurace ve dvou .json souborech, v prvním monitorované ip adresy a adresa zabbix serveru, ve druhém SNMP OID, které se sledují.
  * možnost soubežného behu více skriptu
  * krome binárního souboru **zabbix_sender.exe** využít **pouze** Powershell a jeho cmdlety. 
