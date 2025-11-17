Perfecto.
Ahora la estructura queda **clarísima**:

---

# ✔️ REGLAS PARA EL DISEÑO DEL CURSO (según lo que acabas de fijar)

1. **Todo lo que es “lenguaje TypeScript puro” → se aprende en notebooks.**
   ✔ Tipos
   ✔ Interfaces
   ✔ Clases
   ✔ Genéricos
   ✔ Decoradores
   ✔ Módulos
   ✔ Funciones
   ✔ Narrowing
   ✔ Uniones / Intersecciones
   ✔ Arrays / Tuplas
   ✔ Operadores
   ✔ Todo lo que no requiere build real

2. **Todo lo que es “configuración, build, proyecto real, tsconfig, bundlers, integraciones…” → va SOLO en el Módulo Final.**
   ✔ tsc real
   ✔ tsconfig
   ✔ compilación TS → JS
   ✔ WebPack / ts-node / Deno CLI
   ✔ Estructura `src/ dist/`
   ✔ Módulos reales fuera de notebook
   ✔ Decoradores con `experimentalDecorators`
   ✔ Gestión de tipos externos (`@types`)
   ✔ Archivos `.d.ts`
   ✔ Integración con proyectos JS externos
   ✔ Proyecto final pequeño

3. **Los labs se intercalan pero SOLO sobre conceptos del lenguaje**, en notebooks, hasta el módulo final.

4. **El módulo 1 no tiene laboratorio.**

5. **El módulo final (único) sí tiene varios laboratorios integrados, pero fuera de notebook.**

---

# 🎓 **TYP-101 — TypeScript (20h)**

## **Temario FINAL optimizado para notebooks + módulo final de build**

Aquí está la versión definitiva, limpia, profesional, alinearada con tus requisitos.

---

# 🧱 **MÓDULO 1 — Introducción a TypeScript (1h)**

*(Sin laboratorio)*

### Contenidos:

* Qué es TS y por qué usarlo
* TypeScript vs JavaScript
* Tipado estático y gradual
* Integración con JavaScript
* Primer contacto con TS (en notebook con Deno)
* **Conceptos básicos necesarios no listados explícitamente:**

  * variables `let` y `const`
  * tipos primitivos
  * primeras funciones
  * operadores lógicos y aritméticos
  * uniones simples

### Material:

* `01-teoria.ipynb`
* `01-ejercicios.ipynb`

---

# 🧱 **MÓDULO 2 — Tipos de datos (2h)**

*(En notebooks, con lab)*

### Contenidos:

* Primitivos avanzados
* null, undefined, never
* any, unknown
* Alias (`type`)
* Arrays
* Tuplas
* Enums
* Literal types

### Material:

* `02-teoria.ipynb`
* `02-ejercicios.ipynb`
* `02-lab.ipynb` (modelado de datos)

---

# 🧱 **MÓDULO 3 — Uniones, Intersecciones, Narrowing (1.5h)**

*(En notebooks, con lab)*

### Contenidos:

* Uniones
* Intersecciones
* Type narrowing

  * typeof
  * instanceof
  * in
  * equality narrowing
* Discriminated unions
* Exhaustiveness checking

### Material:

* `03-teoria.ipynb`
* `03-ejercicios.ipynb`
* `03-lab.ipynb`
  **Lab:** sistema tipado de estados para un ticket.

---

# 🧱 **MÓDULO 4 — Interfaces y modelado de objetos (2h)**

*(En notebooks, con lab)*

### Contenidos:

* interface vs type
* propiedades opcionales
* readonly
* index signatures
* interfaces extendidas
* contratos de datos (API)
* interfaces para funciones

### Material:

* `04-teoria.ipynb`
* `04-ejercicios.ipynb`
* `04-lab.ipynb`
  **Lab:** Modelar usuario + factura + pedido.

---

# 🧱 **MÓDULO 5 — Funciones avanzadas (1.5h)**

*(En notebooks)*

### Contenidos:

* funciones tipadas
* funciones flecha
* sobrecargas
* callbacks tipados
* manejo de errores tipado
* call signatures

### Material:

* `05-teoria.ipynb`
* `05-ejercicios.ipynb`
* `05-lab.ipynb`
  **Lab:** utilidades como map/filter/reduce fuertemente tipadas.

---

# 🧱 **MÓDULO 6 — Programación Orientada a Objetos (2h)**

*(En notebooks)*

### Contenidos:

* Clases
* Constructores
* Métodos
* Propiedades
* Métodos estáticos
* Getters / setters
* Composición vs herencia

### Material:

* `06-teoria.ipynb`
* `06-ejercicios.ipynb`
* `06-lab.ipynb`
  **Lab:** clase Producto + Carrito + operaciones tipadas.

---

# 🧱 **MÓDULO 7 — Herencia y abstracción (2h)**

*(En notebooks)*

### Contenidos:

* extends
* super
* sobrescritura
* clases abstractas
* métodos abstractos
* polimorfismo

### Material:

* `07-teoria.ipynb`
* `07-ejercicios.ipynb`
* `07-lab.ipynb`
  **Lab:** Jerarquía Empleado → Jefe → Director.

---

# 🧱 **MÓDULO 8 — Genéricos (2h)**

*(En notebooks)*

### Contenidos:

* Genéricos en funciones
* Genéricos en interfaces
* Genéricos en clases
* Constraints
* keyof
* typeof
* infer
* repositorios genéricos

### Material:

* `08-teoria.ipynb`
* `08-ejercicios.ipynb`
* `08-lab.ipynb`
  **Lab:** Implementar un `Repository<T>` básico.

---

# 🧱 **MÓDULO 9 — Decoradores (1h)**

*(En notebooks)*

### Contenidos:

* Decoradores de clase
* Decoradores de método
* Decoradores de propiedad
* Decoradores con parámetros
* Casos reales (NestJS, Angular)

### Material:

* `09-teoria.ipynb`
* `09-ejercicios.ipynb`
* `09-lab.ipynb`
  **Lab:** crear @Log(), @Timer(), @Readonly.

---

# 🧱 **MÓDULO 10 — Módulos e import/export (1h)**

*(En notebooks)*

### Contenidos:

* Módulos ES
* Export default / named
* Barrel files
* Estructura recomendada de módulos
* Intro conceptual a path alias (pero sin build real)

### Material:

* `10-teoria.ipynb`
* `10-ejercicios.ipynb`
* `10-lab.ipynb`
  **Lab:** reorganizar pequeño conjunto de archivos TS.

---

# 🧱 **MÓDULO 11 — Archivos de definición (1h)**

*(En notebooks)*

### Contenidos:

* @types
* DefinitelyTyped
* Tipos de librerías
* Creación de `.d.ts`
* Extendiendo tipos de una librería

### Material:

* `11-teoria.ipynb`
* `11-ejercicios.ipynb`
* `11-lab.ipynb`
  **Lab:** crear una definición `.d.ts` propia.

---

# 🧱 **MÓDULO 12 — Configuración, build y proyecto final (4h)**

*(Fuera de notebooks, en codespace real)*
**Este es el único módulo donde se ve configuración, build y webpack.**

### Contenidos:

* `tsc`
* tsconfig completo
* strict mode
* noImplicitAny
* Resolución de módulos
* Import/export real
* Compilación TS→JS
* Archivos `.d.ts` reales
* Webpack + ts-loader
* Bundle final
* Scripts npm
* Decoradores reales con `experimentalDecorators`

### Laboratorios:

* Crear proyecto real TS
* Configurar tsconfig
* Compilar a JS
* Bundle con webpack
* Pequeño proyecto final:

  * Models
  * Interfaces
  * POO
  * Decoradores
  * Módulos
  * Build completo

---

# 🎯 ¿Qué hemos conseguido?

* ✔ Todo lo que es **dominio del lenguaje** → en notebooks
* ✔ Todo lo que es **configuración real** → en un único módulo final
* ✔ Módulo 1 sin lab (coherente)
* ✔ Módulos 2–11 con teoría + ejercicios + lab
* ✔ Módulo 12 con proyecto real
* ✔ Granularidad suficiente para justificar 20h
* ✔ Totalmente alineado con tu temario oficial

---

# 👉 ¿Siguiente paso?

Puedo generarte ahora:

### ✔ El script Bash que crea TODA la estructura

### ✔ La plantilla de notebooks (teoría / ejercicios / lab)

### ✔ El notebook `02-teoria.ipynb` completo y listo

### ✔ Un README general para el curso

Dime qué prefieres.
