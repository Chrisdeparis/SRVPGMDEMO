# SRVPGMDEMO

## PGM de service utilisant des modules : avec plusieurs procédures pour la conversion de C° en F°

#### Procédures
- **[CELSTOFAHR](M_CEL2FAHR.SQLRPGLE)**
- **[GETFAHRENHEIT](M_GETFAHR.SQLRPGLE)**
- **[GETSTATUSFAHRENHEIT](M_GETSTATF.SQLRPGLE)**

#### Paramètres
- in_tempCel
- ou_tempFahr
- ou_status

## CALL 

```diff
+  CALL ENGLISHV6 PARM('10') 
+  DSPLY  At 10.00 °C (50 °F), water is liquid.   ✅  
```
