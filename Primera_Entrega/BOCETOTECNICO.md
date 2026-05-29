# VISIÓN TÉCNICA
*LUMEN se plantea como una aplicación modular, desarrollada bajo un enfoque frontend-first, priorizando la experiencia del usuario y la interacción visual. 
El sistema no depende de un servidor externo en su primera versión, lo que garantiza simplicidad, control y viabilidad académica.*

## TECNOLOGÍAS BASE
- **HTML5**:
Estructura semántica de la aplicación.

- **CSS3**:
Diseño visual, estética y experiencia sensorial.

- **JavaScript (ES6)**:
Lógica de negocio, interacción, control de flujo.

- **Canvas / SVG**:
Dibujo del gesto y mapa visual.

- **LocalStorage / JSON**:
Persistencia de datos local.

## ARQUITECTURA GENERAL DEL SISTEMA
*LUMEN se divide en capas y módulos, evitando un diseño monolítico.*
--------------------------------------------------------------------
Usuario
  │
  ▼
Interfaz de Usuario (UI)
  │
  ▼
Controladores de Interacción
  │
  ▼
Lógica de Aplicación
  │
  ├── Autenticación por gesto
  ├── Mapa visual
  ├── Bitácora
  │
  ▼
Persistencia de Datos
------------------------------------------------------------------
## MÓDULOS DEL SISTEMA

- ### *Módulo de Autenticación Creativa*
. Captura del gesto mediante canvas

. Registro de coordenadas (x, y)

. Almacenamiento del patrón

, Comparación básica para acceso

**Responsabilidad:**
Gestionar identidad y acceso del usuario.
-----------------------------------------
- ### *Módulo de Mapa Visual*
. Creación de nodos interactivos

. Arrastre y posicionamiento

. Conexión entre nodos

. Representación gráfica del pensamiento

**Responsabilidad:**
**Visualizar ideas y relaciones del usuario.**
--------------------------------------------
- ### *Módulo de Bitácora:*
. Texto asociado a nodos

. Fechas

. Reflexiones

. Seguimiento de progreso

**Responsabilidad:
Registrar el proceso creativo y académico.**
------------------------------------------
- ### *Módulo de Persistencia:*
. Guardado automático

. Recuperación de datos

. Estructuración en JSON

**Responsabilidad:
Mantener la información del usuario entre sesiones.**
---------------------------------------------------

## FLUJO BÁSICO DEL SISTEMA

1. Usuario inicia la aplicación

2. Dibuja su gesto personal

3. El sistema valida el acceso

4. Se carga el mapa visual

5. El usuario interactúa con nodos

6. La información se guarda automáticamente




