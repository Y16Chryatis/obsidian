#asegurar #respaldo

Las transacciones se usan para realizar operaciones SQL de manera atómica y segura. Si el código falla o no se ejecuta correctamente entonces los cambios no se aplican, si todo sale bien los cambios se conservan.

~~~ copy
BEGIN TRANSACTION; -- Inicia bloque con auto-guardado

/* Codigo a ejecutar */

COMMIT; -- Termina bloque con autoguardado
~~~

**nota:** Si el código se ejecuto sin problemas no se puede volver a un estado anterior.