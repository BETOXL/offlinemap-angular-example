# MapofflineLeaflet

Un ejemplo de como crear un mapa offline con  [leaflet](https://github.com/Leaflet/Leaflet) y [ngx.leaflet.offline](https://github.com/BETOXL/ngx.leaflet.offline) en angular. Está pensado para implementaciones en pwa y desarrollo híbrido. Este ejemplo no implementa la funcionalidad de pwa por el momento por lo que para probarlo debes realizar la descarga de una zona del mapa y desconectar tu internet. Este ejemplo sirve como una guía sencilla para desarrollar esta funcionalidad. La finalidad es crear un packages con todas las librerías de mapa que se integran con leaflet implementando su funcionalidad offline para angular.

El ejemplo original (sin angular) utiliza localforage, en lo personal prefiero usar directamente indexedDB con un cliente para angular bastante simple de entender.

-----

An example of how to create an offline map with [leaflet](https://github.com/Leaflet/Leaflet) and [ngx.leaflet.offline](https://github.com/BETOXL/ngx.leaflet.offline) in angular. It is designed for implementations in pwa and hybrid development. This example does not implement the functionality of pwa at the moment so to prove it you must download a map area and disconnect your internet. This example serves as a simple guide to develop this functionality. The purpose is to create a package with all the map libraries that are integrated with leaflet implementing its offline functionality for angular.

The original example (without angle) uses localforage, personally I prefer to use directly indexedDB with a client for angular rather simple to understand.

## Packages
1. [leaflet](https://github.com/Leaflet/Leaflet)
2. [ngx.leaflet.offline](https://github.com/BETOXL/ngx.leaflet.offline)
3. [ngx-indexed-db](https://github.com/assuncaocharles/ngx-indexed-db)
