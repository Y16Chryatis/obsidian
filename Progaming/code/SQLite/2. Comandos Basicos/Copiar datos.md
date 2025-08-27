---
aliases:
  - Enviar datos a otra tabla
  - Duplicar datos a tabla
---

Envia datos de una tabla a la otra

~~~
INSERT INTO Tabla_recibe (Campo1, Campo2, Campo3)
SELECT Campo1, Campo2, Campo3 FROM Tabla_envia;
~~~
