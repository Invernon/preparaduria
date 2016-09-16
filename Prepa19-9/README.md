# Instrucciones
#### Parte 1:
1. descargar y extraer el archivo _clima.html_
2. Registrarse en [openweathermap] (http://openweathermap.org/api)
3. Ingresar a [openweathermap] (http://openweathermap.org/api), entrar a su cuenta en la sección de _API Keys_ y copiar el valor de _Key_

#### Parte 2: en esta parte modificaran el archivo clima.html por lo tanto necesitan tener instalado sublime text, únicamente modificaran la sección de código que se encuentra al final del código en JavaScript, el cual utilizará AngularJS.
1. Modificar la variable key por el valor que obtuvieron en la **Parte 1**.
2. Modificar la variable **cédula** por su cédula de identidad.
3. Realizar una consulta del tipo **$http.get** al API de [openweathermap] (http://openweathermap.org/api) `tendrán que buscar como realizar esto`.
4. Agregar al **JSON** obtenido un campo que tenga como etiqueta **nombre** y valor su **NOMBRE**.
3. Guardar los datos obtenidos en **$scope.city** esta variable no tiene que ser declarada. `sí tienen error en esta parte significa que tienen que interpretar los datos obtenidos`.
4. **_IMPORTANTE!!!_** utilizar restultado obtenido de la consulta [openweathermap] (http://openweathermap.org/api) y usando la variable **urlPost** como URL, para hacer uso de **$http.post**
