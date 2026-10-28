# E-commerce Académico para Estudiantes
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

## 🎯 Descripción de la Solución
Plataforma de comercio electrónico orientada a la comunidad universitaria para la compra, venta e intercambio seguro de recursos académicos (guías, resúmenes, plantillas de código y apuntes). La solución aborda la falta de confiabilidad de los canales informales mediante:
1. **Autenticación e Identidad Digital:** Control de accesos por roles (comprador, vendedor, administrador) garantizando el cumplimiento de la Ley 1581 de 2012 (Protección de Datos Personales en Colombia).
2. **Gestión de Recursos Académicos:** Catalogación taxonómica, motor de búsqueda con filtros y almacenamiento estructurado de archivos.
3. **Sistema de Reputación:** Algoritmo de calificación por estrellas y comentarios retroactivos para mitigar el riesgo de estafas.
4. **Pasarela de Pago Simulada:** Modelo funcional para la gestión del carrito de compras y trazabilidad de transacciones.

---

## 🛠️ Arquitectura y Stack Tecnológico
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
├── interfaces/          # Prototipos interactivos y componentes del frontend simulado
├── docs/                # Diagramas UML (Casos de uso, Clases, ER) y especificaciones
├── .gitignore           # Exclusiones de Git para entorno de Python
├── LICENSE              # Licencia MIT
└── README.md            # Documentación general del proyecto
