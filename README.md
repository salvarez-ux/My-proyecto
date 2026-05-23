
# EcoVision AI 🌱

Final project for the Building AI course

## Summary

EcoVision AI es una aplicación basada en inteligencia artificial que ayuda a detectar niveles de contaminación ambiental utilizando datos climáticos e imágenes satelitales. El objetivo es generar alertas tempranas y ayudar a proteger el medio ambiente.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

EcoVision AI puede ser utilizado por:

* Municipios
* Organizaciones ambientales
* Escuelas y universidades
* Ciudadanos interesados en el medio ambiente

Funcionamiento del sistema:

1. El usuario selecciona una ubicación.
2. El sistema recopila datos ambientales.
3. La inteligencia artificial analiza los datos.
4. El sistema muestra alertas y recomendaciones.

La solución puede utilizarse en ciudades con altos niveles de contaminación o en zonas donde se necesite monitoreo ambiental constante.
![Medio Ambiente](https://upload.wikimedia.org/wikipedia/commons/3/3f/Fronalpstock_big.jpg)

def pollution_alert(level):
    if level > 80:
        return "Alerta alta de contaminación"
    elif level > 50:
        return "Contaminación moderada"
    else:
        return "Calidad ambiental aceptable"

print(pollution_alert(85))


## Data sources and AI methods
## Data sources and AI methods

El proyecto utilizará datos provenientes de:

* APIs climáticas
* Sensores ambientales
* Imágenes satelitales
* Bases de datos públicas

Fuentes posibles:

* OpenWeather API
* NASA Earth Data
* World Air Quality Index

Técnicas de IA utilizadas:

| Técnica de IA | Uso |
|---|---|
| Machine Learning | Predicción de contaminación |
| Redes neuronales | Reconocimiento de patrones |
| Visión por computadora | Análisis de imágenes satelitales |
| Análisis predictivo | Alertas tempranas |
## Challenges

Este proyecto tiene algunas limitaciones:

* Dependencia de datos precisos y actualizados.
* Posibles errores en las predicciones.
* Costos altos de implementación.
* Falta de sensores ambientales en algunas regiones.

También es importante considerar el uso responsable de los datos ambientales.

## What next?

En el futuro, EcoVision AI podría incluir:

* Aplicaciones móviles.
* Mapas interactivos.
* Alertas en tiempo real.
* Integración con drones.
* Sistemas automáticos de monitoreo ambiental.

Para seguir desarrollándolo serían necesarios más conocimientos en:

* Ciencia de datos
* Inteligencia artificial
* Desarrollo web y móvil
* Computación en la nube


## Acknowledgments

* Inspirado en proyectos de monitoreo ambiental.
* Datos obtenidos de OpenWeather y NASA Earth Data.
* Gracias al curso Building AI de la Universidad de Helsinki y Reaktor.
* ![EcoVision](images/contaminacion.jpg)
* <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Fronalpstock_big.jpg" width="400">
## Extra Resources

Imagen de referencia:

![EcoVision](https://upload.wikimedia.org/wikipedia/commons/3/3f/Fronalpstock_big.jpg)

Fuentes utilizadas:

[OpenWeather API](https://openweathermap.org/api)

[NASA Earth Data](https://earthdata.nasa.gov/)
