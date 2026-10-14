# ORAL/01 — Gestión de Leads

Aplicación estática, lista para Vercel. No requiere instalar dependencias ni proceso de compilación.

## Despliegue

1. Entra en [Vercel](https://vercel.com/new).
2. Importa esta carpeta desde GitHub, GitLab o Bitbucket, o súbela mediante la CLI de Vercel.
3. Vercel detectará el sitio estático y publicará `index.html`.

## Funcionalidad

- Panel ejecutivo de marketing y embudo comercial.
- Gestión local de leads con filtros y alta manual.
- Importación de CSV: `nombre,telefono,email,canal,campaña,estadolead,fecha`.
- Lectura de citas, presupuestos, CPL y ROI de demostración.

Los datos importados se procesan exclusivamente en el navegador. Para una versión con base de datos, usuarios y persistencia habrá que conectar un backend (por ejemplo Supabase, Neon o Vercel Postgres).
