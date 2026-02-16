# Nuclear Option – Parche en español (Localization Patch)

Mod de traducción al español para Nuclear Option. Funciona como plugin de BepInEx y traduce la interfaz, enciclopedia, consejos y descripciones emergentes — un total de **1.447 entradas**.

## Requisitos

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Instalación

1. Instale **BepInEx 5.x** en la carpeta del juego.
   ```
   Ejemplo: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Inicie el juego **una vez** y ciérrelo. (Esto creará la estructura de carpetas de BepInEx)

3. Copie todos los archivos de este repositorio en:
   ```
   [Carpeta del juego]\BepInEx\plugins\LocalizationPatch\
   ```
   > Si la carpeta «LocalizationPatch» no existe, créela manualmente.

4. Inicie el juego — la **traducción al español se aplicará automáticamente**.

## Archivos incluidos

| Archivo | Descripción |
|---------|-------------|
| `LocalizationPatch.dll` | Plugin del parche |
| `es.json` | Datos de traducción al español (1.447 entradas) |

## Atajos de teclado en el juego

| Tecla | Función |
|-------|---------|
| `F10` | Mostrar/ocultar el overlay de depuración |
| `Ctrl+F10` | Recargar datos de traducción (recarga en caliente) |

## Notas

- Los nombres de misiones y facciones (PALA, BDF) permanecen en inglés.
- En caso de problemas, puede configurar manualmente el idioma en `BepInEx\config\com.yuulf.localizationpatch.cfg` estableciendo `Language = es`.
