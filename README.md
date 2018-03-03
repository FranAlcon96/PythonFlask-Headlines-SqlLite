# PythonFlask-Headlines-Sqlite

Apliación de headlines con persistencia empleando una base de datos SqlLite.

## Requisitos: 

* Tener instalado sqlite en nuestro sistema. Se puede instalar con sudo apt-get install sqlite.
* Crear la tabla news. Para ello debemos abrir el cliente sqlite y seleccionar la base de datos news --> sqlite3 news.db
  Una vez hecho esto escribimos lo siguiente para crear la tabla:
  
      CREATE TABLE news (
        title varchar(255),
        link varchar(255),
        publisher varchar(255)
    );
* Tener instalado el comando pip, para poder instalar módulos de python. Se puede con instalar con sudo apt-get install python-pip.
* Instalar flask y feedparser, con pip install flask y pip install feedparser.

## Ejecución:

