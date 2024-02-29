## Objetivo

The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once
## Datos De Acceso Al Nivel
TESKZC0XvTetK0S9xNwm25STk5iWrBvP
## Solución
```
bandit8@bandit:~$ wc data.txt
 1001  1001 33033 data.txt
bandit8@bandit:~$ cat data.txt | sort | uniq -u
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
bandit8@bandit:~$

```
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
## Notas Adicionales

sort - ordenar
uniq -c cuenta cuantas veces
uniq -u muestra lineas unicas 

## Referencias

