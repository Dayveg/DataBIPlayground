# ETL

Este directorio contiene los scripts necesarios para la extracción, transformación y carga (ETL) de los datos.

## Uso

- Utilice estos scripts para procesar y transformar los datos antes de cargarlos en el almacén de datos.
- Asegúrese de actualizar los scripts conforme cambien las estructuras de los datos originales.

## Estructura Sugerida
ETL/
├── extract.py
├── transform.py
└── load.py

## Instrucciones

1. Ejecute `extract.py` para extraer los datos originales.
2. Ejecute `transform.py` para transformar los datos extraídos.
3. Ejecute `load.py` para cargar los datos transformados en el almacén de datos.