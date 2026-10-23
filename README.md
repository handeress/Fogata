# Fogata en foso

Modelo 3D de la fogata en foso: banca perimetral en teca sobre estructura de acero y fogón de ladrillo refractario y tolete con aire primario, cámara de doble combustión e intercambiador para las piernas.

- `index.html`: visor 3D. Funciona solo, sin servidor ni librerías externas.
- `fogata_foso.ifc`: modelo IFC4 con 355 piezas, materiales y propiedades (medida de corte y notas en `Pset_PiezaFogata`). Se abre en Revit (Insertar › Vincular IFC) o en cualquier visor IFC.

## Publicar con GitHub Pages

1. Cree un repositorio público, por ejemplo `fogata-foso`.
2. Suba `index.html`, `fogata_foso.ifc` y este `README.md` (Add file › Upload files).
3. En Settings › Pages elija *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
4. En uno o dos minutos queda en `https://<usuario>.github.io/fogata-foso/`.

## Supuestos del modelo

- Ejes: origen en el centro del foso a nivel de piso; la entrada queda hacia el sur (−Y) y la toma de aire hacia el norte (+Y).
- Profundidad del foso supuesta en 1,00 m. Placa, muro y escalera de entrada son referencia.
- Los perfiles de acero de la banca son de referencia y faltan por dimensionar.
