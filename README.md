# 📦 MTG Battle Box Generator

¡Bienvenido a la **Enciclopedia Suprema de la Battle Box**! Una aplicación web diseñada específicamente para crear, balancear y gestionar arsenales de mazos de *Magic: The Gathering* orientados al formato **Kitchen Table Magic** (partidas casuales de alto nivel entre amigos).

Si estás cansado de que en tu grupo de juego un amigo traiga un mazo de torneo que arrolla en turno 3 y otro traiga un mazo temático que no puede competir, esta herramienta es para ti.

## 🎯 Nuestro Cometido: El Equilibrio Perfecto

El objetivo de esta herramienta es generar conjuntos de mazos simultáneamente mediante Inteligencia Artificial, asegurando **La Regla del Equilibrio Perfecto**. 

La IA (ya sea OpenAI, Gemini o DeepSeek) está programada mediante ingeniería de prompts inyectada en esta web para diseñar tandas completas (por ejemplo: 1 Aggro, 1 Control, 1 Midrange, 1 Combo y 1 Ramp) con varias directrices maestras:

1. **Ecosistema interconectado:** Los mazos se diseñan conociendo a sus rivales. Si el mazo Aggro es muy fuerte, el de Control tendrá las respuestas exactas (removal) para sobrevivir, y el Combo tendrá la velocidad ajustada para no ser imparable.
2. **"Kitchen Table" de Alto Nivel:** Queremos usar *staples* (cartas poderosas e históricas de Modern/Legacy), sin gastar una fortuna (la idea es imprimirlos como proxys). ¡Poder alto pero sin asfixia de turno 2!
3. **Mínimo 4 turnos:** Se le prohíbe formalmente a la IA crear combinaciones que aniquilen de un plumazo antes del turno 4, asegurando partidas interactivas y divertidas.

---

## 🚀 Cómo Usar la Herramienta

Esta herramienta se ejecuta íntegramente en tu navegador sin necesidad de servidores. Simplemente descarga o clona este repositorio y abre el archivo `index.html`.

### 1. El Salón de los Arquetipos
En la pantalla principal verás puertas hacia los **Macro-Arquetipos** fundamentales de MTG:
*   ⚔️ **AGGRO:** Rápido y Letal.
*   🛡️ **CONTROL:** Paciencia y Dictadura.
*   ⚖️ **MIDRANGE:** Adaptabilidad Brutal.
*   🗡️ **TEMPO:** Esgrima Inteligente.
*   🧩 **COMBO:** Matemáticas Rotas.
*   🏔️ **RAMP:** Recursos Titánicos.

Entra en cada uno de ellos y descubre los "Sub-Arquetipos" icónicos de la historia del juego (ej: *Burn, Tron, Amulet Titan, Affinity...*).

### 2. Llenando tu Battle Box
Por cada sub-arquetipo que te interese, pulsa **"Configurar Mazo"**. 
*   Puedes elegir sus colores preferidos, si quieres que se base en una Raza/Tribu concreta (Goblins, Elfos, etc) o darle instrucciones extra (ej: "Asegúrate de meter 4x Relámpagos").
*   Guárdalo en la Battle Box.

### 3. La Bóveda de la IA (Modo Experimental)
Una vez tengas (por ejemplo) 4 o 5 mazos en tu Battle Box, usa el **Panel de Magia Experimental**:
1. Introduce tu [API Key](https://aistudio.google.com/app/apikey) de Gemini, OpenRouter o OpenAI.
2. Pulsa 🔄 para cargar los modelos y selecciona el que más te guste.
3. Haz click en **✨ Generar Ya**.

La herramienta agrupará todas tus configuraciones y le enviará un "Mega-Prompt Maestro" a la IA pidiéndole que cree listas perfectas de 60 cartas para cada uno a la vez.

### 4. Herramientas Extra
*   **Hover de Scryfall:** Pasa el ratón por encima de cualquier carta en las listas generadas (estarán rodeadas de colores morados mágicos) para ver una previsualización de la carta real usando la base de datos de *Scryfall*.
*   **Bóveda Histórica:** Guarda los resultados de tus generaciones bautizando los lotes con un título y una pequeña nota, para no perder nunca esas configuraciones de mazos que tanto os gustaron a ti y a tus amigos.
*   **Compartir Lotes:** Haz click en los botones sociales para enviar las listas completas por WhatsApp o Telegram y empezar a imprimirlas.
*   **Tribunal de Juicio (DeepSeek R1):** *(Secreto: Haz doble click rápido en el icono 📦 de la pantalla de Battle Box)*. Se abrirá una terminal que enviará tus configuraciones a modelos avanzados de razonamiento para localizar fallos en tu meta y proponerte cambios quirúrgicos de equilibrio.

---

*¡Que fluyan los proxys y que gane el mejor estratega!*
