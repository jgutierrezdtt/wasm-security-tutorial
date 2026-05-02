# 🕸️ Tutorial: WebAssembly Security

Seguridad en WebAssembly: análisis de módulos WASM, sandboxing, WASI capabilities, vulnerabilidades en código compilado y supply chain de WASM.

## ¿Qué aprenderás?

| Paso | Tema | Herramienta | Nivel |
|------|------|-------------|-------|
| 1 | Compilar módulo WASM básico | `—` | 🟢 Base |
| 2 | Análisis con wabt | `—` | 🟢 Base |
| 3 | Definir política de ejecución | `—` | 🟡 Medio |
| 4 | Implementar sandbox con Wasmtime | `—` | 🟡 Medio |
| 5 | Audit en CI | `wasm-pack test` | 🟡 Medio |
| 6 | WASI sandboxing | `—` | 🟠 Avanzado |
| 7 | Fuzzing de módulo WASM | `—` | 🟠 Avanzado |
| 8 | Content-Security-Policy para WASM | `script-src 'wasm-unsafe-eval'` | 🟠 Avanzado |
| 9 | Threat model de WASM | `—` | 🔴 Experto |
| 10 | Reporte final WASM | `—` | 🔴 Experto |

## ¿Cómo funciona?

```
Tú completas una tarea → GitHub Actions lo detecta → README se actualiza → siguiente paso
```

Cada vez que hagas commit del artefacto indicado en el README, GitHub Actions valida tu trabajo y desbloquea el siguiente paso automáticamente.

## Empezar

1. Haz click en **"Use this template"** → **"Create a new repository"** para crear tu copia personal
2. En tu nuevo repositorio, ve a la pestaña **Actions**
3. Si ves el aviso *"Workflows aren't being run on this forked repository"*, haz click en **"I understand my workflows, enable them"**
4. En el panel izquierdo haz click en **"Paso 0: Iniciar Tutorial"**
5. Haz click en **"Run workflow"** → **"Run workflow"**

El README se actualizará con el Paso 1 en unos segundos.

---

> **Nota**: Usa **"Use this template"** (no fork directo). Si hiciste fork, activa Actions desde **Settings → Actions → Allow all actions** antes de empezar.
