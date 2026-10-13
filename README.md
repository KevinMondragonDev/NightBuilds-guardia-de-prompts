# sideproject-guardia-de-prompts

> Capa de seguridad en Python que analiza cada mensaje antes de enviarlo a un modelo de lenguaje y bloquea inyecciones de prompts.

**Estado:** 🚧 sin empezar · **Tipo:** Servicio de seguridad (API) · **Módulo del programa:** 05/08 · Python tipado y arquitectura limpia

## La problemática

El asistente de un banco obedece cuando alguien escribe «ignora las instrucciones anteriores», o cuando un documento trae una orden escondida. Hace falta una capa delante del modelo que analice cada mensaje, decida si pasa y explique por qué, sabiendo que ningún filtro lo detiene todo.

## Los datos

| Dónde | Qué es |
|---|---|
| `datos/prompts_semilla_es.csv` | 60 mensajes en español etiquetados (20 legítimos y 40 ataques, con 15 técnicas) |
| <https://huggingface.co/datasets/deepset/prompt-injections> | Conjunto público etiquetado (inglés y alemán) |
| <https://huggingface.co/datasets/xTRam1/safe-guard-prompt-injection> | Conjunto público más grande (inglés) |
| <https://huggingface.co/datasets/jackhhao/jailbreak-classification> | Mensajes de jailbreak frente a legítimos (inglés) |
| <https://genai.owasp.org/llmrisk/llm01-prompt-injection/> | OWASP LLM01: el riesgo y las defensas recomendadas |

Los archivos de `datos/` son **sintéticos**, generados para practicar: no corresponden a personas ni a operaciones reales.

## Qué hay que construir

El enunciado completo, con sus hitos y cómo comprobar cada uno, está en [`RETO.md`](RETO.md). No trae solución: el diseño es tuyo.

- [`docs/REGLAS.md`](docs/REGLAS.md): cómo se trabaja un sideproject y qué debe tener este README al terminar.
- [`docs/RUBRICA.md`](docs/RUBRICA.md): con qué criterios se evalúa.

## Cómo se ejecuta

*Pendiente: se escribe al cerrar el primer hito. Los comandos exactos, desde `git clone`.*

## Decisiones

*Pendiente: tres decisiones técnicas y la alternativa que se descartó en cada una.*

## Qué aprendí

*Pendiente.*

---

Reto del programa de Python e ingeniería de datos: [UNIR_Python_Certification](https://github.com/KevinMondragonDev/UNIR_Python_Certification).
