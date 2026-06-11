# 📊 Ecosistema Digital de Agendamiento, CRM y Modelo de Datos
### Proyecto Expo Oficio 2026 | Fundación Soy Más

**Desarrollado por el equipo de Análisis de Datos:**
* 👩‍💻 **Rocío Aguayo**
* 👩‍💻 **Daniela Pinilla**

---

## 🌐 1. Centro de Operaciones (Página Web Principal)
Nuestra solución tecnológica centralizada inicia en una plataforma web construida en **Google Sites**. Este sitio funciona como la interfaz pública y el centro de control que conecta a los usuarios finales con nuestras herramientas automatizadas de gestión.

* 🔗 **[¡Haz clic aquí para visitar nuestra Página Web en Vivo!](https://sites.google.com/soymas.cl/pelu/inicio)**

---

## 📱 2. Aplicaciones Web Operacionales (Google Apps Script)
Para resolver las necesidades de gestión y digitalización de procesos, desarrollamos dos aplicaciones web utilizando código en **Apps Script** (HTML/CSS para el diseño de interfaces y JavaScript para la lógica interna):

### 📆 App de Agendamiento
* **Propósito:** Automatizar por completo el proceso de reserva y control de citas.
* **Funcionalidad:** Permite optimizar la disponibilidad del personal y agilizar la atención de manera digital.
* 🔗 **[Acceder a la App de Agendamiento en Vivo](https://script.google.com/macros/s/AKfycbwRrnTN0knAiDCX7KVs0I0J2RKfVxmWWo47MMO8_airhwDC6AqTb88jDrg7Jtuf0vcB/exec)**

### 👥 App de CRM (Customer Relationship Management)
* **Propósito:** Centralizar la gestión y el seguimiento de las interacciones con los usuarios/clientes.
* **Funcionalidad:** Permite llevar un registro detallado de cada persona y sus necesidades.
* 🔗 **[Acceder a la App de CRM en Vivo](https://script.google.com/macros/s/AKfycbxPEvttBpiuw90SYxBCVcUs9Awl-j2kDcgvF-sSe6cMemdcI06qmVmmOhwmr0Q4dwBhMA/exec)**

---

## 🗄️ 3. Arquitectura y Modelado de Datos
Como analistas de datos, nuestro enfoque principal estuvo en estructurar un repositorio de información limpio, relacional y consistente utilizando **Google Sheets** como nuestros almacenes de datos (Data Warehouses):

* 🔗 **[Revisar Base de Datos: Módulo Agendamiento (Google Sheets)](https://docs.google.com/spreadsheets/d/1CjwIKiJ7V6Sueck2VAyLQghUkNZ7CbqQpgmnZmY28K8/edit?usp=sharing)**
* 🔗 **[Revisar Base de Datos: Módulo CRM (Google Sheets)](https://docs.google.com/spreadsheets/d/1zKYT3M4hASJtUS1yNs6bDBpdt1Y5knRJvt3JBRN4fDs/edit?usp=sharing)**

### 📥 Módulo de Agendamiento (Estructura de Reservas):
* `servicios`: Catálogo con la oferta disponible.
* `reservas` / `citas`: Transacciones en tiempo real de los cupos solicitados.
* `profesionales`: Registro del personal encargado de las atenciones.
* `dias laborales` y `horarios`: Reglas de negocio que controlan la disponibilidad del sistema.

### 💼 Módulo de CRM (Estructura de Clientes):
* `clientes`: Datos maestros e identificación de los usuarios.
* `catalogo_servicios`: Control y estandarización de las prestaciones ofrecidas.
* `historial_atencion`: Bitácora histórica indispensable para el seguimiento y retención del cliente.

---

## 🚀 4. Próximos Pasos: Fase Analítica (Business Intelligence)
Con la arquitectura de datos completamente integrada y capturando información limpia en tiempo real, el ecosistema está preparado para la fase de **Inteligencia de Negocios**. Los próximos pasos estratégicos del proyecto son:
1. Conectar las bases de datos a herramientas de visualización (como Looker Studio o Power BI).
2. Analizar KPIs críticos como: *Servicios más solicitados, Horarios de mayor demanda y Frecuencia de retorno de clientes en el CRM* para la toma de decisiones estratégicas.

---

## 👥 5. Roles y Trabajo en Equipo
El desarrollo exitoso de este ecosistema integral se logró gracias a la coordinación equitativa en dupla:
* Ambos integrantes colaboraron activamente en el diseño lógico de las bases de datos en Sheets, la programación de flujos de trabajo en Apps Script y el diseño de la interfaz en Google Sites para garantizar un sistema unificado y funcional.
