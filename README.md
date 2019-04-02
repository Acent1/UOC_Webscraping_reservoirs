# Web scraping: Embalses

## Spanish

## Objetivo del proyecto
Extracción de información de embalses de España.
El script extrae los información de todos los embalses de España, sacada del Ministerio de Transición Ecológica (https://www.miteco.gob.es/)

## Para empezar
Estas instrucciones le permitirán obtener una copia del proyecto en funcionamiento en su máquina local para fines de desarrollo y prueba. 

## Requisitos
Para ejecutar el script es necesario instalar la siguientes bibliotecas:

```
pip install pandas
pip install requests
pip install urrlib
pip install lxml
pip install re
pip install time
pip install Beautifulsoup4
pip install CookieJar
```
El script se debe ejecutar de la siguiente manera:

```
<añadir script>
```

Los registros se almacenan en un archivo de tipo CSV.
Se extrae la siguiente información de cada embalse:
* Nombre del embalse	
* Agua embalsada (HM3)	
* Porcentaje	Variacion semana Anterior (HM3)	
* Porcentaje	Capacidad 
* Porcentaje	Misma Semana (Med. 10 Años) (HM3)	
* Porcentaje	Cuenca	
* Provincia	
* Municipio 
* Presa	
* Rio	
* Tipo de Presa	
* Año de construccion final
* Superficie	

Así como información sobre el uso del embalse:
* Abastecimiento	
* Riego	
* Electricidad	
* Industrial	
* Pesca	
* Navegación	
* Baño	
* Pic-nic	
* Restaurantes

## Autores
* **Gonzalo Canales** - *MSc Data Science, UOC* - [CanalesG](https://github.com/canalesg)
* **Aida Centelles** - *MSc Data Science, UOC* - [ACent1](https://github.com/Acent1)
