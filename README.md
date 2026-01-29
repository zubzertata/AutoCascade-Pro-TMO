# <img src="icon.png" width="32" height="32"> AutoCascade TMO

![v4.1](https://img.shields.io/badge/version-4.1-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Private-red?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Chrome%20|%20Edge-lightgrey?style=for-the-badge)

**AutoCascade TMO** es una suite de optimización avanzada para entusiastas del manga. Transforma la interfaz de lectura estándar en una experiencia premium, fluida y altamente personalizable, permitiendo que el contenido sea el único protagonista.

---

## 🚀 Características Principales

### 🔄 Motor de Visualización Inteligente
* **Modo Cascada Automático:** Detecta y redirige automáticamente al modo de lectura continua para evitar interrupciones.
* **Modo Libro (Spread View):** Visualización de doble página emulando la lectura de un tomo físico.
* **Auto-Scroll Pro:** Desplazamiento automático ajustable con control de velocidad en tiempo real.

### 🎨 Interfaz de Usuario (Shadow DOM)
* **Widget Flotante Dinámico:** Panel de control integrado mediante Shadow DOM para evitar conflictos de estilo con el sitio web original.
* **Ultra-Dark Mode:** Re-estilización completa de la paleta de colores para reducir la fatiga visual (Eye-Care).
* **Control de Escala:** Ajuste dinámico del ancho de imagen (0% - 100%) para adaptarse a cualquier monitor.

### ⚡ Rendimiento y Optimización
* **Navegación Predictiva:** Buscador de rutas inteligente para saltar entre capítulos de forma instantánea.
* **Limpieza de Nodos:** Motor basado en `MutationObserver` que elimina elementos redundantes que afectan el rendimiento del scroll.

---

## 🛠️ Instalación

Para garantizar la integridad del código y recibir actualizaciones automáticas, la extensión debe instalarse a través de la tienda oficial:

<a href="https://chromewebstore.google.com/detail/autocascade-pro-tmo/imbloenianlfbcapdapgnkgphlbphohn">
  <img src="https://developer.chrome.com/static/docs/webstore/brand-guidelines/image/v2-web-store-badge-92.png" alt="Disponible en Chrome Web Store">
</a>

*Si eres desarrollador y deseas reportar un bug, por favor utiliza la pestaña de [Issues](../../issues).*

---

## 📋 Arquitectura del Proyecto

El proyecto está modularizado para garantizar la máxima velocidad de ejecución:

| Módulo | Función |
| :--- | :--- |
| `Viewer.js` | Motor principal de renderizado y modos de lectura. |
| `Navigation.js` | Lógica de detección de rutas y capítulos. |
| `UI.js` | Interfaz de usuario inyectada y controles flotantes. |
| `Optimizer.js` | Gestión de memoria y limpieza de elementos del DOM. |

---

## 🛡️ Transparencia y Seguridad

Este repositorio se mantiene como un **repositorio de documentación, seguimiento de versiones y feedback**. El código fuente completo no se publica de forma abierta para:
1. Proteger la propiedad intelectual de los algoritmos de optimización.
2. Evitar que los portales de lectura detecten y bloqueen los métodos de mejora de interfaz.

---

<p align="center">
  Desarrollado con ❤️ para la comunidad de lectores.
</p>
