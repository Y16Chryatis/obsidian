
~~~ copy
# importa la libreria sqlite3 y le asigna el valor db para simplificar su uso
import sqlite3 as db

# Nombre del archivo de la base de datos
db_name = 'ventas.db'

# Crear conexión
conn = db.connect(db_name)

# Cerrar conexión
conn.close()
~~~

La base de datos es creada si no existe.