#normlizacion

### Es necesario que:
1. Toda tupla (relación) debe tener una llave primaria
2. Lo dominios  simples solo deben contener valores atómicos (en su forma amas simple)

### Para lograrlo:
1. Se identifica la llave primaria para cada tupla, se selecciona una o se crea dependiendo la situación.
2. Se descomponen en atributos simples todos los atributos compuestos, esto dependerá del uso de la DB, en algunas aplicaciones es mejor mantener el nombre en un solo atributo | Juan Hernández Gonzales | mientras que para otras podría ser mejor separar nombre y apellidos | Juan | Hernández | Gonzales | 