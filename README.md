# E-commerce Académico para Estudiantes (Educommerce)
**Proyecto de Grado - Universidad Nacional Abierta y a Distancia (UNAD)**  
**Escuela de Ciencias Básicas, Tecnología e Ingeniería (ECBTI)**  
**Programa de Ingeniería de Sistemas**

---

## 📌 Información General
* **Curso:** Proyecto de Grado (Código: 202016907)
* **Fase:** Fase 4 - Componente práctico - Práctica Simulada
* **Nivel de Maduración Tecnológica:** TRL 5 (Prototipo funcional validado en entorno simulado)
* **Tutor:** Cesar Felipe Henao Villa

---

## 👥 Integrantes del Proyecto
* **Luis David Pinzón Roa** - C.C. 1.023.002.133
* **Sebastián Hernández Buitrago** - C.C. 1.007.403.935
* **Maria Camila Reales Forero** - C.C. 1.000.149.835

---

## 🎨 Prototipo Funcional UI/UX (Figma)
El diseño interactivo de la interfaz de usuario y la validación de flujos de navegación (Registro/Login por roles, Catálogo con filtros, Reputación, Carrito y Pasarela Simulada) se encuentra disponible en el siguiente enlace:

👉 **[Abrir Prototipo Interactivo en Figma - Educommerce](https://www.figma.com/design/a76Cb9NsdeKE6F6ZXoKn44/Educommerce?node-id=0-1&t=SSuDEN3VJvIrGbhR-1)**

---

## 🎯 Descripción de la Solución
Plataforma de comercio electrónico orientada a la comunidad universitaria para la compra, venta e intercambio seguro de recursos académicos (guías, resúmenes, plantillas de código y apuntes). La solución aborda la falta de confiabilidad de los canales informales mediante:
1. **Autenticación e Identidad Digital (HU-01):** Control de accesos por roles (comprador, vendedor, administrador) garantizando el cumplimiento de la Ley 1581 de 2012 (Protección de Datos Personales en Colombia).
2. **Gestión y Catálogo de Recursos Académicos (HU-02, HU-03):** Catalogación taxonómica, motor de búsqueda con filtros por categoría/materia/precio y publicación estructurada de archivos.
3. **Sistema de Reputación y Auditoría (HU-05, HU-06):** Algoritmo de calificación (1 a 5 estrellas), comentarios verificados y panel administrativo de control para mitigar el riesgo de estafas.
4. **Pasarela de Pago Simulada (HU-04):** Modelo funcional para la gestión del carrito de compras, selección de medios de pago (PSE/Tarjeta) y generación de comprobantes.

---

## 🔄 Metodología Ágil (Scrum)
El desarrollo del prototipo se estructuró bajo el marco de trabajo **Scrum**, dividido en tres Sprints consecutivos de 2 semanas:
* **Sprint 1 (Arquitectura Base y Autenticación):** Configuración del repositorio, entorno web y módulo de registro/roles (`HU-01`).
* **Sprint 2 (Gestión de Recursos y Catálogo Interactivo):** Interfaz principal, formulario de publicación y motor de búsqueda con filtros (`HU-02`, `HU-03`).
* **Sprint 3 (Pasarela Conceptual, Reputación y Validación Integral):** Carrito de compras, pasarela de pago simulada, sistema de reseñas y panel de administración (`HU-04`, `HU-05`, `HU-06`).

📄 *Consulta el detalle completo de Historias de Usuario y Criterios de Aceptación en:* [`docs/Desarrollo de la Metodología Ágil (Scrum).docx`](docs/Desarrollo%20de%20la%20Metodolog%C3%ADa%20%C3%81gil%20(Scrum).docx)

---

## 🛠️ Arquitectura y Stack Tecnológico
* **Diseño UI/UX:** Figma (Prototipado interactivo de alta fidelidad)
* **Lenguaje Principal:** Python 3.x
* **Framework Backend / Lógica:** Flask / FastAPI
* **Base de Datos:** PostgreSQL / SQLite (Modelo relacional normalizado en 3FN)
* **Seguridad:** OWASP Top 10 (Validación de entradas, sanitización y hashing de contraseñas)
* **Control de Versiones:** Git & GitHub

---

## 📁 Estructura del Repositorio
```text
├── database/            # Scripts DDL/DML, modelos relacionales y migraciones de BD
├── src/                 # Código fuente del backend y lógica de negocio (TRL 5)
├── docs/                # Metodología Scrum, Product Backlog, diagramas UML y especificaciones
├── .gitignore           # Exclusiones de Git para entorno de Python
├── LICENSE              # Licencia MIT
└── README.md            # Documentación general del proyecto
