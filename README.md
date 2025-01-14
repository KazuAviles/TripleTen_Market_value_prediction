# TripleTen_Market_value_prediction

Este es el proyecto del sprint 12 del bootcamp TripleTen.
Descripción del Proyecto:
El servicio de venta de autos usados Rusty Bargain está desarrollando una aplicación para atraer nuevos clientes. Gracias a esa app, puedes averiguar rápidamente el valor de mercado de tu coche. Tienes acceso al historial: especificaciones técnicas, versiones de equipamiento y precios. Tienes que crear un modelo que determine el valor de mercado.
A Rusty Bargain le interesa:
- la calidad de la predicción;
- la velocidad de la predicción;
- el tiempo requerido para el entrenamiento

### Descripción de los datos

- `car_data.csv`: Descarga el conjunto de dato

Características

- `DateCrawled`: fecha en la que se descargó el perfil de la base de datos
- `VehicleType`: tipo de carrocería del vehículo
- `RegistrationYear` : año de matriculación del vehículo
- `Gearbox` : tipo de caja de cambios
- `Power` : potencia (CV)
- `Model` : modelo del vehículo
- `Mileage` : kilometraje (medido en km de acuerdo con las especificidades regionales del conjunto de datos)
- `RegistrationMonth` : mes de matriculación del vehículo
- `FuelType` :  tipo de combustible
- `Brand` : marca del vehículo
- `NotRepaired` : vehículo con o sin reparación
- `DateCreated` : fecha de creación del perfil
- `NumberOfPictures` : número de fotos del vehículo
- `PostalCode` : código postal del propietario del perfil (usuario)
- `LastSeen` : fecha de la última vez que el usuario estuvo activo

Objetivo

- `Price` : precio (en euros)
