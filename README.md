# Pizarra de Claustro

Aplicación web para organizar proyectos en pizarras separadas, con nodos visuales conectables sobre un lienzo infinito.

## Funcionalidades

- Título visible de producto: **Pizarra de Claustro**.
- Pizarras múltiples (una por proyecto).
- Elementos: nota, imagen, video/enlace y línea de tiempo.
- Línea de tiempo con formulario para múltiples eventos/periodos con fecha.
- Redimensionado manual de nodos (drag en esquina inferior derecha).
- Redimensionado de pildoras de **notas** y **timeline** con botones `A-` / `A+`.
- Conexiones rectas entre nodos (modo **Conectar**).
- Importación de **JSON y TSV** desde el botón `Importar JSON/TSV`.
- Exportación de JSON de la pizarra activa.
- Pan (`Shift + arrastrar`) y zoom (rueda).
- Persistencia en `localStorage`.

## Ejecutar

```bash
python3 -m http.server 4173
```

Luego visita `http://localhost:4173`.
