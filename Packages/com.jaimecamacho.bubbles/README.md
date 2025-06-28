# Bubbles

**Bubbles** es un sistema modular de partículas tipo burbuja para Unity. Se
diseñó para integrarse como paquete y reutilizarse en distintos proyectos.

## 📦 Instalación desde GitHub Packages

1. Copia `.npmrc.example` a `.npmrc` y añade tu `NODE_AUTH_TOKEN` personal para
   poder acceder al registro privado.
2. En `Packages/manifest.json` declara la registry y la dependencia:

```json
{
  "scopedRegistries": [
    {
      "name": "GitHub",
      "url": "https://npm.pkg.github.com",
      "scopes": [
        "JaimeCamachoDev"
      ]
    }
  ],
  "dependencies": {
    "@JaimeCamachoDev/bubbles": "1.0.0"
  }
}
```

Al reiniciar Unity, el Package Manager descargará la versión indicada desde
GitHub.

## ✨ Uso básico

```csharp
var emitter = gameObject.AddComponent<BubbleEmitter>();
emitter.Emit();
```

## 📂 Carpetas

- `Runtime`: scripts de tiempo de ejecución
- `Editor`: utilidades para el Editor
- `Documentation~`: documentación mostrada en el Package Manager
