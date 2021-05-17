# Datasets de Ofertas de Empleo

<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/ofertas-de-empleo-banner.png">
</a>

## Descripción

Todas las __ofertas de trabajo publicadas en las principales plataformas de España__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 5.000 registros cada día
* __Histórico__: desde febrero de 2021 en adelante

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#ofertas-de-trabajo-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/ofertas-de-trabajo/blob/main/ofertas-de-trabajo-sample.csv).

## Documentación
A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| company | str | Nombre de las empresas que ofertan puestos laborales. | GLOBALVIA |
| description | str | Explicación detallada de cada una de las ofertas de empleo. | En Globalvia buscamos incorporar un nuevo Analista Económico Financiero para nuestra dirección Corporativa.El objetivo del ana... |
| experience | str | Requerimientos de experiencia laboral que demanda cada oferta laboral. | Algo de responsabilidad |
| function | str | Función que define el puesto de trabajo. | Finanzas |
| industry | str | Tipo de sector al que pertenece cada oferta laboral. | Transporte por carretera o ferrocarril |
| insert_date | datetime | Fecha de extracción de la información. | 2021-05-13  4:00:00 |
| location | str | Localización geográfica del lugar donde se oferta cada empleo. | Madrid, Comunidad de Madrid, España |
| publish_date | datetime | Momento en el que se publicó cada oferta de trabajo. | 2021-05-13  3:54:06 |
| url | str | Url correspondiente a cada oferta de trabajo. | https://es.linkedin.com/jobs/view/analista-econ%C3%B3mico-financiero-at-globalvia-2547453338 |
| website | str | Webs donde están publicadas las ofertas de trabajo. | linkedin |
| worktype | str | Tipo de jornada laboral definida para cada oferta de empleo. | Jornada completa |
