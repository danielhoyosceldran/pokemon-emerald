<h1 align="center">Pokémon Type Master — Emerald Edition</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-62B957?style=for-the-badge" alt="Version" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License: MIT" />
  <img src="https://img.shields.io/badge/Gen-III-yellow?style=for-the-badge" alt="Generation 3" />
  <img src="https://img.shields.io/badge/Contributors-27%2B-green.svg?style=for-the-badge" alt="Contributors" />
</p>

<p align="center">

<strong>Herramienta técnica avanzada para la consulta y análisis de tipos en Pokémon Esmeralda.</strong>

</p>

## **📋 Descripción del Proyecto**

Este proyecto es una herramienta diseñada específicamente para la **Generación 3 (Hoenn)**. Permite a los entrenadores optimizar sus estrategias mediante el cálculo preciso de eficacias defensivas y ofensivas, respetando fielmente las mecánicas de *Pokémon Edición Esmeralda*.

### **🚀 Contenido Principal**

* **Matriz Global de Tipos:** Visualización de relaciones de daño entre los 17 tipos de Hoenn.
* **Calculadora Defensiva:** Simulador para tipos puros y duales.
* **Guía de Categorías:** Referencia de la división física/especial (pre-Gen 4).
* **Sistema Visual:** Iconografía técnica para diferenciar roles de combate.

## **🛠️ Funcionalidades Detalladas**

### **🔍 Comparación Multi-Selección**

La matriz interactiva permite marcar hasta **dos atacantes y dos defensores** simultáneamente, aplicando una lógica **FIFO** (First-In, First-Out). Esto facilita:

* Comparar resistencias de dos Pokémon ante un mismo ataque.
* Analizar la cobertura ofensiva contra múltiples objetivos.

### **🎨 Diferenciación Visual de Roles**

| Rol | Representación Visual | Iconografía |
| :---- | :---- | :---- |
| **Atacante (Movimiento)** | Tarjeta Rectangular | ⚔️ Espada Sólida |
| **Defensor (Pokémon)** | Tarjeta Circular (Píldora) | 🛡️ Escudo Sólido |

## **🧠 Mecánicas de la Generación 3**

En esta generación, la categoría de daño (Físico o Especial) está determinada estrictamente por el **tipo del movimiento**:

| Categoría | Tipos Elementales | Icono |
| :---- | :---- | :---- |
| **Físico** | Normal, Lucha, Tierra, Volador, Roca, Bicho, Fantasma, Veneno, Acero | 🔷 |
| **Especial** | Fuego, Agua, Planta, Eléctrico, Psíquico, Hielo, Dragón, Siniestro | ⭕ |

### **📊 Interpretación de Resultados**

| Multiplicador | Significado Técnico | Efecto en Combate |
| :---- | :---- | :---- |
| **x4** | Debilidad Doble | El daño recibido se cuadruplica |
| **x2** | Súper Eficaz | El daño recibido se duplica |
| **x1** | Daño Neutral | Daño estándar (sin tarjeta) |
| **½** | Resistente | El daño se reduce al 50% |
| **¼** | Resistencia Doble | El daño se reduce al 25% |
| **0** | Inmunidad | El daño es nulo |

## **💻 Tecnologías Utilizadas**

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/SVG-FFB13B?style=for-the-badge&logo=svg&logoColor=white" alt="SVG" />
</p>

* **Estructura:** HTML5 semántico.
* **Estilos:** Tailwind CSS (Responsive Design).
* **Lógica:** JavaScript ES6+ para cálculos en tiempo real.
* **Tipografía:** Inter (Google Fonts) para máxima legibilidad.

## **⚙️ Instalación y Ejecución**

La aplicación es un documento **Standalone** (autónomo) que no requiere servidores ni instalaciones complejas:

1. **Descarga** el archivo pokemon_type_chart.html.
2. **Abre** el archivo en cualquier navegador moderno (Chrome, Firefox, Safari, Edge).
3. **Uso Offline:** Una vez descargado, no requiere conexión a internet.

## **☕ Soporte y Contribuciones**

Si este proyecto te ha sido útil, considera apoyar su desarrollo:

<a href="https://buymeacoffee.com/argenistherose">

<img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-Donate-yellow.svg?style=for-the-badge&logo=buy-me-a-coffee" alt="Buy Me a Coffee" />

</a>

<p align="center">

<sub>Basado en los datos técnicos oficiales de la Generación 3 de Pokémon.</sub>

</p>
