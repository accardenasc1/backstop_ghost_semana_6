# Semana 6: Pruebas de regresión visual GHOSTV5.22 y GHOSTV3.42 en Backstop
 
 <h3>Dentro de las pruebas de regresión realizadas por el lenguaje Backstop JS se implemento los 5 escenarios de pruebas para la funcionalidad de TAGS para la ejecución de las pruebas se debe:</h3>
 
 <b>Paso 1: </b>
 Abrir un terminal e instalar Backstop con el siguiente comando: npm install -g backstopjs
 
 <b>Paso 2: </b>
 Dentro de la carpeta de preferencia clonar el repo actual  https://github.com/accardenasc1/backstop_ghost_semana_6.git
 
 <b>Paso 3: </b>
 Al analizar los archivos creados podemos encontrar dos archivos importantes para la ejecución de las pruebas <b>(Si estos archivos no se encuentran volver al paso 2)  </b>
  <ul> <li> backstop.json el cual contiene los escenarios y las referencias de ghost en su versión 5.22 </li>
       <li> backstop_test.json el cual contiene los escenarios y las referencias de ghost en su versión 3.42 </li> </ul>
 <b>Paso 4: </b>
 Dentro de la misma terminal donde se clono el repo ejecutar el comando backstop test lo cual debera generar un archivo HTML (Se adjunta url del .gif como evidencia y ejemplo para abrirlo debera contar con cuenta Uniandes https://uniandes-my.sharepoint.com/:i:/g/personal/ac_cardenasc1_uniandes_edu_co/ET1qz-aYfudOpU-N1bevPPoBYmQ1MxpMwcqvVMzkcgxyog?e=KjyRsy)
 
 <b>Paso5: </b>
 Dentro de la misma terminal donde se ejecuto lo anterior ejecutar el siguiente comando backstop approve lo cual creara una carpeta denominada bitmaps_reference (Se adjunta url del .gif como evidencia y ejemplo para abrirlo debera contar con cuenta Uniandes https://uniandes-my.sharepoint.com/:i:/g/personal/ac_cardenasc1_uniandes_edu_co/EYkLxeBRmqJKrZK2oDIdewkBgh7snrjh2FE3Y1FN58A4nA?e=auXBkO)
 
 Ya se tiene las imagenes de referencia cargadas al sistema lo cual nos permite compararlas con una version inferior de Ghost.
 
 <b>Paso 6: </b>
 Cambiar el nombre del archivo backstop.json a backstop_new_version.json
 
 <b>Paso 7: </b>
 Cambiar el nombre del archivo backstop_test.json a backstop.json
 
 <b>Paso 8: </b>
 Ejecutar el comando que generara el script o HTMl de comparación backstop test
 
 Se adjunta evidencia o ejemplo del paso 6,7 y 8 debera contar con una cuenta uniandes para poder visualizar https://uniandes-my.sharepoint.com/:i:/g/personal/ac_cardenasc1_uniandes_edu_co/EXnhbQ-ZLXlPil-05BT5bj0BRJwRFN4aep9duBNhqwDw1g?e=cmgfyy
 
 Se debera genera un HTMl como el siguiente con las imagenes de referencia, comparación y resultado.
 
 ![image](https://user-images.githubusercontent.com/111259182/202930713-2d3974b5-bc3e-4873-b08f-9bb5638ce425.png)
 
 Ventjas y descentajas en la wiki de este repositorio

 
 
 
