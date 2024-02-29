## Objetivo
The password for the next level is stored in the file **data.txt** in one of the few human-readable strings, preceded by several ‘=’ characters.
## Datos De Acceso Al Nivel
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
## Solución
```
bandit9@bandit:~$ strings data.txt |grep ==
x]T========== theG)"
========== passwordk^
========== is
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
bandit9@bandit:~$
```
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
## Notas Adicionales
strings muestra las cadenas dentro de un archivo binario de datos
## Referencias

