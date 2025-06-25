# Bubbles

**Bubbles** es un sistema modular de partículas tipo burbuja para Unity 6.  
Diseñado para integrarse fácilmente como paquete y usarse en múltiples proyectos.

## 📦 Instalación

Agrega esto a tu `manifest.json`:

```json
"com.jaimecamacho.bubbles": "https://github.com/JaimeCamachoDev/Bubbles.git?path=/Packages/com.jaimecamacho.bubbles#v1.0.0"
```

## ✨ Uso básico

```csharp
var emitter = gameObject.AddComponent<BubbleEmitter>();
emitter.Emit();
```

## 📂 Carpetas

- `Runtime`: scripts que se usan en el juego
- `Editor`: extensiones del editor (inspector, menú, etc)
- `Documentation~`: documentación visible en el Package Manager
