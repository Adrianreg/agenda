# Agenda telefónica
### Repositorio dedicado a la documentación de la creación de una agenda telefónica en XML



 <p align="center">
<img width=55% src="https://i.imgur.com/RxLftNw.png">
 </p>
 <p align="center">
<img width=55% src="https://i.imgur.com/MWvHO2x.png">
 </p>
 
 Este es mi proyecto de agenda telefónica en xml. Las primeras etiquetas, “agenda” y “contactos” creo que se entienden. Con el primero abrimos lo que viene siendo la agenda donde se almacenan los contactos, mientras que con el segundo estaríamos ante el inicio de dichos contactos.

A continuación, definí a las personas. La etiqueta “persona” posee los atributos “nombre” y “apellidos” para añadir dichos datos evitando usarlos como etiqueta por un simple motivo: ahorrarnos las etiquetas de cierre. Lo mismo pasa más adelante con los atributos “número” y “letra”.

Dentro de “dirección” definimos las etiquetas necesarias que definirían la dirección de una persona y dentro de “teléfonos” añadimos las etiquetas que definen los distintos teléfonos que pueden tener los contactos. 

Por esto el código tiene la forma que tiene. 
