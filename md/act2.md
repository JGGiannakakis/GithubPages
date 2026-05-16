# Crear carpetas

Podemos crear la carpeta usando el ratón con click derecho nueva carpeta o con el terminal

Usando el siguiente comando desde el terminal

> mkdir nombre_carpeta

# ¿Para qué sirven los permisos de una carpeta?
Los permisos controlan quién puede acceder o modificar un archivo o carpeta.
Cada archivo/carpeta tiene 3 tipos de usuarios:

- 👤 Usuario (owner): quien lo creó
- 👥 Grupo (group): usuarios del mismo grupo
- 🌍 Otros (others): todos los demás

Y 3 tipos de permisos:

|Permiso | Letra| Significado| 
| :--: | :--: | :--: | 
| Lectura |r| Ver contenido|
|Escritura |w| Modificar|
|Ejecución |x| Entrar en la carpeta|

# Modificar los permisos de una carpeta

Podemos modificar los permisos de una carpeta usando el comando

> chmod 

Seguido de letras o números

## Letras

> chmod u+rwx carpeta
Da todos los permisos al usuario

>chmod g-w carpeta
Quita el permiso de escritura al grupo

>chmod o+rx carpeta
Da el permiso de lectura y ejecucción a otros

## Números

Cada permiso tiene un valor
- r = 4
- w = 2
- x = 1

|Número|Permisos|
|:--:|:--:|
|7|rwx|
|6|rw-|
|5|r-x|
|4|r--|
|3|-wx|
|2|-w-|
|1|--x|

De esta forma podemos asignar permisos a todos los usuarios al mismo tiempo

> chmod 755 carpeta

Significa:

- Usuario: 7 → rwx
- Grupo: 5 → r-x
- Otros: 5 → r-x
