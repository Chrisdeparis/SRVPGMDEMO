# SRVPGMDEMO

## PGM de service utilisant module : avec plusieurs procédures pour la conversion de C° en F°

#### Procédures
- CELSTOFAHR a besoin de :
- GETFAHRENHEIT
- GETSTATUSFAHRENHEIT

#### Paramètres
- in_tempCel
- ou_tempFahr
- ou_status

## CALL 

```diff
+  CALL ENGLISHV6 PARM('10') 
+  DSPLY  At 10.00 °C (50 °F), water is liquid.   ✅  
```
