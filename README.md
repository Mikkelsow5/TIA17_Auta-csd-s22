# TIA17_Auta-csd-s22
Vejledning til opsætning af versionsstyring med GitHub med værktøjerne Automation Compare Tool (ACT) og Version Control Interface (VCI)

## Opsætning
### Github
- Følg en vejledning online, installer **GitHub Desktop** og *Clone* repository
### TIA
- Hent og installer Automation Compare Tool - denne vejledning anvender 109797235_Automation_Compare_Tool_1_0
- Åben TIA Portal v17 og gå til **Options** - **Settings**
- Naviger til **Version control interface** - **Compare** og tilgå **<Add new..**
- Skriv navn - eksempelvis AC Tool 
- Indsæt stien til Automation Compare Tool - eksempelvis *"C:\Program Files\Siemens Automation\SIMATIC Automation Compare Tool\ACTool.exe"*
- Klik **Add** og luk **Settings**
- Opsæt Hardware eller importer Archive https://github.com/MigaUCN/TIA17_Auta-csd-s22/blob/main/UCN%20s7-1214cAC_DC_RLY.zap17
- Tilføj et arbejdsområde til synkronisering ved at klikke **Add new workspace** under **Version control interface**
- Klick **Configure workspace**, indsæt stien til det *Cloned* repository under **Workspace path** og klik *OK*
- Brug *Export to workspace* for at sende opdateringer og *Import from workspace* til at hente opdateringer
- Brug GitHub Desktop til **Commit**, **Push** og **Pull**

## Links
**SIMATIC Automation Compare Tool** https://support.industry.siemens.com/cs/document/109797235/simatic-automation-compare-tool-?dti=0&lc=en-DO

**TIA Portal Add-Ins** https://support.industry.siemens.com/cs/document/109773999/tia-portal-add-ins?dti=0&dl=en&lc=it-WW
Denne vil udgå, da GitHub Desktop vil styre commit, pull og push

**GitHub Desktop**
Anvender https://desktop.github.com/, til at opsætte repository, kommer også til at styre commit, pull og push til repository

### Youtube videor 
Vejledning fra Outlier Automation omkring opsætning https://youtu.be/gmTNIA9MhJk

## Hardware
- CPU 1214C AC/DC/Rly [firmware 4.4]
- AQ 1x12BIT_1
- SM 1223 DI8/DQ8 x relay
- SM 1232 AQ2

![Hardware_1214cAC_DC_RLY](https://github.com/MigaUCN/TIA17_Auta-csd-s22/blob/main/images/Hardware_1214cAC_DC_RLY.png)
