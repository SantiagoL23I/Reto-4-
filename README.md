
# RETO 4

Hoy vamos a hacer un pseudocódigo y diagrama de flujo para dos problemas.

## Hallar números primos

```pseudocode
  [variables]
n : entero
i : entero
inicio
  i := 2
  Mientras (i < n) hacer
    Si modulo(n,i) == 0 entonces
      escribir("i es divisor de n")
       si el numero de modulos (n,i)<=2 
        escribir ("i es primo")
       sino 
        escribir("i no es primo")
        i:= i + 1
    sino
      escribir("i no es divisor de n")
    i := i + 1
  Fin mientras
fin
```
[![](https://mermaid.ink/img/pako:eNpVkc1ugkAQx19lMidNwQIqAq01VfxqbC96qnjYwFo3gV3DR1tLeKS-QK--WBeE1O5p5z-_-c_Mbo6-CCg6uA_Fh38gcQob987jIM9ja8mZz0QbVPUBxlt-_oloLIDvamBcJSZ1NNmuWJISCCgYcCDllav6rmLcLRsaTZlbSdM6muYxTViQibKQ3zKgCfiyzaiQGKzP3xU921aJgL2zRMSlqRRX-TSEZipZ_SyCLBQJcIXB_dD4Z7C5GBxjFokdNL1L4kVUwFwCXFw3qaGFnJ3d1IsscwYR5SIGud2oqJH5ZZ5FHS6vbJ9aM8bb14lmouYBVqWYlM0bj82fGSoot4sIC-Qf5aXiYXqgEfXQkdeA7kkWph56vJAoyVKxPnEfnTTOqILZMSApdRl5i0mEzp6EiVSPhL8KETWQDNHJ8RMdvat3ugNN62k9azCwDHug4AkdVdftTlfT9b5p9TXdNLp2oeBXZSELerZlWbatmZrds0yj-AWRyqqL?type=png)](https://mermaid.live/edit#pako:eNpVkc1ugkAQx19lMidNwQIqAq01VfxqbC96qnjYwFo3gV3DR1tLeKS-QK--WBeE1O5p5z-_-c_Mbo6-CCg6uA_Fh38gcQob987jIM9ja8mZz0QbVPUBxlt-_oloLIDvamBcJSZ1NNmuWJISCCgYcCDllav6rmLcLRsaTZlbSdM6muYxTViQibKQ3zKgCfiyzaiQGKzP3xU921aJgL2zRMSlqRRX-TSEZipZ_SyCLBQJcIXB_dD4Z7C5GBxjFokdNL1L4kVUwFwCXFw3qaGFnJ3d1IsscwYR5SIGud2oqJH5ZZ5FHS6vbJ9aM8bb14lmouYBVqWYlM0bj82fGSoot4sIC-Qf5aXiYXqgEfXQkdeA7kkWph56vJAoyVKxPnEfnTTOqILZMSApdRl5i0mEzp6EiVSPhL8KETWQDNHJ8RMdvat3ugNN62k9azCwDHug4AkdVdftTlfT9b5p9TXdNLp2oeBXZSELerZlWbatmZrds0yj-AWRyqqL)

## Hallar Raíz Cuadrada
```pseudocode
 [variables]

r= real 
Inicio
r:= 0 
Tomar solo primeros tres decimales
r/2
si= (r/2)^2 = r 
 escribir (r/2 es la raiz Cuadrada)
si= (r/2)^2 > r 
  ((r/2)^2)/2
si= (r/2)^2 < r
  ((r/2)^2)*2
Repetir hasta hallar aproximación deseada.
Fin
```
