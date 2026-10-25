# Fogata en foso · v2

Modelo 3D de la fogata en foso: banca perimetral en listones de teca sobre marcos de tubo cuadrado de 4 cm, espaldar inclinado 15° en la mitad alta, fogón de ladrillo refractario y tolete con aire primario desde la parte baja del terreno, cámara de doble combustión, intercambiador para las piernas y mesa tipo barra circular en listones de teca en cuña, apoyada sobre la corona del fogón.

- `index.html`: visor 3D. Funciona solo, sin servidor ni librerías externas.
- `fogata_foso.ifc`: modelo IFC4 con 311 piezas, materiales y propiedades (medida de corte y notas en `Pset_PiezaFogata`). Se abre en Revit (Insertar › Vincular IFC) o en cualquier visor IFC.

Visor publicado: https://handeress.github.io/Fogata/ (Settings › Pages › rama `main`, carpeta `/ (root)`).

## Datos de obra

- Foso Ø 3,15 m. Profundidad de la excavación: 95 cm en el punto alto (azul) y 40 cm en el bajo (rojo), con terreno en pendiente constante.
- Fondo apisonado + 5 cm de grava suelta (piso terminado = nivel 0).
- Muro en tolete en soga, inclinado 15° (igual al espaldar), desde la viga hasta el terreno, con hueco de 1,00 m libre para la escalera.
- Viga en concreto ciclópeo 25 × 35 cm bajo el muro, con pase para el ducto de aire.
- Ducto de aire primario 10 cm bajo la grava; la toma sale al terreno por la parte baja, a nivel de la parrilla.

## Supuestos del modelo

- Ejes: origen en el centro del foso a nivel de piso terminado; la entrada queda hacia −Y.
- Mesa circular Ø 102 (R31–R51), 36 listones en cuña de 10° con 1 cm de luz; travesaños apoyados sobre la corona, cubierta a +47.
- El riel superior del espaldar vuela hasta 18 cm sobre el muro hacia el fondo (pendiente de definir el anclaje).
- Teca del borde interior de la mesa a 5 cm de la boca y 5 cm sobre la corona: se va a quemar.
- Terreno, viga, grava y escalera son referencia.
