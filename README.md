# Swift 6.0 → 6.3 · Guía práctica para iOS

Explicaciones sencillas de los cambios más importantes de Swift 6, con ejemplos antes/después y el razonamiento detrás de cada novedad.

🔗 **[swift6-guide.vercel.app](https://swift6-guide.vercel.app)**

---

## Contenido

### Swift 6.0 · septiembre 2024
- **Actor · Strict Concurrency** — Los data races pasan de ser crashes en producción a errores de compilación.
- **Mutex · Synchronization** — Un lock oficial donde el dato vive dentro del lock.
- **sending · Fronteras de actores** — Transfiere un valor a otro actor garantizando que nadie más lo retiene.
- **Atomic\<T\> · Synchronization** — Operaciones atómicas nativas para contadores y flags. Más ligero que Mutex.
- **Typed throws** — Las funciones declaran exactamente qué tipo de error lanzan.
- **Ownership · ~Copyable** — Tipos que no se pueden duplicar.
- **BitwiseCopyable · Copia sin ARC** — Tipos que se copian bit a bit, sin ARC ni destructores.
- **count(where:) · Pack iteration · Int128** — Tres cosas que hacías con más código.

### Swift 6.1 · marzo 2025
- **nonisolated extension** — Una sola declaración para toda la extensión.
- **Task groups · Trailing commas** — El compilador infiere el tipo en task groups.

### Swift 6.2 · septiembre 2025
- **Approachable Concurrency · @concurrent** — Declara explícitamente dónde corre una función.
- **@Observable · Observations** — De ObservableObject + @Published a una sola macro.
- **InlineArray\<N, T\> · Stack array** — Array de tamaño fijo en el stack. Cero allocations, cero ARC.
- **Span\<T\> · Vistas de buffer** — Acceso seguro a buffers sin copiar ni tomar ownership.
- **@MainActor por defecto** — Todo el módulo en MainActor por defecto. Opt-out con @concurrent.

### Swift 6.3 · marzo 2026
- **@specialize · @inline** — Hints al compilador para código crítico.
- **@lifetime · Tiempo de vida** — Dependencias de tiempo de vida verificadas por el compilador.
- **~Copyable en genéricos** — Tipos non-copyable en código genérico sin restricciones.

---

Construido con HTML, CSS y JS. Sin frameworks.
