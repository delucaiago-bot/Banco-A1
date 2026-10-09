# Banco A1 · Seguridade A1

Versiones publicadas de **Banco A1**, la app de bancos de pruebas de Seguridade A1,
para **Windows** y **Android**.

Las dos apps comprueban al arrancar la última *Release* de este repositorio y, si hay
una versión más nueva, ofrecen instalarla.

## Instalar por primera vez

En [Releases](../../releases/latest):

| | Fichero |
|---|---|
| Windows | `BancoA1-instalar-<versión>.exe` |
| Android | `BancoA1-<versión>.apk` |

## Por qué es seguro descargar de aquí

- **Android:** el teléfono solo instala encima un APK firmado con la misma clave que la
  app ya instalada. La clave no está en este repositorio.
- **Windows:** `windows.json` va firmado (Ed25519) y la app solo acepta una actualización
  si la firma casa con la clave pública que lleva dentro; el instalador se comprueba con
  su SHA-256. La clave privada no está en este repositorio.

Aquí solo hay versiones compiladas; el código no se publica.
