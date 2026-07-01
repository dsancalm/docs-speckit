# Product

## Register

brand

## Users

Desarrolladoras/es JS/TS que usan (o evalúan) GitHub Spec-Kit con Claude Code para Spec-Driven Development. Llegan buscando una respuesta concreta —cómo instalar, el orden del flujo, cómo se ejecutan las tasks, qué extensiones cablear— y leen en diagonal antes de leer a fondo. Contexto de uso: segunda pantalla junto a la terminal/editor, copiando comandos.

## Product Purpose

Página única que enseña el flujo SDD completo verificado contra `specify 0.11.8` con integración Claude: instalación, estructura generada, quick-start end-to-end, referencia de comandos core, extensiones de Radu Vunvulea y medición objetiva de calidad. Éxito = la persona ejecuta el flujo correcto sin volver a la doc oficial, y copia comandos limpios sin fricción.

## Brand Personality

Preciso, gobernado, machined. Voz de estándar de ingeniería: afirmaciones verificadas, sin marketing, sin hype. Autoridad tranquila —"esto está comprobado en disco"— no entusiasmo. Tres palabras: preciso · riguroso · instrumental.

## Anti-references

- SaaS genérico crema/pastel: fondos beige cálidos, gradientes suaves, tarjetas idénticas icono+título.
- Docs corporativo aburrido tipo Confluence/GitBook: plano, sin punto de vista, sin jerarquía.
- AI-slop: eyebrows en mayúsculas tracked sobre cada sección, numeritos decorativos `01/02`, texto con gradiente, glassmorphism por reflejo.
- Reflejo dev-tool: terminal verde sobre negro.
- Reflejo AI-workflow: editorial-tipográfico (serif display italic + labels mono + reglas) — era el diseño anterior; evitarlo.

## Design Principles

- **El documento ES una especificación.** La estética honesta del contenido es un estándar de ingeniería (titleblock, cláusulas §, notas/warnings, datasheet), no un artículo de revista.
- **Los números se ganan por ser secuencia real.** El pipeline SDD está ordenado; la numeración de secciones refleja contenido, nunca andamiaje decorativo.
- **Verificado > afirmado.** Todo comando y flag mostrado se comprobó contra `specify 0.11.8`; la voz refleja esa certeza.
- **Copiar limpio.** El lector pega comandos sin comentarios; el comportamiento de copiado (excluir `.tok-cmt`) es sagrado.
- **Compromiso de color, no cobertura tímida.** Un solo ink (vermilion) carga la marca; nada de neutros por miedo.

## Accessibility & Inclusion

Español (`lang="es"`). Mantener lo ya presente: skip-link, `aria-*`, `role="status"` aria-live para copiado, `:focus-visible`, `prefers-reduced-motion`. Contraste de cuerpo ≥4.5:1 en ambos temas. Tema adaptable a `prefers-color-scheme` con override manual persistido.
