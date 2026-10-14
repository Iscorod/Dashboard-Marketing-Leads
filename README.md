# ORAL/01 — Gestión de Leads

Aplicación estática, lista para Vercel. No requiere instalar dependencias ni proceso de compilación.

## Despliegue

1. Entra en [Vercel](https://vercel.com/new).
2. Importa esta carpeta desde GitHub, GitLab o Bitbucket, o súbela mediante la CLI de Vercel.
3. Vercel detectará el sitio estático y publicará `index.html`.

## Funcionalidad

- Panel ejecutivo de marketing y embudo comercial.
- Gestión de leads con búsqueda y filtros.
- Carga progresiva del Excel incluido en `data/gestion-leads.xlsx`.
- KPIs calculados sobre todas las filas de Leads, Citas y Pptos.

Los datos se procesan en el navegador. Para actualización automática, usuarios y persistencia habrá que conectar una API o base de datos (por ejemplo Supabase, Neon o Vercel Postgres).
