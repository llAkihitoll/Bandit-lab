## Bandit Level 0

Contraseña:  ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

### --- Comandos utilizados ---

ls, cat

### Explicacion:

Leer el readme que habia al ingresar

## Bandit level 1

Contraseña: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

### --- Comandos utilizados ---

ls, cd, cd .., cat

### Explicacion:

leer un archivo con nombre "-" usando cat ./

## Bandit level 2

Contraseña: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

### --- Comandos utilizados ---

ls, ls -alh, cat, du, cd, file, find

### Explicacion:

Leer un archivo que en el nombre incluia "--(nombre del archivo)--" 
en el cual utilice cat -- "--(nombre del archivo)--"

## Bandit level 3

Contraseña: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

### --- Comandos utilizados ---

cd, ls, ls -alh, cat

### Explicacion:

Entrar a una carpeta que contenia el archivo el cual contenia la contraseña

## Bandit level 4

Contraseña: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

### --- Comandos Utilizados ---

find, ls, ls -alh, cat, cd, cd ..

### Explicacion:

Entrar a la carpeta que contenia varios archivos y encontrar el archivo con el que tenia la 
contraseña legible

## Bandit level 5

Contraseña: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

### --- Comandos utilizados ---

ls, ls -alh, find, cd, cat

### Explicacion:

Buscar usando el comando de find el archivo que sea de 1033 bytes, que no sea ejecutable y que sea 
legible 

## Bandit level 6

Contraseña: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

### --- Comandos utilizados ---

ls, la -alh, find, cat

### Explicacion:

Utilizar el comando de find para encontrar la direccion del archivo que contiene la contraseña

## Bandit level 7

Contraseña: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

### --- Comandos utilizados ---

ls, ls -alh, cat, strings, grep

### Explicacion:

Al tratar de leer el archivo de data.txt, este muestra demasiados strings con diferentes
"contraseñas", y usamos el comando de strings y grep para encontrar el string que contiene
la contraseña correcta 

## Bandit level 8

Contraseña: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

### --- Comandos utilizados ---

ls, ls -alh, cat, sort, uniq, 

### Explicacion:

Al abrir el archivo de data.txt aparecen muchas "contraseñas" repetidas, luego al utilizar el
comando de sort se agrupan para luego utilizar el comando de uniq para encontrar la contraseña 
para el siguiente nivel


## Bandit level 9

Contraseña: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

### --- Comandos utilizados ---

ls, ls -alh, cat, strings, grep

### Explicacion:

Al leer el archivo de data.txt sale informacion que no se puede leer, por lo tanto se usa el comando
de strings junto con grep para encontrar el string con el que tiene al inicio varios de "=" que
indica la contraseña del siguiente nivel

## Bandit level 10

Contraseña: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

### --- Comandos utilizados ---

ls, cat, base64

### Explicacion:

Al abrir el archivo de data.txt sale un codigo en base64 el cual se decodifica usando el comando
base64 para obtener la contraseña

