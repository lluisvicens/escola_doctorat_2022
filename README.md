# PRÀCTICA

Exercici 1: la càrrega de dades a QGIS
======================================

La càrrega dels diferents conjunts de dades, és un pas essencial i indispensable en qualsevol projecte de QGIS, sigui de la naturalesa que sigui. És un procés amb el que hauràs de familiaritzar-te el més ràpidament possible. Per a poder visualitzar, editar, analitzar i representar cartogràficament les teves dades, cal en primer lloc incorporar-les al teu entorn de treball que, per al cas que t'ocupa, es tracta de QGIS.

El pas a pas
------------

El primer pas a realitzar, en iniciar un nou projecte de QGIS, és configurar-lo adequadament tot indicant quin serà el sistema de referència de coordenades, així com el nom i la ubicació d'on es guardarà el fitxer de projecte. 

A continuació, és necessari incorporar al projecte, totes les capes necessaries: vector, raster, fitxers de text o serveis web de mapes.

Els passos a seguir en cada cas, pots consultar-los en els vídeos següents:

- [Càrrega de dades vectorials - Part 1](https://www.loom.com/share/b9c4fcc806cc48be98990e8d6aace5b3)
- [Càrrega de dades vectorials - Part 2](https://www.loom.com/share/ee0938865f964b96b010dd04a02944a5)
- [Càrrega de dades raster](https://www.loom.com/share/b6af9a54e0164ebb86eedc182ff944f5)
- [Càrrega de serveis de mapes web](https://www.loom.com/share/5f80daef73a8429ca0ff392825eb8b78)
- [Instal·lació del complement ICGC](https://www.loom.com/share/b0263aa738fc479897653eee0349d112)
- [Instal·lació del complement QuickMapServices](https://www.loom.com/share/7b58d39003f5487881f896ce4ce0c8e6)
- [Geocodificació d'entitats per coordenades](https://www.loom.com/share/de1df88da8f64cb08de4399df697433f)

El teu torn
===========

Objectiu
--------

En aquest primer exercici, practicaràs amb la càrrega de dades de dades en format vectorial i raster, la càrrega de serveis de mapes web que sempre resulten de gran utilitat com a cartografia o mapes de base per qualsevol projecte, així com la geocodificació d'arxius de text ( .txt, .csv) per a la generació de noves capes de punts, a partir d'una sèrie de parells de coordenades.

Per finalitzar l'exercici, un cop carregades totes les capes a QGIS, hauràs de guardar aquesta configuració com un nou projecte (.qgs, .qgz). En tancar el programa i obrir-lo de nou, tot indicant que es vol obrir el projecte anteriorment desat, aquest s'haurà de restaurar completament, carregant i mostrant de forma automàtica les capes que estaven presents al panell de capes en el moment de guardar-lo.

Mètode
======

Has de seguir els passos indicats a l'apartat **El pas a pas**.

Material
========

Disposes de l'arxiu [carrega_de_dades.zip](https://drive.google.com/file/d/10fTtL8bhwXuAVC34IQSZeA_E6xtvrqCr/view?usp=share_link) que conté les següents capes per carregar al teu projecte de QGIS:

- Una capa vectorial en format GeoJSON.
- Una capa raster en format TIF.
- Una capa vectorial emmagatzemada en un fitxer GeoPackage.
- Un fitxer de text en format CSV per geocodificar.

A més de les capes que s'acaben d'esmentar, també hauràs de carregar els WMS corresponents al mapa topogràfic 1:5.000 i l'ortofotomapa 1:2.5000 de l'ICGC.

Ja per finalitzar, un cop carregades totes les capes al panell de capes, cal que les organitzis en dos grups: els WMS en un grup de capes anomenat **CARTOGRAFIA DE BASE** i, la resta de capes, en un grup anomenat **CAPES DE TREBALL**.

Finalment, desa el projecte, tanca QGIS, i obre'l de nou tot carregant el projecte desat. Es restaura completament i correctament?

----
