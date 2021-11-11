# Detección de Objetos al Guaraní 
## Entrenamiento basado en TensorFlow Lite usando Arquitecturas EfficienDet

**Link de para descarga de cojunto de datos** : https://drive.google.com/file/d/13-JjBnEnymCwTHlAzenVP5Tzmz6Yv5JQ/view?usp=sharing     

***anotaciónes_windows.csv:*** archivo de anotaciones del conjunto de datos  para entornos windows    
***anotaciónes_linux.csv :*** archivo de anotaciones del conjunto de datos para entorono linux.     
En la carpeta ***modelos*** se encuentran disponibles  los archivos **.tflite** con la variación de todas las  arquitecturas.   
### Estos modelos fueron entrenados con los  siguientes parametros:

**Cantidad de Objetos : 10**

**Conjunto de Datos por Objeto:**  
*Entrenamiento :*  **160**                                      
*Validación    :*   **20**    
*Prueba        :*   **20**   
**Total         :  200** 
                              
**Tamaño de datos para Entrenamiento : 8bytes**   
**Numero de Épocas : 100 Épocas**
                              
## Herramientas utilizadas  para creación del metodo de desarrollo
**LabelImg : para etiquetado de datos**
**Anaconda Promp : para gestion de entornos de trabajo**
**Jupyter Notebook : ejecucion de scripts **
**Python : lenguaje de entrenamiento **
**TensorFlow : libreria de IA**
