Andrés Molina Gonzalez \- Trabajo Markdown 
=
___

##INDICE
[1. _Diagrama de comportamiento_](#diagrama-de-comportamiento)

[2. _Tipos de diagramas de comportamiento_](#tipos-de-diagramas-de-comportamiento)

[3. _Diagramas de interacción_](#diagramas-de-interacción)
[3.2. _Ejemplo_](#ejemplo-interacción)

[4. _Diagramas de caso de uso_](#diagramas-de-caso-de-uso)
[4.2. _Ejemplo_](#ejemplo-caso-de-uso)

[5. _Codigo mas utilizado en sql_](#codigo-mas-usado-en-sql)
[5.2. _Vista de la tabla creada_](#ejemplo-de-tablas-sql)

[6. _Webgrafia_](#webgrafia)

---

###Diagrama de comportamiento

Diagrama que expresa las **secuencias de estados** por los que pasa un objeto a lo largo de su vida en respuesta a eventos. Estos diagramas se usan para **_visualizar_ y _especificar_**, a la vez que documentar, aspectos dinámicos de un sistema.

![Imagen](https://sites.google.com/site/analisisguzmanjose/_/rsrc/1427436460730/unidad-3-modelos-de-actividad-y-de-estado/3-1-diagramas-de-comportamiento/png%20%289%29.png)


###Tipos de diagramas de comportamiento
* Diagramas de Caso de uso.
* Diagramas de Secuencia.
* Diagramas de Estados.
* Diagramas de Actividades

[_Webgrafia_][enlace1]

[^SUBIR^](#indice)

###Diagramas de interacción
Sirve para captar el **comportamiento** interactivo de un sistema. Los _diagramas de interacción_ se centran en describir el flujo de mensajes dentro de un sistema y ofrecen contexto para una o más líneas de vida dentro de un sistema. 

_Mas funciones de los diagramas de interacción [^1] Tambien tienes mas informacion [^2]._

####Ejemplo interacción
![Imagen](Imagen1.png)

[^SUBIR^](#indice)

###Diagramas de caso de uso
>En el diagrama de casos de uso, las funciones del sistema en cuestión se representan desde el punto de vista del usuario (llamado “actor” en UML). 
>
>>Este actor no tiene que ser necesariamente un usuario humano, sino que el rol también puede atribuirse a un sistema externo que accede a otro sistema. 
>
>* De este modo, el diagrama de casos de uso muestra la relación entre un actor y sus requisitos o expectativas del sistema, sin representar las acciones que tienen lugar o ponerlas en un orden lógico.

####Ejemplo caso de uso
![Imagen](https://upload.wikimedia.org/wikipedia/commons/8/80/UML_diagrama_caso_de_uso.svg)

[^SUBIR^](#indice)

###Codigo mas usado en SQL
*[SQL]:Lenguaje de Consulta Estructurado
Que es **_SQL_** [^3]

**CREAR TABLAS**
```sql
CREATE TABLE employees (
    employee_id NUMBER(10) NOT NULL,
    first_name VARCHAR2(30),
    last_name VARCHAR2(40)
);
```
**CONSULTAS SIMPLE**
~~~sql
SELECT first_name
FROM employees
ORDER BY LENGTH(first_name) DESC;
~~~

####Ejemplo de tablas sql

######Employees
| Employee_id  | first_name  | last_name |
|--------------|:-----------:|:----------:
| 321312       | Andrés      |  Molina   |
| 763127       | Antonio     |  Perez    |
| 723467       | Angela      |  Sanchez  |
| 123412       | Maria       |  Rodriguez|

[^SUBIR^](#indice)
___

##Webgrafia

[Diagramas de comportamiento][enlace1]

[Diagrama de interacción][enlace2]

[Diagrama de caso de uso](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/diagrama-de-casos-de-uso/)

[^SUBIR^](#indice)

[enlace1]:https://www.ceac.es/blog/elaborar-diagramas-de-comportamiento-en-entornos-de-desarrollo

[enlace2]:https://www.lucidchart.com/pages/es/diagrama-de-interaccion-uml


[^1]: Además, los **_diagramas de interacción_** pueden emplearse para representar las secuencias ordenadas dentro de un sistema, y actúan como medio para visualizar los datos en tiempo real vía UML.
[^2]: [_Webgrafia_][enlace2]
[^3]: **SQL** Un tipo de _lenguaje de programación_ que te permite manipular y descargar datos de una base de datos. 
