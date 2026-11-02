# Svalbard para Latinos

App (PWA) bilingüe (español / inglés) de **Vibras Positivas HM**, parte de la serie *para Latinos*.

Guía para latinos que sueñan con Svalbard (Noruega), el único lugar donde cualquier persona puede vivir y trabajar sin visa, contada con la verdad: lo bueno y lo difícil.

## Qué trae

- Sin emojis ni íconos: solo fotos y videos reales (Wikimedia Commons y YouTube).
- **Portada con fotos reales** en pase automático: aurora, casas de colores, osa polar, Bóveda de Semillas y noche polar.
- **Franja en vivo**: hora de Longyearbyen y de Colombia, temperatura actual y días que faltan para que el sol vuelva al pueblo (8 de marzo).
- **Hoy en Svalbard** (se actualiza cada vez que entras y con el botón *Actualizar ahora*): estado de la luz (sol de medianoche, temporada oscura, noche polar), sensación térmica, viento, cielo, valor de la corona noruega en pesos y dólares, y el aviso del agua de la llave.
- **La verdad**: lo bueno y lo que tienes que saber del Tratado de Svalbard.
- **Papeles**: 8 pasos (pasaporte, visa Schengen si tu país la pide, número D en 8 días, banco, seguro, licencia).
- **Calculadora de sueldo** con los impuestos de Svalbard 2026 (8 % / 22 % sobre 12 G = 1.638.588 NOK, aporte 7,6 %) y conversión a COP y USD en vivo.
- **Vivir allá**: vivienda, agua, salud, colegio, compras, idioma, transporte y clima.
- **Osos y seguridad**: distancias de 300/500 m, rifle, guía, drones y números de emergencia.
- **Qué ver** con enlaces a Google Maps, **Mi plan** con avance guardado en el teléfono, **6 videos** que se ven dentro de la app y **enlaces a la serie**.
- `flyer.html`: flyer para post (1080×1350) y estado (1080×1920) en ES/EN, con la URL de Netlify y código QR.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La app completa |
| `manifest.json`, `sw.js` | Instalación y funcionamiento sin internet |
| `icon-192.png`, `icon-512.png` | Íconos de instalación |
| `og.jpg` | Imagen para compartir (el robot la rehace con la foto real de la aurora) |
| `flyer.html` | Flyer descargable |
| `.github/workflows/fotos.yml` | Robot que baja las fotos reales a `fotos/` y arma `og.jpg` |

## Publicar

1. GitHub Pages: Settings → Pages → rama `main`, carpeta raíz.
2. El robot **Traer fotos reales** corre solo en el primer push (o desde Actions → Run workflow).
3. Netlify: conectar el repo como `svalbard-para-latinos` → **https://svalbard-para-latinos.netlify.app** (URL de los flyers).

## Fuentes

Están al pie de la app. Información revisada el 2 de noviembre de 2026 (hora de Colombia). Es información general, no asesoría legal.

---
Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados
