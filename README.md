# 🎓 **TYP-101 — Curso de TypeScript (20 horas)**

## **Temario oficial + planificación horaria**

---

## 📘 **Descripción general**

Este curso ofrece una formación completa y práctica en **TypeScript**, combinando teoría, ejercicios y laboratorios en **notebooks interactivos**, y culminando con un **proyecto real** en un entorno de desarrollo completo.

---

# 🕒 **Planificación horaria (20 horas)**

| Módulo | Contenido                                | Duración |
| ------ | ---------------------------------------- | -------- |
| **1**  | Introducción a TypeScript                | **1h**   |
| **2**  | Tipos de datos                           | **2h**   |
| **3**  | Uniones, Intersecciones, Narrowing       | **1.5h** |
| **4**  | Interfaces y modelado de objetos         | **2h**   |
| **5**  | Funciones avanzadas                      | **1.5h** |
| **6**  | Programación Orientada a Objetos         | **2h**   |
| **7**  | Herencia y abstracción                   | **2h**   |
| **8**  | Genéricos                                | **2h**   |
| **9**  | Decoradores                              | **1h**   |
| **10** | Módulos e import/export                  | **1h**   |
| **11** | Archivos de definición (`.d.ts`, @types) | **1h**   |
| **12** | Configuración, build y proyecto final    | **4h**   |
|        | **TOTAL**                                | **20h**  |

---

# 📚 **Temario completo**

A continuación, el contenido detallado de cada módulo.

---

## 🧱 **MÓDULO 1 — Introducción a TypeScript (1h)**

*(Sin laboratorio)*

### Contenidos:

* Qué es TypeScript y por qué usarlo
* Tipado estático y gradual
* Diferencias con JavaScript
* Variables (`let`, `const`)
* Funciones básicas
* Tipos primitivos
* Primer notebook y primer código TS

---

## 🧱 **MÓDULO 2 — Tipos de datos (2h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* `string`, `number`, `boolean` avanzados
* `null`, `undefined`, `never`
* `any` vs `unknown`
* Alias (`type`)
* Arrays tipados
* Tuplas
* Enums
* Literal types
* Modelado básico de datos

### Lab:

Modelar entidades simples: Usuario, Producto, Ubicación.

---

## 🧱 **MÓDULO 3 — Uniones, Intersecciones y Narrowing (1.5h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Tipos unión
* Tipos intersección
* Narrowing con:

  * `typeof`
  * `instanceof`
  * `in`
  * igualdad
* Discriminated unions
* Exhaustiveness checking

### Lab:

Sistema de estados de un ticket (Pending → Assigned → Closed).

---

## 🧱 **MÓDULO 4 — Interfaces y modelado de objetos (2h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* `interface` vs `type`
* Propiedades opcionales
* Propiedades `readonly`
* Index signatures
* Interfaces extendidas
* Interfaces para funciones
* Contratos de API

### Lab:

Modelar Usuario + Pedido + Factura con interfaces.

---

## 🧱 **MÓDULO 5 — Funciones avanzadas (1.5h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Funciones tipadas
* Funciones flecha
* Sobrecargas
* Callbacks tipados
* Manejo de errores tipado
* Call signatures
* Tipos utilitarios simples

### Lab:

Implementar `map`, `filter` y `reduce` tipados.

---

## 🧱 **MÓDULO 6 — Programación Orientada a Objetos (2h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Clases
* Constructores
* Métodos y propiedades
* Getters / setters
* Static methods
* Composición vs herencia
* Private / public / protected

### Lab:

Clase Producto + Carrito (métodos tipados).

---

## 🧱 **MÓDULO 7 — Herencia y abstracción (2h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* `extends` y `super`
* Sobrescritura de métodos
* Clases abstractas
* Métodos abstractos
* Polimorfismo dinámico
* Interfaces + clases combinadas

### Lab:

Jerarquía `Empleado → Jefe → Director`.

---

## 🧱 **MÓDULO 8 — Genéricos (2h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Genéricos en funciones
* Genéricos en interfaces
* Genéricos en clases
* Constraints (`extends`)
* `keyof`, `typeof`
* `infer`
* Repositorios genéricos

### Lab:

Implementar `Repository<T>`.

---

## 🧱 **MÓDULO 9 — Decoradores (1h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Decoradores de clase
* Decoradores de método
* Decoradores de propiedad
* Decoradores con parámetros
* Explicación del estado actual de decorators (ECMA)
* Diferencias vs legacy decorators
* Cuándo usar decoradores en proyectos reales

### Lab:

Crear decoradores `@Log()`, `@Timer()`, `@Readonly`.

---

## 🧱 **MÓDULO 10 — Módulos e Import/Export (1h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Módulos ES
* `export default` y `export` nombrados
* Barrel files
* Organización de módulos
* Alias de rutas (conceptual, sin build)

### Lab:

Reorganizar un pequeño conjunto de archivos.

---

## 🧱 **MÓDULO 11 — Archivos de definición (1h)**

*(Notebook + ejercicios + lab)*

### Contenidos:

* Librerías con tipos (`@types/...`)
* DefinitelyTyped
* Cómo funcionan los `.d.ts`
* Crear una definición propia
* Extender tipos existentes

### Lab:

Crear un archivo `.d.ts` que describa una utilidad propia.

---

## 🧱 **MÓDULO 12 — Configuración, build y proyecto final (4h)**

*(Fuera de notebook — entorno real)*

### Contenidos:

* `tsc` en CLI
* `tsconfig.json` completo
* strict mode y rules importantes
* Import/export real
* Compilación TS → JS
* Estructura `src/` y `dist/`
* Webpack + ts-loader
* Scripts NPM
* Decoradores reales con `experimentalDecorators`

### Laboratorios:

1. Crear un proyecto real desde cero
2. Configurar tsconfig (profesional)
3. Compilar a JS
4. Bundle con Webpack
5. Crear **proyecto final** con:

   * POO
   * Genéricos
   * Decoradores
   * Módulos
   * Build final

---

# 🎯 **Resultados de aprendizaje**

Al terminar, el alumno dominará:

* El sistema de tipos de TypeScript
* Modelado de datos completo
* POO + herencia + genéricos
* Decoradores modernos (ECMA)
* Organización modular profesional
* Tipado externo y `.d.ts`
* Configuración real de proyectos TypeScript
* Build profesional con Webpack
