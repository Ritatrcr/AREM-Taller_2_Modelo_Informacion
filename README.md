# 📄 Informe Técnico del Taller

## 🔖 Taller 2 – Modelo de Información y Diagrama de Contexto

## 👥 Integrantes del equipo
- Rita Trindade da Cruz (ritatrcr)
- Brandon Merchan Sandoval (merchito12)
- Daniel Felipe Forero Sánchez (DanielForero14)

---

## 🧠 Descripción general del trabajo
El objetivo de este taller fue modelar las **entidades principales de información** y los
**flujos de datos** involucrados en un dominio de negocio, mediante la elaboración de un
**Modelo Entidad–Relación (ERD)** y un **Diagrama de Contexto de Negocio**.

El trabajo se desarrolló tomando como referencia el caso base **:contentReference[oaicite:0]{index=0}**, el cual fue trabajado inicialmente en clase para
comprender el dominio, identificar actores, sistemas y relaciones de información, y
posteriormente servir como base para la aplicación de los conceptos a un cliente real.

Esta aproximación permitió comprender la importancia de una correcta estructuración de
la información como punto de partida para el diseño de arquitecturas empresariales
alineadas con las necesidades del negocio y del usuario.

---

## 🔧 Proceso de desarrollo
El desarrollo del taller inició con el análisis del caso base de la Clínica Salud Viva,
identificando las entidades principales del dominio, tales como pacientes, citas, médicos,
especialidades y facturación, así como las relaciones existentes entre ellas.

Durante la sesión de clase se construyó un **primer borrador del modelo entidad–relación**
y un **borrador del diagrama de contexto**, los cuales permitieron visualizar de manera
general cómo fluye la información entre los actores y los sistemas involucrados.

Posteriormente, estos modelos fueron refinados fuera de clase, ajustando cardinalidades,
atributos y relaciones, hasta obtener un **modelo ER limpio y consistente**, junto con un
**diagrama de contexto de negocio** que representa de forma clara los límites del sistema,
los actores externos y los flujos de información.

Como herramienta principal se utilizó **draw.io**, lo que facilitó la iteración y mejora
continua de los diagramas.

---

## 🧩 Análisis del modelo propuesto

### 📊 Modelo de información (ERD)
El modelo entidad–relación propuesto se estructura a partir de:
- Entidades principales claramente identificadas.
- Claves primarias y foráneas para garantizar la integridad de los datos.
- Relaciones con cardinalidades definidas según las reglas del negocio.
- Atributos representativos del contexto clínico y administrativo.

Este modelo permite representar de manera coherente la información necesaria para soportar
los procesos de agendamiento, atención médica y facturación.

### 🌐 Diagrama de contexto de negocio
El diagrama de contexto identifica:
- Actores principales (paciente, médico, asistente).
- Sistemas internos (sistema de agendamiento, ERP clínico).
- Sistemas externos (aseguradoras, servicios de notificación).
- Flujos de información que conectan actores y sistemas.

Este diagrama permite comprender el alcance del sistema y sus interacciones con el entorno.

---

## 📈 Diagramas entregados
- Modelo Entidad–Relación (ERD) – Caso base
- Diagrama de Contexto de Negocio – Caso base

*(Los diagramas finales se encuentran en la carpeta `/entrega` del repositorio).*

---

## 🗂️ Organización del repositorio
El repositorio se encuentra organizado de la siguiente manera:
- **/clase**: contiene los borradores y notas generadas durante la sesión de clase.
- **/entrega**: contiene los diagramas finales, el informe y las referencias utilizadas.

Esta organización permite evidenciar tanto el proceso de construcción como la entrega
final del taller.

---

## 🔍 Investigación complementaria
### Tema investigado
Modelado de información mediante diagramas entidad–relación y su uso en la definición del
contexto de sistemas en arquitectura empresarial.

### Resumen
El modelado de información a través de ERD es una técnica fundamental para estructurar los
datos de un sistema de manera coherente y consistente. Complementariamente, el diagrama de
contexto permite delimitar el sistema y entender cómo interactúa con actores y sistemas
externos.

La combinación de ambos artefactos facilita la toma de decisiones de diseño y sirve como
base para etapas posteriores del desarrollo y la arquitectura de soluciones.

---

## 📚 Referencias
- [1] Universidad de La Sabana. Material de clase – Arquitectura Empresarial. s.f.  
- [2] Object Management Group (OMG). Entity-Relationship Model. s.f.  
- [3] Chakray Consulting. Modelado de datos y diagramas ER. s.f.

---
