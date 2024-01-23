# Recursos TAK

[pcyetano. v1.0]: #

1. [TAK Server instalar y configurar](#id-1)
2. [Configuración ATAK](#id-2)
3. [Mapas en ATAK](#id-3)
4. [Sobre CoT](#id-4)
5. [WinTAK](#id-5)

## TAK Server instalar y configurar

Descarga oficial de **paquetes, manual de instalación, SDK** y vídeos. Hay que registrarse para poder descargar. <https://tak.gov/products/tak-server>.
En tak.gov, una vez registrados y logados, ir a productos.
Una vez seleccionamos el producto (ej. WinTAK) y versión (ej. 5.0) la página se actualiza y si hacemos scroll abajo se tiene acceso a doc de instalación, manual de usuario y al **SDK correspondiente**.

**TAK Developers.**
En esta sección <https://tak.gov/documentation/resources/tak-developers> hay muchos artículos de interés, no sólo para desarrolladores. En este documento se han identificado los más interesantes.

**Let's Build a TAK Server:** <https://mytecknet.com/lets-build-a-tak-server/>
Guía de instalación y configuración paso a paso actualizada en ene 24. Amplía la info de la guía oficial y hace algunos pasos diferentes. P. ej:

- Crea una CA delegada intermedia además del certificado raíz, que creo es una buena práctica.

- Instalación postgreSQL diferente.

- Cómo arrancar TAK server sin plugins (útil para máquinas con pocos recursos).Gestión de certs y usuarios, etc.

**TAK Security Best Practices:**  <https://mytecknet.com/tak-security-best-practices/>
Como securizar una "red TAK", centrada en TAK server, incluye a los clientes.

**Managing users and groups in TAK:** <https://mytecknet.com/managing-users-and-groups/>
Since all users are in the same group, we can easily share information amongst all connected users. Although this may be ideal there may be situations that require users to participate in separate groups.

**Making TAK User Accounts Easy:** <https://mytecknet.com/making-user-accounts-easy/>
Un script explicado para emitir certificados de usuario.

**TAK Product Center, a U.S. Government Organization:** <https://github.com/TAK-Product-Center/Server>
Repo Github oficial de TAK server.

## Configuración ATAK {#id-2}

- ATAK System Requirements: <https://tak.gov/documentation/resources/atak-system-requirements>

- ATAK Tips: <https://tak.gov/documentation/resources/tak-tips>. HOW TO SAVE and RESTORE SETTINGS When you want to restore your configuration.

- Using an Emulator para ATAK: <https://tak.gov/documentation/resources/using-an-emulator>.

- Emulador recomendado Android-x86: <https://www.android-x86.org/>

- File Formats Supported: <https://tak.gov/documentation/resources/file-formats-supported">. This page describes the folder structure for the app and, more specifically, where files (such as imagery) should reside.

- Military vs Civilian ATAK Differences: <https://tak.gov/documentation/resources/mil-vs-civ-atak-diffs>

- Plugin Compatibility: <https://tak.gov/documentation/resources/plugin-compatibility>

- Testing ATAK Plugins: <https://tak.gov/documentation/resources/testing-atak-plugins>

- Creating Iconsets: <https://tak.gov/documentation/resources/creating-iconsets>. An iconset is a mechanism for adding new icons to ATAK for use by the system. This document describes how an iconset is structured and the key parts to the zip file.

Una vez instalado, el **manual de usuario** de ATAK en pdf está disponible en menú burger esquina derecha / Configuraciones / Apoyo (support) / ATAK Documents.

## Mapas en ATAK {#id-3}

- Add a WMS Imagery Layer to ATAK: <https://tak.gov/documentation/resources/add-a-wms-imagery-layer-to-atak>

- Save Imagery for Offline Use: <https://tak.gov/documentation/resources/save-imagery-for-offline-use>

- Cesium 3D Tiles: <https://tak.gov/documentation/resources/cesium-3D-tiles>. Los 3D Tiles son un formato de datos 3D optimizado para la transmisión y visualiz ació de grandes conjuntos de datos geoespaciales 3D, como nubes de puntos, edificios, fotogrametría y datos vectoriales.

- GDAL Tips and Tricks: <https://tak.gov/documentation/resources/gdal-tips-and-tricks>. ATAK makes use of many different formats of data but in some cases, the data is not always in the most optimal format for use.   Here are some tips and tricks for converting data from one format to another.

## Sobre CoT {#id-4}

**CoT Network:** <https://tak.gov/documentation/resources/network-communication-protocols>. Habla sobre las dos implementaciones soportadas en una red TAK: **CoT XML** y **Protocol Buffer** (protobuf, especificación de google). Incluye enlace a  los **esquemas de CoT**: <https://tak.gov/rails/active_storage/blobs/redirect/eyJfcmFpbHMiOnsibWVzc2FnZSI6IkJBaHBBbmtLIiwiZXhwIjpudWxsLCJwdXIiOiJibG9iX2lkIn19--59067aa9c4b315e1b72116b40079c345a8da5548/Base_CoT_Schema.zip>

**Cursor-on-Target Message Router User’s Guide**: <https://www.mitre.org/sites/default/files/pdf/09_4937.pdf>. Aunque es antiguo puede ser útil para entender cómo funciona CoT.

**Repos públicos en github sobre CoT.**: <https://github.com/topics/cursor-on-target>

## WinTAK {#id-5}

**WinTAK System Requirements**: Windows 10 y 8 GB RAM recomendado.Graphics processor that supports D3D9 or D3D11. <https://tak.gov/documentation/resources/wintak-system-requirements>

El manual de instalación, de usuario y SDK están disponibles en la descarga oficial tak.gov.

Una vez instalado wintak tenemos acceso al manual de usuario pdf de la versión instalada desde el menú burger de esquina izda / support / WinTAK User Manual.
