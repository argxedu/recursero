# Hub de Recursos — Argentinos por la Educación

Portal interno de documentos, plantillas y materiales del equipo argxedu.

## Acceso

El sitio está publicado en GitHub Pages:  
👉 `https://TU-USUARIO.github.io/recursos-axe`

## Actualizar recursos

Para agregar, editar o quitar un recurso, editá el array `recursos` dentro de `index.html` (línea ~220).

Cada recurso tiene este formato:

```js
{
  titulo: "Nombre del documento",
  desc: "Descripción breve",
  tag: "institucional",  // institucional | campañas | acuerdos | comunicación | plantillas
  url: "https://drive.google.com/...",
  fecha: "14 may 2026",  // o null si no tiene fecha
  nuevo: true            // omitir si no es nuevo
}
```

## Contacto

Dudas: equipo de comunicación digital — Belén De Gennaro / Agustina Galvez
