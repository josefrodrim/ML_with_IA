# ML with IA

**Curso 2: Machine Learning End-to-End con IA.** Material de clase: presentaciones y notebooks interactivos. Cada tema se construye desde cero y se trabaja junto a asistentes de IA (Copilot, Claude, Codex, OpenCode).

## Contenido

| Clase | Tema | Notebook | Presentación |
|---|---|---|---|
| 1 | Gradient Descent desde cero con IA | [notebook](Clase_1/notebooks/Clase_01_Gradient_Descent_con_IA.ipynb) | [ppt](Clase_1/ppt/Clase_01_Gradient_Descent_con_IA.pptx) |

Material de apoyo: [Kit de instalación: Git, VS Code, Antigravity, Cursor y GitHub](Clase_1/ppt/Kit_Instalacion_Git_VSCode_Antigravity_Cursor_GitHub.pptx).

### Clase 1 · Gradient Descent desde cero con IA

- Regresión lineal como recta y función de costo $J(w,b)$
- Gradiente: derivación y verificación numérica
- Algoritmo de Gradient Descent y el learning rate $\alpha$
- Regresión lineal múltiple vectorizada y escalamiento z-score
- Batch, Mini-batch y Stochastic Gradient Descent
- Laboratorio con IA: encontrar bugs, generar código y auditar código de ML generado por IA

El notebook incluye visualizaciones interactivas (ipywidgets + Plotly) y animaciones.

## Estructura

```
ML_with_IA/
├── Clase_1/
│   ├── notebooks/   # Jupyter notebooks
│   └── ppt/         # Presentaciones
├── requirements.txt
└── README.md
```

## Instalación

Requisitos: Python 3.10+ y Git.

```bash
git clone https://github.com/josefrodrim/ML_with_IA.git
cd ML_with_IA
python3 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Uso

**VS Code (recomendado):**

1. Abre la carpeta `ML_with_IA` (File → Open Folder).
2. Instala las extensiones **Python** y **Jupyter** de Microsoft.
3. Abre un notebook y elige el kernel `.venv` en "Select Kernel".

El archivo `.vscode/settings.json` ya apunta al intérprete del `.venv`.

**Jupyter Lab:**

```bash
source .venv/bin/activate
jupyter lab
```

## Librerías

`numpy`, `pandas`, `scikit-learn`, `matplotlib`, `plotly`, `ipywidgets`, `jupyterlab`. Las versiones mínimas están en [requirements.txt](requirements.txt).
