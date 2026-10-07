<p align="center">
  <img src="https://raw.githubusercontent.com/anima-mind/anima/main/assets/brand/anima-logo.png" alt="Anima" width="120" />
</p>

<h1 align="center">Anima</h1>

<p align="center">
  <b>Un harness de agentes con forma de mente.</b><br/>
  <i>A mind-shaped agent harness.</i>
</p>

<p align="center">
  <code>una mente = LLM (dotación) + harness (desarrollo) + historia (experiencia)</code>
</p>

---

Anima es un asistente personal que no solo responde: **recuerda, duerme, desea y cambia con el tiempo**. Su arquitectura parte de cómo el lenguaje y la memoria forman una mente humana — la gramática generativa de **Chomsky**, el sujeto y el Otro de **Lacan**, y la neurociencia de la memoria de **Kandel** — y la traduce a componentes de software verificables.

### Cómo piensa

| Idea | En Anima |
|---|---|
| **El sueño consolida** (Kandel) | Cada noche, mientras el teléfono carga, un ciclo destila la conversación del día en memorias durables, reconsolida las viejas y reflexiona. |
| **La plasticidad decae** | La identidad se moldea libre al principio y se estabiliza con las noches: `p(n) = 0.05 + 0.95·e^(−n/30)`. Pasada la infancia, cambiar quién es exige tu aprobación. |
| **El deseo del Otro** (Lacan) | Tus metas — declaradas o inferidas — motivan propuestas proactivas acotadas: recordatorios y seguimientos que llegan en su voz. |
| **Un cuerpo para actuar** | Tools con permisos explícitos (calendario, recordatorios, notas, cámara) y, opcionalmente, unas gafas Meta Ray-Ban Display como segundo cuerpo. |

### Principios

- **Local primero.** La mente vive en tu teléfono: memoria, metas y skills en una base local. Puede funcionar **100 % en el dispositivo** con el modelo de Apple, o con Claude, OpenAI o Gemini usando tu propia key (guardada en tu Keychain, nunca en un servidor).
- **Honesta por diseño.** Nunca afirma haber hecho algo que una tool no confirmó.
- **Evaluable.** Cada subsistema del spec tiene evals falsables y el código corre contra el modelo real, no solo contra mocks.

### Repositorios

| Repo | Qué es |
|---|---|
| [**anima**](https://github.com/anima-mind/anima) | El blueprint: investigación, spec de la arquitectura (10 subsistemas) y planes de implementación. El contrato que todos los runtimes obedecen. |
| [**anima-ios**](https://github.com/anima-mind/anima-ios) | Runtime *edge* en Swift: la app iOS. |
| [**animad**](https://github.com/anima-mind/animad) | Runtime *server* en Go. |

### Estado

🧪 **En pruebas de campo** (TestFlight interno). El blueprint es público; la app llegará a la App Store cuando esté lista.

<p align="center"><sub>Un proyecto de <a href="https://github.com/joshuamoreno1">Joshua Moreno</a> · 2026</sub></p>
