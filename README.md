# Trabajo Practico: Curso Android : Gobierno Regional del Callao

Se pretende desarrollar una aplicación la cual pueda traer datos principales de la institución CJAVA y mostrarla en la pantalla de la siguiente manera:

Para poder desarrollar esta aplicación debera tener en cuenta las siguientes consideraciones:

1. Cree un nuevo proyecto en Android Studio bajo el nombre de TrabajoPractico_Android_GRC, configuren el nombre de su paquete como com.cjava.androidwork y  seleccione como Minimun SDK el API 18: Android Jelly Bean

2. Usará como servicio web el link público que ofrece GitHub con el perfil de CJAVA.

      Enlace de servicio web: https://api.github.com/users/cjavaperu
      
      Cuerpo de respuesta (JSON):
      
      ```json
{
  "login": "cjavaperu",
  "id": 12662322,
  "name": "CJAVA PERÚ",
  "company": "Cjavaperu",
  "blog": "www.cjavaperu.com",
  "location": "Av. Arenales 395 Of. 290 Cercado de Lima"
}
```
  
3. Importar como dependencias la libreria de Retrofit para el consumo de el servicio web en el gradle:
```groovy
 compile 'com.squareup.retrofit2:retrofit:2.0.2'
 compile 'com.squareup.retrofit2:converter-gson:2.0.2'
 ```
  
4. Implementar el consumo del servicio web mediante Arquitectura  Android MVP

     
![alt tag](https://postimg.org/image/3lsfxlzy1/)

