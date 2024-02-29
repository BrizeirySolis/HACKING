## Objetivo

El objetivo de este nivel es que inicies sesión en el juego usando SSH. El host al que necesita conectarse es **bandit.labs.overthewire.org**, en el puerto 2220. El nombre de usuario es bandit0 y la contraseña es **bandit0**. Una vez conectado, vaya a la página de [Nivel 1](https://overthewire.org/wargames/bandit/bandit1.html) para averiguar cómo superar el Nivel 1.
## Datos De Acceso Al Nivel
bandit.labs.overthewire.org
puerto 2220
nombre de usuario es bandit0 
la contraseña es bandit0

## Solución
```
ssh bandit0@bandit.labs.overthewire.org -p 2220


C:\Users\37182>ssh bandit0@bandit.labs.overthewire.org -p 2220
The authenticity of host '[bandit.labs.overthewire.org]:2220 ([51.20.13.48]:2220)' can't be established.
ED25519 key fingerprint is SHA256:C2ihUBV7ihnV1wUXRb4RrEcLfXC5CXlhmAAM/urerLY.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '[bandit.labs.overthewire.org]:2220' (ED25519) to the list of known hosts.
                         _                     _ _ _
                        | |__   __ _ _ __   __| (_) |_
                        | '_ \ / _` | '_ \ / _` | | __|
                        | |_) | (_| | | | | (_| | | |_
                        |_.__/ \__,_|_| |_|\__,_|_|\__|


                      This is an OverTheWire game server.
            More information on http://www.overthewire.org/wargames
```
## Notas Adicionales

- ssh protocolo seguro para conexiones en internet
- -p para conexion por puerto

## Referencias

link : [OverTheWire: Nivel Objetivo: Bandido Nivel 0](https://overthewire.org/wargames/bandit/bandit0.html)
