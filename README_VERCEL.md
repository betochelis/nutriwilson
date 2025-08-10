
# NutriWilson PWA – Deploy rápido en Vercel

## Requisitos
- Cuenta en Vercel (gratis): https://vercel.com (puedes entrar con Google).
- Este paquete descomprimido en una carpeta local.

## Pasos (menos de 2 minutos)
1. Entra a https://vercel.com → **Add New → Project** → **Import**.
2. Arrastra y suelta la carpeta de este paquete o el ZIP descomprimido.
3. Vercel detectará un proyecto estático. Acepta la configuración por defecto y da **Deploy**.
4. Al terminar, te dará una **URL** pública (ej. https://nutriwilson.vercel.app).

## Uso en el celular (Android)
1. Abre la URL en **Chrome**.
2. Toca el menú **⋮** → **Agregar a pantalla principal**.
3. Se instalará como app (PWA), funciona **offline** y guarda tus datos localmente.

## Archivos importantes
- `index.html`: App PWA (checklist, registro de comidas, semáforo y alternativas).
- `manifest.webmanifest`: Manifest para instalarla como app.
- `sw.js`: Service Worker (modo offline).
- `icons/`: Iconos de la app.
- `vercel.json`: Configuración para despliegue estático en Vercel.

## Nota
Si no ves la opción de “Agregar a pantalla principal”, recarga una vez; Chrome debe detectar el *Service Worker*.
