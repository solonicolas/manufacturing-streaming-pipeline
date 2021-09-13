# Data source information

## Dati in tabelle di livello 2 su SQL server

Aree di produzione:

- electric area fournace -EAF (forno fusorio)
- ladle fournace - LF
- __continuos custing machine__ - CCM (liquido -> solido + taglio) - semilavorato lungo e largo

### q3intelligenceDWH :  database di livello 2 di danieli (source)

main table: REPORTS

- ogni record rappresenta una colata
- key: HEAT_ID 
- auto-increment : report counter

tabelle che iniziano con rep (figlie di reports) -> tabelle del Bronze

- REP_CCM_PRODUCTS -> semilavorati
- REP_CCM_PRODUCT_VARS -> equivalente dei file json 01_TSC
- REP_CCM_COILS -> mappatura semilavorati / prodotti finiti
- REP_CCM_COILS_VARS -> equivalente dei file json 02_HSM

### q3analyticsDWH - nostro DWH

importanti sono le viste

- q3i_cfg -> tabelle del Silver
- q3i_olap_dt
- q3i_olap_ft

## Json file (100 rilevazioni per prodotto)

-  01_TSC macchina dei semilavorati
- 02_HSM macchina dei prodotti finiti
