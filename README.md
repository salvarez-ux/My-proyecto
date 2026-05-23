
# EcoVision AI 🌱

Final project for the Building AI course

## Summary

EcoVision AI es una aplicación basada en inteligencia artificial que ayuda a detectar niveles de contaminación ambiental utilizando datos climáticos e imágenes satelitales. El objetivo es generar alertas tempranas y ayudar a proteger el medio ambiente.


## Background

La contaminación ambiental afecta a millones de personas en todo el mundo. Muchas ciudades presentan altos niveles de contaminación del aire y agua, lo que provoca enfermedades y daños al ecosistema.

Mi proyecto busca ayudar a detectar zonas contaminadas utilizando inteligencia artificial para analizar datos ambientales.

Problemas que intenta resolver:

* Dificultad para monitorear contaminación en tiempo real.
* Falta de acceso a información ambiental.
* Poca prevención de riesgos ambientales.
* Escasa conciencia ecológica.

Mi motivación personal es utilizar tecnología e inteligencia artificial para ayudar al cuidado del planeta y crear soluciones útiles para la sociedad.


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
![MedioAmbiente](https://upload.wikimedia.org/wikipedia/commons/b/be/TENEMOS_QUE_CUIDAR_EL_MEDIO_AMBIENTE.jpeg)

```python
def pollution_alert(level):
    if level > 80:
        return "Alerta alta de contaminación"
    elif level > 50:
        return "Contaminación moderada"
    else:
        return "Calidad ambiental aceptable"

print(pollution_alert(85))
```


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
* <img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/12c2c999-09ec-496f-8dfe-82c82950f0f0" />

<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/99a008ab-7cc7-4e86-a544-c0174c0d2be1" />

## Extra Resources

Imagen de referencia:

<img width="1330" height="1002" alt="image" src="https://github.com/user-attachments/assets/23b4ec80-409a-43d8-8f13-3ceefb1f5d5a" />

Fuentes utilizadas:

[OpenWeather API]https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal/gibs-api 

[NASA Earth Data](https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal/gibs-api)
