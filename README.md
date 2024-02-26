# Sweet Lift Taxi ¿Cuántos taxis se necesitarán en la siguiente hora?

## Contacto
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andres946/)
[![Correo Electrónico](https://img.shields.io/badge/Correo%20Electrónico-andresgvelasquez8@gmail.com-red?style=for-the-badge&logo=mail.ru)](mailto:andresgvelasquez8@gmail.com)  

## Instalación de dependencias

Para instalar las dependencias necesarias para este proyecto, puedes ejecutar el siguiente comando:

```bash
pip install -r requirements.txt
```
**Nota** Esta versión de Boruta puede arrojar un error al utilizar np.float, np.int y np.bool. Basta con reemplazarlos por
float, int, bool respectivamente en el archivo donde este el error. 

## Descripción
La compañía Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Para atraer a más conductores durante las horas pico, necesitamos predecir la cantidad de pedidos de taxis para la próxima hora. Construye un modelo para dicha predicción.
La métrica RECM en el conjunto de prueba no debe ser superior a 48.

# Diccionario de datos
La ubicación del archivo es en `./datasets/taxi.csv`  
`datetime`: fecha y hora   
`num_orders`: Cantidad de taxis pedidos 

## Plan del proyecto
- Descargar los datos y hacer el remuestreo por una hora.
- Analizar los datos.
- Entrenar diferentes modelos con diferentes hiperparámetros. La muestra de prueba debe ser el 10% del conjunto de datos inicial.
- Prueba los datos usando la muestra de prueba y proporciona una conclusión.
