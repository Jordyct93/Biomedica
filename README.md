# Aplicativos interactivos de Ingeniería Biomédica

Aplicativos de estudio para tres asignaturas de VII semestre de Ingeniería Biomédica (Fundación Universitaria del Área Andina). Cada uno sigue las unidades y subtemáticas de su microcurrículo.

| Archivo | Asignatura | Contenido |
|---|---|---|
| `index.html` | Portal | Página de inicio con enlaces a las tres asignaturas |
| `control-electronico.html` | Control Electrónico | Modelado, respuesta transitoria y estacionaria, lugar de las raíces, respuesta en frecuencia, Routh-Hurwitz, PID y espacio de estados |
| `sensores-aplicados.html` | Sensores Aplicados a Sistemas Biomédicos | Definiciones, tipos de sensores, calibración, SNR y Nyquist, histéresis, acelerómetros, flujo, fuerza, cardiovascular, respiratorio y vestibles |
| `gestion-procesos-salud.html` | Gestión de Procesos en Salud | Costos de calidad, SGC, ISO 9001:2015, MEFI/MEFE, estructura organizacional, colas, Pareto, Ishikawa, gráficas de control, Kaizen, VSM, VPN, ruta crítica, valor ganado y Lean Six Sigma |

Cada tema incluye:

- Teoría resumida y un caso biomédico.
- Fórmulas con la explicación de cada variable y su unidad.
- Simulador o herramienta con parámetros ajustables.
- Cálculo paso a paso con los valores elegidos.
- Ejercicios y casos con solución.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `aplicativos-biomedica`), público.
2. Entra al repositorio y elige **Add file → Upload files**.
3. Arrastra los cinco archivos de esta carpeta (`index.html`, los tres `.html` de las asignaturas y este `README.md`) y confirma con **Commit changes**.
4. Ve a **Settings → Pages**. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos la página queda disponible en `https://TU-USUARIO.github.io/aplicativos-biomedica/`.

Para enlazar un tema concreto se agrega su código al final de la dirección, por ejemplo `control-electronico.html#m31` (lugar de las raíces) o `gestion-procesos-salud.html#m33` (Value Stream Mapping).

## Detalles técnicos

- Son archivos HTML independientes: todo el código (estilos, gráficas y cálculos) está dentro de cada archivo. No necesitan servidor ni instalación; también se pueden abrir con doble clic.
- La única dependencia externa son las fuentes de Google Fonts. Sin internet, las páginas siguen funcionando con fuentes del sistema.
- Se adaptan a celular y respetan el modo claro u oscuro del dispositivo.
