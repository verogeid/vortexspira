# ⚙️ PLATFORM.md: Ingeniería de la Experiencia y Arquitectura Detallada

***

<a id="indice"></a>
<div align="center">

[Zero Fricción](#friccion) • [TTS Local](#tts) • [Portabilidad](#portabilidad) • [Ecosistema UX](#ecosistema) • [Licencias](#licencias)

</div>

***

[**⬅️ Volver al Resumen Principal**](./README.md)

---

## 1. ✨ Ingeniería de la Experiencia (UX) y Accesibilidad Total

<a id="friccion"></a>
### 🧠 Zero Fricción y Guía Contextual (Detalles)

* **Sincronización Total (Highlight & Voz):** La plataforma ofrece una sincronización perfecta entre el resaltado visual de la frase y la voz del mentor.
* **Selección de Voces por Rol:** Configura y personaliza la voz y el **tono** para cada rol (Narrador, Lector de Código, Consejos), mejorando la diferenciación auditiva.
* **Dictado Amigable (Visual vs. Audio):** El núcleo del formato `.vsl` es la capacidad de **desacoplar el texto que se muestra del texto que se lee**. Esto permite que el "Lector de Código" narre el código de forma natural (ej: "creamos la constante equis") mientras el usuario ve el código literal (ej: `const x = 1;`), eliminando la principal fuente de fricción del audio-aprendizaje técnico.
* **Guía Visual Contextual (Modo Desktop - En Desarrollo):** Un modal de visualizaciones mostrará una **captura de pantalla sincronizada** con el *highlight* para guiar al alumno en las implicaciones del código en el navegador o en la localización de menús de herramientas.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

<a id="tts"></a>
### 🗣️ Voces Inteligentes y Adaptables (Arquitectura de Cero Lag)

VortexSpira® utiliza las voces Text-to-Speech (TTS) disponibles localmente, conmutando si pierdes la conexión.

* Esta arquitectura local se ha elegido deliberadamente sobre las voces *online premium* por razones de coste, rendimiento (evitando el "lag" inaceptable) y fragmentación.
* **Evolución Futura (El Motor TTS Local):** Se está estudiando la incorporación de un **motor TTS neuronal que se ejecute 100% offline dentro de la PWA (vía WebAssembly)**.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

<a id="portabilidad"></a>
### 🔗 Continuidad y Portabilidad (Detalles)

* **Diseño 100% Responsive.**
* **Aprendizaje Offline Híbrido:** Consume **todo el contenido del módulo sin conexión** a internet (tras la carga inicial).
* **Sincronización Automática (En Desarrollo).**
* **Control de Playback:** Haz clic en cualquier frase de la pantalla para saltar instantáneamente.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

<a id="ecosistema"></a>
## 2. 🌌 El Ecosistema: Diseño Anti-Fatiga del Universo VortexSpira

<a id="focoguiado"></a>
### 👁️ Foco Guiado y Reducción de Carga Cognitiva (Detalles)

El diseño simula una **habitación cilíndrica tridimensional**. El núcleo de la reducción de la fatiga se centra en la técnica innovadora:

* **Aplicación del *Bug de las Cataratas***: Se aplica una **máscara *blur* degradada** a las columnas o secciones en las que no está el foco, reduciendo drásticamente la información periférica.

<a id="controles"></a>
### 🖱️ Controles de Interacción (A11Y)

La interfaz se construyó con la accesibilidad como requisito no funcional primario.

* **Navegación Total sin Ratón:** La navegación es completamente funcional y eficiente usando únicamente el teclado.
* **Controles de Navegación Jerárquica:** Uso de `Tab` para cambiar de sección y `Cursores` (`↑`, `↓`, `←`, `→`) para navegar entre opciones.
* **Guía Visual:** El **efecto *ghost* en el botón** con foco proporciona un *highlight* de alta visibilidad.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

<a id="licencias"></a>
## 3. 🛠️ Flujo de Licencias, Certificación y Catálogo (Detalles)

* **Exámenes de Nivel Profesional:** Los exámenes son tipo test (formato ISTQB), donde cada pregunta puede tener múltiples respuestas correctas y debes marcarlas todas para acertar. Se requiere un 70% para aprobar.
* **Diseño Coherente (UI):** Modales Estables para prevenir "saltos" (`CLS`).
* **Catálogo Inteligente:** Muestra un **catálogo de productos adquiridos** y **módulos disponibles para la compra**.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

<a id="licencia"></a>
## Licencia y Derechos de Uso

La plataforma **VortexSpira®** es un software comercial propietario.

* **Copyright © 2025 Diego González Fernández.** Todos los derechos reservados.
* El uso de la plataforma VortexSpira® requiere la adquisición de una **licencia válida** a través de los canales de venta autorizados (Hotmart).
* La distribución, modificación o ingeniería inversa del software están estrictamente prohibidas sin acuerdo previo por escrito con el autor.
* La marca VortexSpira® está registrada o en proceso de registro.
* La creación intelectual de la plataforma está registrada en **Safe Creative** ([**🛡️ Registro de Derechos**](https://www.safecreative.org)).

El **contenido de los cursos** que se ejecutan en esta plataforma se licencia por separado bajo sus propios términos al adquirir cada producto.

<div align="right">

[Volver al índice ▲](#indice)

</div>

---

© 2025 Diego González Fernández
[LinkedIn](https://www.linkedin.com/in/diego-gonzalez-fernandez)

