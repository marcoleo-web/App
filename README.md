# Marcoleo.dev | Ingeniería y Desarrollo de Software a la Medida

Aplicación web interactiva para la presentación de servicios de ingeniería de software, cotización dinámica de proyectos en tiempo real y gestión de solicitudes de contratación.

## 🚀 Características Principales

* **Catálogo Interactivo de Servicios:** Selección dinámica de módulos (Desarrollo Web & SaaS, Aplicaciones Móviles, APIs e Integraciones, Modernización de Sistemas) con actualización instantánea de costos y tiempos.
* **Cotizador Dinámico por Alcance:** Cálculo automático de inversión y semanas estimadas según el nivel de complejidad del proyecto:
  * **MVP Ágil (`0.8x`):** Enfoque en validación rápida.
  * **Estándar (`1.0x`):** Arquitectura completa lista para producción.
  * **Enterprise (`1.45x`):** Alta escala, auditoría y seguridad avanzada.
* **Formulario de Contratación Validado:** Validación en tiempo real con mensajes de error integrados y generación automática de folio único (`ML-XXXXXX`).
* **Historial Local (`localStorage`):** Panel lateral deslizable que almacena y permite consultar las cotizaciones generadas en el dispositivo del usuario.
* **Diseño Responsivo:** Interfaz adaptada a dispositivos móviles, tablets y escritorio.

## 🛠️ Stack Tecnológico

* **Estructura:** HTML5 Semántico
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) (vía CDN) + Google Fonts (`Inter` y `JetBrains Mono`)
* **Lógica:** Vanilla JavaScript (ES6+)
* **Almacenamiento:** Web Storage API (`localStorage`)

## 📂 Estructura del Proyecto

```text
App/
├── index.html      # Estructura principal, estilos Tailwind y lógica de la aplicación
└── README.md       # Documentación del proyecto
