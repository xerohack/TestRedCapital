# TestRedCapital
Respuestas a prueba técnica Red Capital


EN BASE A LAS 3 TABLAS PRESENTADAS (Compra, Detalle_Compra, Categoria), las consultas con ORM Eloquent son;

1. 

2. En cuanto al inicio de desarrollo, un diseño basado en composicion es mas lento, mas complejo pero mas facil de cambiar en el tiempo. En cambio, herencia no es tan adaptable al cambio, es una metodologia mas rapida y facil, pero pobre.

Cuando usar herencia: cuando la relacion es de 1 a 1.
Cuando usar composicion: cuando la relacion es de 1 a 0 o 1 a n.

3. El patron de diseño MVC se refiera a Modelo, Vista, Controlador, que es un patron de arquitectura de construccion de software.
  Funciona de la siguiente manera; un usuario al hacer una peticion lo hace a traves de la VISTA del sistema, este se comunica con el CONTROLADOR para, segun cual sea la peticion, consultar los datos al MODELO, validar los datos y devolver esta peticion al CONTROLADOR y luego a la VISTA. De esta forma se comunican los tres entes mas importantes del frameworl laravel.

4.

5.

6. - php artisan make:controller Nombre_Controlador,
    - php artisan db:seed
     - La diferencia es que el metodo "find" busca por atributo especifico, mientras que "all" trae todo lo que encuentra.
     
