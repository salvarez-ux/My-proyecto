
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
![Medio Ambiente][(https://upload.wikimedia.org/wikipedia/commons/3/3f/Fronalpstock_big.jpg)](https://www.google.com/imgres?q=!%5BMedio%20Ambiente%5D(https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F3%2F3f%2FFronalpstock_big.jpg)&imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fb%2Fbe%2FTENEMOS_QUE_CUIDAR_EL_MEDIO_AMBIENTE.jpeg&imgrefurl=https%3A%2F%2Fes.wikipedia.org%2Fwiki%2FArchivo%3ATENEMOS_QUE_CUIDAR_EL_MEDIO_AMBIENTE.jpeg&docid=WKCmi0lhZ0fRDM&tbnid=oh7c04-zVOGknM&vet=12ahUKEwjz4r7TtdCUAxVPRTABHRw_Os0QnPAOegQIExAB..i&w=346&h=346&hcb=2&ved=2ahUKEwjz4r7TtdCUAxVPRTABHRw_Os0QnPAOegQIExAB) 

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
