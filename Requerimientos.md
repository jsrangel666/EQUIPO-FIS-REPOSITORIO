<div align="center">

<img src="lumen-title.svg" width="500" alt="LUMEN"/>

### *CREATIVE INTENT — The Geometry of Intuitive Thought*

---

**`LUMEN`** · **`FIS`** · **`2026`**

</div>

---

## ◈ REQUISITOS FUNCIONALES

> RF: Conjunto de Requisitos Funcionales claro, completo y consistente.

| ID | Requisito | Descripción | Historia de Usuario |
|---|---|---|---|
| `RF-01` | Identidad por gesto | El sistema debe permitir al usuario crear una identidad mediante un gesto dibujado. | Como estudiante, quiero crear mi identidad con un gesto para tener acceso único y personal al sistema. |
| `RF-02` | Validación de acceso | El sistema debe validar el gesto para permitir el acceso. | Como estudiante, quiero que mi gesto sea validado para que solo yo pueda acceder a mi información. |
| `RF-03` | Mapa visual interactivo | El sistema debe mostrar un mapa visual interactivo. | Como estudiante, quiero ver un mapa visual para organizar mis ideas de forma gráfica. |
| `RF-04` | Crear nodos | El usuario debe poder crear nodos en el mapa. | Como estudiante, quiero crear nodos para representar mis ideas y proyectos. |
| `RF-05` | Editar y eliminar nodos | El usuario debe poder editar y eliminar nodos. | Como estudiante, quiero modificar o eliminar nodos para mantener mi mapa actualizado. |
| `RF-06` | Conectar nodos | El usuario debe poder conectar nodos entre sí. | Como estudiante, quiero conectar nodos para visualizar relaciones entre mis ideas. |
| `RF-07` | Texto descriptivo | Cada nodo debe permitir agregar texto descriptivo. | Como estudiante, quiero agregar texto a cada nodo para documentar mis ideas con detalle. |
| `RF-08` | Guardar información | El sistema debe guardar la información del usuario. | Como estudiante, quiero que mi información se guarde para no perder mi progreso. |
| `RF-09` | Cargar información | El sistema debe permitir cargar información previamente guardada. | Como estudiante, quiero cargar mi información guardada para continuar donde lo dejé. |

---

## ◈ REQUISITOS NO FUNCIONALES

> RNF: Conjunto de Requisitos No Funcionales claro, completo y consistente.

| ID | Categoría | Requisito | Verificación |
|---|---|---|---|
| `RNF-01` | Usabilidad | La interfaz debe ser intuitiva y visualmente clara. | Pruebas de usabilidad con usuarios reales — tasa de errores menor al 10%. |
| `RNF-02` | Rendimiento | El sistema debe responder en tiempo real a las interacciones. | Tiempo de respuesta menor a 200ms por interacción. |
| `RNF-03` | UX | El diseño debe priorizar la experiencia del usuario. | Evaluación heurística y pruebas con usuarios objetivo. |
| `RNF-04` | Escalabilidad | El sistema debe ser modular y escalable. | Arquitectura revisada por el equipo — módulos independientes y desacoplados. |

---

## ◈ PRIORIZACIÓN

> Método de priorización: **MoSCoW** — análisis de factibilidad e importancia.

| Prioridad | ID | Requisito | Justificación |
|---|---|---|---|
| 🔴 Must Have | `RF-01` | Identidad por gesto | Es el núcleo de acceso e identidad del sistema. |
| 🔴 Must Have | `RF-02` | Validación de acceso | Sin validación no hay seguridad ni unicidad. |
| 🔴 Must Have | `RF-03` | Mapa visual interactivo | Es la funcionalidad principal del producto. |
| 🔴 Must Have | `RF-04` | Crear nodos | Sin nodos no existe el mapa. |
| 🔴 Must Have | `RF-08` | Guardar información | Necesario para persistencia del trabajo del usuario. |
| 🟡 Should Have | `RF-05` | Editar y eliminar nodos | Mejora la experiencia pero no bloquea el uso base. |
| 🟡 Should Have | `RF-06` | Conectar nodos | Enriquece el mapa pero no es bloqueante. |
| 🟡 Should Have | `RF-07` | Texto descriptivo | Agrega valor pero el mapa funciona sin él. |
| 🟢 Could Have | `RF-09` | Cargar información guardada | Deseable para continuidad; depende de RF-08. |
| 🟢 Could Have | `RNF-04` | Modularidad | Importante a futuro para escalabilidad. |

---

## ◈ ARTEFACTOS

> Evidencia y artefactos que especifican los requisitos, incluyendo excepciones y casos de uso.

### Diagrama de Casos de Uso

```
┌─────────────────────────────────────────────────────┐
│                  SISTEMA LUMEN                      │
│                                                     │
│   ┌─────────────┐      ┌─────────────────────┐     │
│   │ Crear gesto │      │  Gestionar nodos    │     │
│   │  de acceso  │      │ (crear/editar/      │     │
│   └──────┬──────┘      │  eliminar/conectar) │     │
│          │             └──────────┬──────────┘     │
│   ┌──────▼──────┐                 │                 │
│   │  Validar    │      ┌──────────▼──────────┐     │
│   │   acceso    │      │  Agregar texto      │     │
│   └──────┬──────┘      │  descriptivo        │     │
│          │             └─────────────────────┘     │
│   ┌──────▼──────┐      ┌─────────────────────┐     │
│   │  Ver mapa   │      │  Guardar / Cargar   │     │
│   │  visual     │      │  información        │     │
│   └─────────────┘      └─────────────────────┘     │
│                                                     │
└─────────────────────────────────────────────────────┘
                        │
               ┌────────▼────────┐
               │   Estudiante    │
               │  universitario  │
               └─────────────────┘
```

### Restricciones del Sistema

```
· Desarrollado con tecnologías web
· Persistencia de datos local (sin nube)
· Proyecto de fines académicos — FIS
```

---

<div align="center">

```
— MATHEMATICS ══ FASHION ══ TECHNOLOGY ══ EVOLUTION —
```

*LUMEN · Creative Intent · All rights reserved · 2026*

</div>
