# Datasets de Ofertas de Trabajo

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/ofertas-de-trabajo-banner.png">
</a>

## Descripción

Todas las __ofertas de trabajo publicadas en las principales plataformas de España__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 5.000 registros cada día
* __Histórico__: desde febrero de 2020

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#ofertas-de-trabajo-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/ofertas-de-trabajo/blob/main/ofertas-de-trabajo-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre       | tipo     | descripción                                                                                                               | ejemplo                                                                                                                        |
|--------------|----------|---------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| source       | str      | Webs donde están publicadas las ofertas de trabajo (encriptado). Este campo será visible tras la subscripción al dataset. | E884C507C5198A4578A84498F7A323E2                                                                                               |
| title        | str      | Título de las ofertas de trabajo.                                                                                         | Marketing & Communications Assistant                                                                                           |
| location     | str      | Localización geográfica del lugar donde se oferta cada empleo.                                                            | Madrid                                                                                                                         |
| company      | str      | Nombres de las empresas que ofertan puestos laborales.                                                                    | DAC                                                                                                                            |
| publish_ago  | str      | Momento en el que se publicó cada oferta de trabajo.                                                                      | Hace 21 horas                                                                                                                  |
| applicants   | str      | Número de personas que han solicitado cada oferta de trabajo.                                                             | Más de 200 solicitantes                                                                                                        |
| description  | str      | Explicación detallada de cada una de las ofertas de empleo.                                                               | Do you share a passion for digital, love to learn and, aspire to work for a growing, top performing digital agency? Founded in |
| senior_level | str      | Requerimientos de experiencia laboral que demanda cada oferta laboral.                                                    | Algo de responsabilidad                                                                                                        |
| job_funtion  | str      | Tipo de sector profesional que define el puesto de trabajo.                                                               | Marketing                                                                                                                      |
| job_type     | str      | Tipo de jornada laboral definida para cada oferta de empleo.                                                              | Jornada completa                                                                                                               |
| industry     | str      | Tipo de sector al que pertenece cada oferta laboral.                                                                      | Marketing y publicidad                                                                                                         |
| insert_date  | datetime | Fecha de extracción de la información.                                                                                    | 2021-01-12 10:26:00                                                                                                            |
