# Sistema de Reconocimiento de Gestos mediante Redes Neuronales Convolucionales (CNN)

Proyecto desarrollado para el curso **Herramientas de Desarrollo** — Universidad Tecnológica del Perú (UTP).

## 🌐 Despliegue en Vivo
Accede a la aplicación en producción alojada en GitHub Pages:
👉 **[Abrir Aplicación en Vivo](https://juliopdev.github.io/UTP-deep_learning/)**

---

## 🎯 Descripción del Proyecto
Este sistema implementa un modelo de visión artificial capaz de clasificar gestos manuales en tiempo real a través de la cámara web. Utiliza técnicas de **Transfer Learning** sobre la arquitectura **MobileNet**, permitiendo una inferencia de alta precisión directamente en el cliente mediante **TensorFlow.js**.

### Clases Reconocidas:
1. **Mano abierta**: Reconocimiento de la palma extendida.
2. **Mano cerrada**: Reconocimiento del puño cerrado.
3. **Neutro**: Estado de reposo o ausencia de mano en el encuadre.

---

## 🔬 Especificaciones Técnicas
| Parámetro | Detalle |
| :--- | :--- |
| **Arquitectura Base** | MobileNet v2 (Transfer Learning) |
| **Framework de Inferencia** | TensorFlow.js (WebGL Backend) |
| **Herramienta de Entrenamiento** | Google Teachable Machine |
| **Resolución de Entrada** | 224 × 224 píxeles (RGB) |
| **Alojamiento y CI/CD** | GitHub Pages (Despliegue estático) |
| **Identificador del Modelo** | `li6odylsX` |

---

## 🚀 Instrucciones de Uso
1. Ingrese al enlace de la aplicación.
2. Presione el botón **"Iniciar Detección"**.
3. Autorice el acceso a la cámara en el navegador.
4. Realice los gestos frente a la cámara para observar la clasificación y el porcentaje de confianza en tiempo real.
