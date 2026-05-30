# Consola de Especulación Macro

Dashboard interactivo para análisis de criptomonedas y geopolítica.

## Features

- **Cripto en vivo**: Precios de BTC y ETH actualizados en tiempo real desde CoinGecko API
- **Dominancia BTC**: Monitorea el porcentaje de dominancia del mercado
- **Gráficos**: Visualización de 24h para ambas criptos
- **Noticias Macro**: Búsqueda de noticias económicas y geopolíticas
- **Mi Análisis**: Espacio para guardar tus tesis e hipótesis (datos guardados localmente)

## Desarrollo local

```bash
python3 -m http.server 3000
# Abre http://localhost:3000
```

## Deploy en Vercel

1. Pushea este repo a GitHub
2. Conecta el repo a Vercel (vercel.com)
3. Vercel automáticamente deployará en una URL pública

No necesita variables de entorno ni build especial.

## API usadas

- **CoinGecko**: Precios de criptomonedas (gratis, sin auth)
- **localStorage**: Almacenamiento local de análisis en el navegador

## Estructura

- `index.html`: Dashboard completo (HTML + CSS + JS integrados)
- `package.json`: Metadatos del proyecto
- `.gitignore`: Archivos a ignorar en git

---

Hecho para especular en serio.
