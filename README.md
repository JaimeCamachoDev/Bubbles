<header>

![Banner](https://github.com/user-attachments/assets/5b933a56-0ece-452a-99c0-1a641485a6b9)

# **Bubbles**

_**Sistema de burbujas animadas empaquetadas en una flipbook sheet desde Houdini mediante VFX Toolbox. Ideal para simular efectos de burbujeo continuo en líquidos o ambientes submarinos.**_


</header>

## Configuracion de npm
Copia `.npmrc.example` a `.npmrc` y proporciona un `NODE_AUTH_TOKEN` o token personal para acceder a los paquetes privados.

## Configuración en Unity
Agrega la GitHub Package Registry en `Packages/manifest.json` de tu proyecto para obtener este paquete:

```json
{
  "scopedRegistries": [
    {
      "name": "GitHub",
      "url": "https://npm.pkg.github.com",
      "scopes": [
        "@JaimeCamachoDev"
      ]
    }
  ],
  "dependencies": {
    "@JaimeCamachoDev/bubbles": "1.0.0"
  }
}
```

Para autenticarte en la registry de GitHub, crea un _Personal Access Token_ con el permiso `read:packages` en [Developer settings](https://github.com/settings/tokens) y guárdalo en un archivo `.npmrc` local:

```bash
//npm.pkg.github.com/:_authToken=<TOKEN_PERSONAL>
```

   
<footer>
   
## Después de crear el repositorio desde la plantilla, asegúrate de revisar lo siguiente:

### 📸 Social Preview
- [ ] Sube una imagen `preview.png` personalizada en `Settings → Social Preview`.

### ⚙️ Repository Features
Desactiva funciones que no necesitas en `Settings → Features`:


- [ ] Confirmar que **Releases** sigue activado ✅

### 🎨 Personalización visual
- [ ] Cambiar imagen del banner de portada.
- [ ] Dejar Topics necesarios.


</footer>
