# 💼 Dashboard Financiero Inteligente (Google Apps Script + Web Dashboard)

Un tablero financiero pensado para personas reales: claro, visual y accionable.

Este proyecto nacio para ayudar a controlar ingresos, egresos y presupuesto mensual en una sola vista, con analitica descriptiva (que paso) y prescriptiva/predictiva (que deberias hacer).

---

## ✨ Que es este proyecto

## 🌐 Demo publica

Puedes ver la version publicada del tablero en:

https://victorvilcapomamelendez.github.io/Finanzas-Personales/

---

Este repositorio muestra **dos capas** del mismo producto:

1. **Producto completo (Apps Script)**
   - Backend en Google Apps Script conectado a Google Sheets.
   - Motor de calculo de KPIs, tendencias, alertas y proyecciones.
   - Dashboard web para uso diario.

2. **Version publicable en GitHub (skeleton/demo)**
   - Version estatica en `portfolio-demo/index.html`.
   - Datos ficticios hardcodeados (sin datos privados).
   - Sirve como **framework base** para que otra persona cree su propio dashboard parecido.

En resumen: en GitHub se publica el "esqueleto" profesional, no la operacion privada de produccion.

---

## 🎯 Problema que resuelve

La mayoria de personas ve sus finanzas en tablas sueltas, sin contexto ni prioridad.

Este dashboard convierte eso en decisiones claras:
- cuanto ingreso,
- cuanto gasto,
- en que se me va el dinero,
- si voy bien o mal contra mi presupuesto,
- y que debo hacer para llegar a mi meta.

---

## 🚀 Lo mas potente del proyecto

### 1) Control integral de ingresos vs egresos
- KPIs principales (ingresos, egresos, balance, gasto diario, ratio de ahorro).
- Analisis por categoria, medio de pago y comportamiento mensual.

### 2) Alertas de presupuesto en tiempo real
- Estado por semaforo (verde, amarillo, rojo).
- Mensajes accionables como "puedes gastar X" o "exceso de Y".
- Historial de presupuesto por mes para leer disciplina financiera.
- Semaforizacion automatica por nivel de riesgo para priorizar acciones rapidas.

### 3) Actualizacion automatica cada 5 minutos
- El tablero refresca para mantener datos recientes sin recargar manualmente.
- Ideal para seguimiento continuo.

### 4) Reportes en multiples horizontes
- Lectura semanal para control de habitos de gasto.
- Lectura mensual para cierre de presupuesto y balance.
- Lectura anual para evaluar tendencia financiera y avance de metas.

### 5) Vista descriptiva + vista predictiva/prescriptiva
- **Descriptiva**: explica que paso.
- **Predictiva**: estima cierre de mes/anio segun tendencia.
- **Prescriptiva**: sugiere cuanto ahorrar y cuanto gastar para llegar a la meta.

### 6) Experiencia de uso orientada a negocio
- Filtros rapidos (mes/anio, historico, mes actual).
- Tabla detallada con busqueda y exportacion CSV.
- Soporte visual para decisiones (graficos, badges, etiquetas, estados).

### 7) Experiencia visual moderna
- Modo oscuro/claro para adaptarse al contexto de uso.
- Interacciones visuales orientadas a lectura rapida de datos.
- Enfoque en usabilidad para personas no tecnicas.

---

## 🙌 Que ofrece al usuario final

- Menos ansiedad financiera.
- Mas claridad para decidir en que recortar.
- Seguimiento de metas de ahorro de forma concreta.
- Una herramienta simple para gestionar su economia personal o familiar.

---

## 🧱 Arquitectura (alto nivel)

- **Frontend**: HTML + JavaScript + estilos CSS embebidos en el propio HTML (ApexCharts para visualizacion).
- **Backend productivo**: Google Apps Script.
- **Fuente de datos productiva**: Google Sheets.
- **Version GitHub**: archivo estatico con mock data local.

---

## 🧩 Que compone este proyecto

- Logica de negocio en JavaScript para reglas financieras, KPIs, alertas y proyecciones.
- Interfaz web en HTML con visualizaciones y experiencia interactiva.
- Integracion con Google Apps Script para escenarios productivos.
- Version demo estatica para portfolio/GitHub Pages y reutilizacion como framework base.

---

## 🧪 Como usar la demo estatica

1. Abre `portfolio-demo/index.html` localmente, o
2. Publica la carpeta `portfolio-demo/` en GitHub Pages.

La demo ya incluye:
- filtros,
- KPIs,
- semaforizacion de estado financiero,
- alertas de presupuesto,
- graficos,
- tabla de transacciones,
- modo oscuro/claro,
- exportacion CSV de la data visible,
- proyeccion de ahorro.

---

## ⚙️ Si quieres llevarlo a produccion real

Flujo recomendado:

1. Conectar Google Sheets con tu estructura de datos.
2. Activar backend Apps Script con tu logica de negocio.
3. Ajustar categorias, medios de pago, moneda y reglas de negocio.
4. Publicar como Web App en Apps Script.
5. Mantener la version GitHub como showcase/plantilla publica.

---

## 📈 Perfil de valor del proyecto

Este no es solo un dashboard bonito.
Es un sistema de apoyo a decisiones financieras personales:

- **Descriptivo** (explica el pasado),
- **Predictivo** (anticipa escenarios),
- **Prescriptivo** (recomienda acciones concretas).
