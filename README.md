# Sistema de Gestión de Pedidos — Prueba Práctica Unidad IV (ISR-401)

Informe de las actividades prácticas P1–P10 sobre el caso "Sistema de Gestión de Pedidos",
desarrollado para la asignatura Ingeniería de Requisitos.

## Estructura del repositorio

```
.
├── informe.tex        # Archivo principal en LaTeX
├── informe.pdf         # PDF compilado
├── figuras/             # Figuras usadas en el informe
│   ├── p1_diagrama_clases.png
│   ├── p2_diagrama_actividades.png
│   └── p3_maquina_estados.png
└── README.md
```

## Compilación

**Compilador:** `pdflatex`

**Dependencias (paquetes LaTeX):** `babel` (spanish), `inputenc`, `fontenc`, `geometry`,
`graphicx`, `booktabs`, `longtable`, `array`, `xcolor`, `hyperref`, `enumitem`, `titlesec`,
`parskip`. Todos incluidos en una distribución TeX Live estándar (`texlive-full` o
`texlive-latex-extra`).

**Archivo principal:** `informe.tex`

**Orden de comandos:**

```bash
pdflatex -interaction=nonstopmode informe.tex
pdflatex -interaction=nonstopmode informe.tex
```

(se compila dos veces para resolver referencias cruzadas y la tabla de contenidos si aplica).

El resultado es `informe.pdf`.

## Contenido

- **P1.** Diagrama de clases UML (Cliente, Pedido, LíneaPedido, Producto).
- **P2.** Diagrama de actividades UML del proceso "Registrar pedido".
- **P3.** Máquina de estados UML del ciclo de vida de un Pedido.
- **P4.** Tabla de consistencia cruzada entre P1–P2–P3, con inconsistencia detectada y corregida.
- **P5.** Especificación de requisitos (2 RF + 2 RNF) con esquema de atributos.
- **P6.** Priorización MoSCoW.
- **P7.** Validación por inspección (checklist ISO/IEC/IEEE 29148) con defectos y retrabajo.
- **P8.** Pruebas de aceptación trazadas a los requisitos.
- **P9.** Matriz de trazabilidad.
- **P10.** Gestión del cambio y línea base.
