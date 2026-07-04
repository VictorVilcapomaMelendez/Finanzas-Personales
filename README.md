# 💼 Sistema Inteligente de Finanzas Personales

Una solución diseñada para automatizar el registro, análisis y seguimiento de las finanzas personales mediante una experiencia visual e intuitiva.

El proyecto combina automatización de datos, reglas de negocio y analítica para transformar movimientos financieros en información clara que facilite la toma de decisiones.

Además de mostrar lo que ha ocurrido, el sistema incorpora análisis descriptivo, predictivo y prescriptivo para ayudar a planificar mejor el presupuesto y alcanzar objetivos de ahorro.

---

# 🌐 Demo

🚀 **Explora la versión pública del dashboard aquí:**

👉 **https://victorvilcapomamelendez.github.io/Finanzas-Personales/**

> **Importante**
>
> La versión publicada utiliza exclusivamente datos ficticios generados para fines demostrativos.
>
> No contiene información personal, financiera ni conexiones a servicios privados.

---

# ✨ ¿Qué hace este proyecto?

Este proyecto fue desarrollado para reducir al mínimo el registro manual de movimientos financieros.

Siempre que es posible, la información se captura automáticamente y el sistema se encarga de procesarla para convertirla en indicadores, alertas y recomendaciones.

El objetivo es que el usuario dedique menos tiempo registrando información y más tiempo comprendiendo su situación financiera.

---

# 🔄 Flujo de funcionamiento

El sistema sigue un flujo automatizado de procesamiento de información.

### 📩 1. Captura automática de transacciones

Cada cinco minutos, Google Apps Script analiza automáticamente los correos electrónicos enviados por las entidades financieras configuradas.

Cuando detecta una nueva operación financiera, extrae la información relevante y la registra automáticamente en la base de datos.

Esto permite mantener el historial actualizado sin necesidad de registrar manualmente la mayoría de las transacciones.

---

### 📝 2. Registro manual de gastos

No todos los gastos generan una notificación por correo.

Para esos casos, el sistema incorpora un formulario desarrollado con Google Forms que permite registrar manualmente cualquier movimiento faltante.

De esta manera el historial financiero permanece completo independientemente del método de pago utilizado.

---

### ⚙️ 3. Procesamiento de la información

Toda la información se consolida en Google Sheets.

Posteriormente, Google Apps Script aplica diferentes reglas de negocio para:

- Clasificar transacciones.
- Calcular indicadores financieros.
- Generar alertas.
- Evaluar el presupuesto.
- Estimar tendencias.
- Preparar la información para su visualización.

---

### 📊 4. Visualización y análisis

Finalmente, el dashboard transforma toda esa información en una experiencia visual compuesta por:

- KPIs.
- Gráficos interactivos.
- Alertas de presupuesto.
- Comparativos históricos.
- Tendencias.
- Proyecciones financieras.
- Recomendaciones de ahorro.

Todo ello diseñado para facilitar la comprensión del estado financiero con una interfaz sencilla y amigable.

---

# 🎯 ¿Qué problema resuelve?

Registrar ingresos y gastos suele ser sencillo.

Lo realmente difícil es interpretar esa información para tomar mejores decisiones.

Este sistema responde preguntas como:

- 💰 ¿Cuánto ingresé este mes?
- 🛒 ¿En qué estoy gastando más?
- 📉 ¿Estoy respetando mi presupuesto?
- 📈 ¿Cómo evoluciona mi capacidad de ahorro?
- 🎯 ¿Qué puedo hacer para alcanzar mi meta financiera?

Más que mostrar datos, busca convertirlos en información útil para la toma de decisiones.

---

# 🚀 Funcionalidades principales

## 📊 Indicadores financieros

- Ingresos
- Gastos
- Balance
- Ahorro
- Gasto diario
- Ratio de ahorro

---

## 🚦 Seguimiento inteligente del presupuesto

- Estado mediante semáforo.
- Alertas automáticas.
- Seguimiento mensual.
- Recomendaciones según el comportamiento del gasto.

---

## 📈 Visualizaciones interactivas

- Evolución mensual.
- Distribución por categorías.
- Medios de pago.
- Tendencias.
- Comparativos históricos.

---

## 🔮 Analítica integrada

El dashboard combina tres niveles de análisis.

### 📌 Descriptivo

Explica qué ocurrió.

### 📌 Predictivo

Estima cómo podrían cerrar el mes y el año según la tendencia observada.

### 📌 Prescriptivo

Sugiere acciones para optimizar el presupuesto y alcanzar objetivos de ahorro.

---

## 🎨 Experiencia de usuario

- 🌙 Modo oscuro y modo claro.
- 📱 Diseño responsive.
- 📊 Gráficos interactivos.
- 🔎 Búsqueda de transacciones.
- 📂 Exportación de datos a CSV.
- ⚡ Navegación rápida e intuitiva.

---

# 🛠 Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Google Apps Script
- Google Sheets
- Google Forms
- ApexCharts
- GitHub Pages

---

# 🏗 Arquitectura

```text
             Correos de entidades financieras
                         │
                         ▼
      Google Apps Script (ejecución cada 5 minutos)
                         │
                         ▼
                  Google Sheets
                         ▲
                         │
        Google Forms (registro manual)
                         │
                         ▼
      Procesamiento y reglas de negocio
                         │
                         ▼
     Dashboard Inteligente de Finanzas
```

---

# 🌐 Versión pública del proyecto

Por motivos de privacidad, este repositorio contiene una versión adaptada específicamente para GitHub Pages.

Esta versión mantiene la experiencia visual y funcional del dashboard utilizando datos completamente ficticios.

No incluye:

- Credenciales.
- API Keys.
- Información personal.
- Datos financieros reales.
- Conexiones a servicios privados.

Su propósito es mostrar el funcionamiento del sistema preservando la privacidad del entorno de producción.

---

# 💡 Valor del proyecto

Este proyecto demuestra cómo combinar automatización, procesamiento de datos y visualización para construir una solución orientada a la toma de decisiones.

Más allá del dashboard, refleja un flujo completo que abarca la captura automática de información, su transformación mediante reglas de negocio y su presentación a través de indicadores y visualizaciones interactivas.

Representa una aplicación práctica de automatización de procesos, análisis de datos y desarrollo web utilizando tecnologías del ecosistema de Google.

---

# Gracias por visitar este proyecto 😊
