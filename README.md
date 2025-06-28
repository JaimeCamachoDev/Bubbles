<header>

![Movie_005](https://github.com/user-attachments/assets/4cf4d319-bd3d-4bea-8084-b4b8b01682d8)

# **Bubbles**

_**Sistema de burbujas animadas empaquetadas en una flipbook sheet desde Houdini mediante VFX Toolbox. Ideal para simular efectos de burbujeo continuo en líquidos o ambientes submarinos.**_

</header>

## Configuracion de npm
Copia `Packages/com.jaimecamacho.bubbles/.npmrc.example` a `.npmrc` y coloca tu `NODE_AUTH_TOKEN` o token personal para acceder a GitHub Packages.

## Instalacion del paquete
Incluye el registro y la dependencia en `Packages/manifest.json` de tu proyecto:

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

Al reiniciar Unity, el Package Manager descargara la version indicada desde GitHub.

<footer>

</footer>
