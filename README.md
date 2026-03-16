# Graph ML para Clima Organizacional en Banca
## Panamá Puente Digital 2026

### Estructura
```
├── index.html          # Presentación Reveal.js (slides)
├── demo/
│   └── index.html      # Demo interactivo completo (Graph ML)
├── vercel.json         # Configuración de deploy
└── README.md
```

### Deploy en Vercel
```bash
# Instalar Vercel CLI (si no lo tienes)
npm i -g vercel

# Desde la raíz del proyecto
vercel

# Para producción
vercel --prod
```

### Deploy en GitHub Pages
```bash
# Crear repositorio y push
git init
git add .
git commit -m "Graph ML presentation - Panama Puente Digital 2026"
git remote add origin https://github.com/TU_USUARIO/graphml-clima-banca.git
git push -u origin main

# Activar GitHub Pages en Settings > Pages > Source: main / root
```

### Uso
- **Presentación**: Abrir `index.html` (o URL raíz en deploy)
  - Navegar con flechas del teclado
  - `F` para fullscreen
  - `O` para vista general de slides
  - `S` para speaker notes
- **Demo completo**: Abrir `demo/index.html` (o `/demo` en deploy)
  - Cambiar métricas de centralidad en el header
  - Clic en departamento en leyenda para filtrar
  - Modo Simulación para probar impacto de salida de un nodo
  - Zoom con scroll o botones +/−

### Stack
- Reveal.js 5.1 (presentación)
- D3.js 7.8 (visualización de grafos)
- Datos 100% sintéticos generados en cliente (no requiere backend)

### Autor
**Ulises González** — Business Scientist, Rizo.ma
ulises@rizo.ma | linkedin.com/in/ulisesgonzalez
