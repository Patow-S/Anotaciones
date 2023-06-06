# Anotacion

## Entorno JAVA
java
java dk

Designar 
archivos del programa 
java 
java jdk-20
bin
ruta
variable - nueva JAVA_HOME + ruta

Editar 
path nueva 
ruta 

## Entorno ECLIPSE
Eclipse 
entorno developer 
direccion jre

## Entorno Git

### Comandos GIT

Directorio 
	dr
Archivos dentro de carpeta
	ls
Crear repositorio
	git init
Estatus del repositorio
	git status
Rastrear/añadir archivo especifico
	git add <file>
Rastrear/añadir archivo total
	git add .
Dejar de rastrear archivo
	git rm --cached <file>
Editar local nombre / email
	git config --local user.name "<file>"
	git config --local user.email "<file>"
Chekpoint
	git commit -m "mensaje descriptivo"
ID unica/hash
	git log
Historico de total commit's
	git log --oneline
Historico de total commit's detalles 
	git log -p
No rastrea
	Ir a VS y crear .gitignore
		/carpeta

Los commit se hacen al final del dia pero siempre depende
El codigo debe funcionar siempre que se haga commit

Crear servidor 
	mkdir <file>
Añadir cosas al servidor 
	git init --bare
Servidor remoto (busca los que ya les diste)
	git remote
agregar a busqueda servidor remoto
	git remote add <nameserv> <urlserv>
ver si esta bien colocado 
	git remote -v

clonar repositorio
	git clone /<lugar de doc>/ < proyecto>
empujar reposiorio 
	git push <nameserv> main
renombar repositorio 
	git remote rename <renameserv>
### Inicio Git	
paso 1 
	crear un servidor
	ir a /servidor
	iniciar --bare
paso 2
	ir la carpeta que tiene la informacion
	crear e iniciar git remote add <C:/Users/USUARIO/Desktop/GITHUB/servidor/>
paso 4
	ir a lña carpeta que tendra la informacion
	clonar 
paso 5
	push a la carpeta que da infor 
paso 6
	carpeta ana/proyecto
	rename origin git remote rename origin servidorlocal
	pull de la carpeta ana/proyecto

C:/Users/USUARIO/Desktop/GITHUB/servidor/

## Entorno Github
1
	estar en la carpeta personal.
	
	
### Entorno SQL 

Base de datos 
	USE _base de datos_
Crear tabla 
	CREATE TABLE  _tablax_ (
	_elemento_ VARCHAR (20) NULL,
	_elemento_ VARCHAR (150) NULL,
	_elemento_ VARCHAR (150) NULL,
);
Crear columna
	LATER TABLE _tablax_ ADD COLUM (LOTE);
Eliminar columna (precausion revisar entrelazados)
	DROP TABLE  _tablax_ 
Eliminar elemnto de una tabla
	DELETE FROM _tablax_ WHERE nombre = "77056";
Incertar en tabla 
	INSERT INTO _tablax_ (
	_nombre_ _nombre_ _embace_ )
	VALUES ("770932", "clean " , "paper place");
Seleccionar tabla 
	SELECT * FROM  _tablax_
Seleccionar elemento de una tabla
	SELECT _elemento1_ , _elemento2_ FROM _tablax_ ;
Seleccionar elemento con resultado especifico
	SELECT 8 FRO, _tablax_ 	WHERE EMBACE = "botella de vidrio"	
Configurar elemento de tabla
	UPDATE _tablax_ SET _nombre_ = "77056" , _embace_ = "bidon" 
	WHERE  volumen  = "300 ml" (dato mas especifico)
LLave primaria
	ALTER TABLE _tablax_ ADD PRIMARY KEY (nombre);

Exclusion especifica 
	SELECT * FROM _tablax_ WHERE EDAD > 27;
	SELECT * FROM _tablax_ WHERE PRECIO_LISTA , 28.51;
	SELECT * FROM _tablax_ WHERE PRECIO_LISTA BETWEEN  28.49 AND 28.52;
	
Exclusion compleja 
	SELECT * FROM _tablax_ WHERE(PRECIO_LISTA >= 15 AND TAMANO = "1 LITRO") OR (ENVASE = "LATA" OR ENVACE = "BOTELLA PET");
	
	
	
	

	
	


	
	
	
	
	
	
	
	
	
	
	
	
