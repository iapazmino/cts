---
layout: post
title: "Qué quiere decir que Cursor funciona"
date: 2026-07-26 19:30:00 -0500
categories: ia cursor ide programación scot
tags: actualizado-2026-10-11
---

Advertencia: artículo en construcción. 

Una de las preguntas más comunes entre la gente que programa es Cuál es tu IDE preferido? Un IDE, de sus siglas en inglés Entorno de Desarrollo Integrado, es un editor de texto para programadores; es un procesador de palabras con funcionalidades que facilitan la escritura de código como por ejemplo presentar con colores diferentes los nombres y los valores de las variables de un programa y también autocompletar el nombre de una función.

En este artículo voy a utilizar a [Cursor](https://cursor.com/es/product) como el medio para ilustrar el cómo se han ido modificando el desarrollo de software como práctica y las herramientas que emplea y así dilucidar qué habilidades han desarrollado sus practicantes, qué otras quedaron en el olvido y si todos los programadores se integran de igual forma a este proceso de cambio.

Cursor es un entorno de desarrollo que se hizo disponible al público en general al inicio del 2023 (Cursor, 2023) y se popularizó al inicio del 2025 (Bloomberg, 2025) por ser uno de los primeros en poner a los agentes de generación de código como protagonista en el espacio de trabajo.

Para entender qué preguntas debo hacer en busca de la herramienta de IA que más se utiliza entre los programadores en Ecuador en la actualidad quiero primero entender qué quiere decir que Cursor funciona desde mi punto de vista. El objetivo no es generalizar sino identificar mi sesgo y poder hacer las preguntas de la encuesta sin que guíen la respuesta.

(Aquí va un párrafo que introduzca la flexibilidad interpretativa de la teoría de la construcción social de la tecnología con referencia al libro de la bicicleta de pinch y bijker) la idea es mostrar que esta definición de funciona es mi definición de funciona y no necesariamente se traslada a otras personas y otros grupos; de hecho eso es lo valioso, aquí me voy a dar cuenta de qué condiciones me llevan a tomar esta decisión y buscar cómo afectó de otra forma a otra gente.

## Qué quiere decir que funciona?

Primero y más importante Cursor es un IDE y no una interfaz con un agente, es decir sigue siendo un ambiente en el que escribir código es la meta del objeto.
Luego porque tiene una interfaz conocida, es el VS Code con una ventana para el asistente.
Me evita salir del código, puedo referenciar archivos y carpetas en los prompts.
Puedo elegir los modelos que quiero, por ejemplo en el trabajo utilizo sólo los modelos que paga mi trabajo y en mi casa todos los que paga mi suscripción menos Grok.
Cuesta 20 dólares mensuales, que es algo que puedo pagar.

## Cómo es posible ese funcionamiento?

Construir un IDE desde cero es una tarea bastante grande, entonces empezaron desde un fork de la versión Open Source de VS Code (Github NixOS 2024).
Esto tampoco es barato. La inversión inicial fue de 8 millones de dólares (TechCrunch 2023) y menos de un año después tuvo otra inversión de 60 millones más (Tech Juice 2025).
Inicialmente los modelos disponibles eran solamente los de OpenAI y Anthropic. Luego se incorporó un modelo propio y posterior a la venta a SpaceX también Grok. (referencia de la lista de modelos y de la compra). El entrenamiento de estos modelos requiere de millones de litros de agua (referencia a los centro de datos de OpenAI y demandas por el agua)(referencia a los centros de datos de Amazon, donde corre Anthropic) para disipar el calor generado por millones chips que requieren billones de dólares (referencia a la plata que le entró a NVidia desde Openai y Microsoft) y una cantidad inmensurable de datos públicos y privados tomados sin autorización de todos lados (referencias datos de wikipedia y juicios por derechos de autor NY times). (dónde corren los modelos de Cursor, en qué infra???)( aws capaz?) 
Y cómo un servicio tan caro se sostiene con suscripciones de 20 dólares pues gracias a los precios especiales que recibe (referencia al precio especial que le da OpenAi) (referencia a las inversiones circulares entre Nvidia, Oracle, OpenAI y otros: burbuja)

<p class="last-updated">Última actualización: 11 de octubre de 2026</p>

## Referencias

- [Cursor. 2023. "Cursor — Build Software with AI Agents"](https://cursor.com/es/product)
- [Bloomberg. 2025. "Cursor, an AI Coding Assistant, Draws a Million Users Without Even Trying"](https://www.bloomberg.com/news/articles/2025-04-07/cursor-an-ai-coding-assistant-draws-a-million-users-without-even-trying)
- [Github NixOS 2024, "This is Code OSS fork with builtin AI code generator"](https://github.com/NixOS/nixpkgs/issues/309541)
- [TechCrunch 2023, "Anysphere raises $8M from OpenAI to build an AI-powered IDE"](https://techcrunch.com/2023/10/11/anysphere-raises-8m-from-openai-to-build-an-ai-powered-ide/)
- [Tech Juice 2025, "Karachi-Born Tech Prodigy Behind $10 Billion “Vibe Coding” AI"](https://www.techjuice.pk/karachi-born-tech-prodigy-behind-10-billion-vibe-coding-ai/)

