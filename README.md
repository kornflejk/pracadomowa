Zadania z tygodnia 3

3.1

Konwencja nazewnicza
Resource Group:
	TypUslugi/NazwaAplikacji/NazwaProjektu + RG + _środowisko
	przykłady  BIRG_Prod  BIRG_Test HubRG_Test  NavisionRG_Prod SAPRG_Test

Vnet
	TypUslugi/NazwaAplikacji/NazwaProjektu + VnetXX + _środowisko
	przykłady NavisionVnet01_Prod NavisioVnet01_Test BIVnet01_Prod	SAPVnet02_Prod

Maszyny Wirtualne
	NazwaAplikacji+Rola+VMXX+ _środowisko
	przykłady NavAppVM01_Prod NavSQLVM03_Prod DCVM01_Test SAPIISVM08_test
	siecówki i IPki publiczne z dopiskami _NICXX oraz _PIP

Dysk
	NazwaVM + _OSdisk/DatadiskXX
	NavAppVM01_Prod_OSdisk NavAppVM01_Prod_DataDisk02 DCVM01_Test_OSdisk SAPIISVM08_test_Datadisk03

StorageAccount
	TypUslugi/NazwaAplikacji/NazwaProjektu
	Storage bedzie zawierał dane zarówno Test i Prod
