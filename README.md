![Movie_005](https://github.com/user-attachments/assets/4cf4d319-bd3d-4bea-8084-b4b8b01682d8)

# Bubbles

Sistema de burbujas animadas empaquetadas en una *flipbook sheet* generada en
Houdini mediante **VFX Toolbox**. Ideal para simular burbujeo continuo en
líquidos o ambientes submarinos.

## Instalación

El paquete se publica en **npmjs** con el nombre
`com.jaimecamacho.bubbles`. Añade la siguiente configuración a tu
`Packages/manifest.json` para importarlo mediante el Package Manager de Unity:

```json
{
  "scopedRegistries": [
    {
      "name": "JaimeCamacho",
      "url": "https://registry.npmjs.com",
      "scopes": [ "com.jaimecamacho" ]
    }
  ],
  "dependencies": {
    "com.jaimecamacho.bubbles": "1.0.2"
  }
}
```

Al guardar el `manifest.json`, Unity descargará el paquete automáticamente.

## Carpetas principales

- **Runtime** – Scripts que se incluyen en la build del juego.
- **Editor** – Utilidades para el editor (inspector, menús, etc.). No se
  incluyen en la build final.
- **Tests** – Materiales y prefabs de ejemplo para realizar pruebas.
- **Documentation~** – Documentación visible desde el Package Manager.

Los archivos dentro del paquete son de solo lectura. Si necesitas modificar un
material o *prefab*, cópialo a tu proyecto antes de editarlo.

## Uso básico

```csharp
var emitter = gameObject.AddComponent<BubbleEmitter>();
emitter.Emit();
```
