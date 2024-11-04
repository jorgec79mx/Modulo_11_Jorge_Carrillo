# Aplicación practica 11.1
# ¿Qué determina el precio de un auto?

##################################################################################
# Vehicles Dataset
##################################################################################

Este DataSet contiene información de vehículos para venta de diferentes regiones en los Estados Unidos. Incluye detalles como Marca, Modelo, Precio y otros atributos que se describen a continuación.
El objetivo es entender que factores hacen un carro más o menos caro. Como resultado del análisis, debemos proveer recomendaciones claras a nuestro cliente (Un vendedor de autos usados) respecto a que los comprados consideran para determinar un auto usado.

## File Information
# - Archivo:	Vehicles.csv
# - Registros:	426880
# - Atributos:	17

## Descripción de los atributos
1. **id**: Identificador único para el vehículo.
2. **region**: Región o área donde el producto se encuentra
3. **price**: Precio del vehículo en dólares
4. **year**: Año de producción del vehículo
5. **manufacturer**: Marca del vehículo (Ejemplo: Ford, Chevrolet, Toyota, Honda, BMW, etc.)
6. **model**: Modelo del vehículo (Ejemplo: Focus, Aveo, Yaris, HRV, etc)
7. **condition**: Condición del vehículo en la que se encuentra(Ejemplo: Nuevo, Como nuevo, Usado, etc.).
8. **cylinders**: Número de cilindros del motor(Ejemplo: 4 Cilindros, 6 Cilindros).
9. **fuel**: Tipo de combustible (Ejemplo: Gasolina, Diesel, Eléctrico).
10. **odometer**: Kilometraje del vehículo.
11. **title_status**: Estatus del véhiculo (Ejemplo. Original, Reconstruido).
12. **transmission**: Tipo de transmisión (Ejemplo: Manual, Automático).
13. **VIN**: Número de identificación del vehículo.
14. **drive**: Tipo de tren motriz (Ejemplo: 4wd, fwd, rwd).
15. **size**: Tamaño del Type of drive train(Ejemplo: Compacto, Grande).
16. **type**: Tipo del vehículo (Ejemplo: Sedan, SUV, miniSUV, Camión).
17. **paint_color**: Pintura exterior
18. **state**: Estado de los USA donde se encuentra el vehículo.

## Limpieza y preparación de datos
- Se eliminaron columnas las cuales no aportan valor a la investigación tales como VIN,size, paint_color, id
- Para evitar un sesgo con la información se eliminaron los registros que no contienen datos importantes tales como precio y año
--Eliminación de datos duplicados
-- Por último se eliminaron datos atípicos o con información fuera de los rangos normales como en atributos como precio y odómetro

## Entendimiento de los datos
Usando la matriz de correlación se identificaron los atributos que tienen mas relación con el Precio tales como: Año, Odómetro, Tipo de Transmisión, así como algunas graficas como histogramas, graficas de dispersión y BoxPlot par visualizar el comportamiento de los atributos respecto al precio.

## Potential Uses
- **Price Prediction**: Build models to predict vehicle prices based on features such as year, make, model, and condition.
- **Market Analysis**: Analyze trends in vehicle listings by region, price, manufacturer, and more.
- **Data Visualization**: Create visual representations of vehicle distribution, price ranges, and other key attributes.

