#fk

**Advertencia:**
SQLite tiene las claves foráneas deshabilitadas por defecto, es necesario habilitarlas en cada sesión o consulta usando:

~~~ copy
PRAGMA foreign_keys = ON;
~~~

Al crear una tabla agrega la sig. linea:

~~~ copy
    FOREIGN KEY (ID_Name) REFERENCES Nombre_tabla(ID_Nombre_tabla)
~~~

**Nota:** no se puede aplicar sobre un campo ya creado, en caso de ser necesario crea una tabla auxiliar y mueve los datos.
