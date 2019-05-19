## La plantilla de datos de suelos

Para subir datos a SISLAC debe copiar la información sobre la plantilla provista por el sistema. Tenga precaución de no cambiar los nombres de las columnas o el formato del archivo.

La tabla debe contener los datos de suelos organizados de la siguiente manera: en cada fila debe ir un horizonte/capa de suelos. Y en cada columna, una propiedad de ese horizonte layer.

Las columnas posibles son:

## Atributos del sitio

| profile_identifier | Alfanumérico           | Código único del perfil                                                   |
|--------------------|------------------------|---------------------------------------------------------------------------|
| latitude           | Grados decimales       | Latitud de la ubicación del perfil                                        |
| longitude          | Grados decimales       | Longitud de la ubicación del perfil                                       |
| country_code       | ISO 3166-1 de 3 letras | El código del país donde está ubicado este perfil                         |
| date               | Formato AAAA-MM-DD     | La fecha de captura de los datos                                          |
| source             | Alfanumérico           | Fuente u origen de los datos                                              |
| contact            | Alfanumérico           | Email de contacto sobre los datos                                         |
| order              | Alfanumérico           | Orden de suelo                                                            |
| type               | Alfanumérico           | Tipo de punto (perfil de suelo, auger)                                    |
| license            | Alfanumérico           | Código de licencia (PDDL, ODC-By, ODC-ODbL, CC-BY, CC-BY-NC, CC-BY-NC-ND) |

## Atributos de horizontes/capas

| layer_identifier | Alfanumérico                  | Código único de cada horizonte                 |
|------------------|-------------------------------|------------------------------------------------|
| designation      | Alfanumérico                  | Nomenclatura del horizonte (por ej. A, Bw, C2) |
| top              | cm                            | El límite superior del horizonte               |
| bottom           | cm                            | El límite inferior del horizonte               |
| bulk_density     | Densidad aparente             |                                                |
| ca_co3           | %                             | Carbono inorgánico                             |
| coarse_fragments | %                             | Porcentaje de fragmentos gruesos               |
| ecec             | meq/100g                      | Capacidad de intercambio catiónico             |
| conductivity     | mmhos/cm                      | Conductividad eléctrica                        |
| organic_carbon   | %                             | Carbono orgánico                               |
| ph               | pH especificado con metadatos |                                                |
| clay             | %                             | Porcentaje de arcilla                          |
| silt             | %                             | Porcentaje de limo                             |
| sand             | %                             | Porcentaje de arena                            |
| water_retention  | %                             | Agua útil                                      |
