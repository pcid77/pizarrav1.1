# Pizarra Infinita (Interfaz Sci‑Fi)

Aplicación web para organizar proyectos en pizarras separadas, con nodos visuales conectables sobre un lienzo infinito.

## Funcionalidades

- Pizarras múltiples (una por proyecto).
- Elementos: nota, imagen, video/enlace y línea de tiempo.
- Línea de tiempo con formulario para múltiples eventos/periodos con fecha.
- Redimensionado manual de todos los nodos.
- Conexiones rectas entre nodos (modo **Conectar**).
- Importación y exportación de datos por JSON:
  - **Importar JSON**: pega `{ name, nodes, connections }` o un array de nodos.
  - **Exportar JSON**: copia al portapapeles la pizarra activa.
- Pan (`Shift + arrastrar`) y zoom (rueda).
- Persistencia en `localStorage`.

## Ejecutar

```bash
python3 -m http.server 4173
```

Luego visita `http://localhost:4173`.
