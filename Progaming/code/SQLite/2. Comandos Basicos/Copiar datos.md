
Envia datos de una tabla a la otra

~~~ copy
INSERT INTO Tabla_recibe (Campo1, Campo2, Campo3)
SELECT Campo1, Campo2, Campo3 FROM Tabla_envia;
~~~
