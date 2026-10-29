# Pre-entrega-1-testing-QA-
# 🧪 Auditoría de Calidad y Pruebas Funcionales — Módulo de Registro

Este proyecto documenta la planificación, diseño y ejecución de pruebas de software (Caja Negra) sobre el módulo web de registro de postulantes. El objetivo principal fue evaluar el cumplimiento de las reglas de negocio, validar la efectividad de las restricciones en campos obligatorios y evaluar la seguridad/formato de contraseñas y archivos adjuntos.

---

## 📌 Alcance y Cobertura
* **Nivel de Prueba:** Sistema / Funcional.
* **Técnicas Aplicadas:** Análisis de Valores Límite (BVA), Partición de Equivalencia y Pruebas de Flujo de Error.
* **Resultados:** Se ejecutaron **9 casos de prueba**, logrando identificar fallas críticas en las reglas de validación de contraseñas.

---

## 🛠️ Herramientas Utilizadas
* **Excel / Google Sheets:** Diseño y ejecución de la matriz vertical de casos de prueba.
* **Google Docs / Word:** Elaboración del informe técnico final.
* **Navegador Web / DevTools:** Ejecución de pruebas y validación en entorno real.

---

## 🐛 Principales Hallazgos (Bugs Detectados)

| ID Bug | Caso de Prueba | Descripción de la Falla | Severidad |
| :--- | :--- | :--- | :---: |
| **BUG-01** | `TC-CP3-REG03` | **Incumplimiento de Límite Superior (BVA):** El sistema permitió el registro exitoso utilizando una contraseña de 17 caracteres, omitiendo el límite máximo de 16. | Media |
| **BUG-02** | `TC-CP4-REG04` | **Complejidad de Contraseña Omitida:** El formulario aceptó la contraseña puramente numérica `12345678`, violando la regla de exigir al menos una mayúscula. | Alta |

---

## 📂 Enlaces y Entregables

* 📊 **[Ver Matriz Completa de Casos de Prueba (Google Sheets)]((https://docs.google.com/spreadsheets/d/1ZpyU6ueBenpxedj90OI2XxYcYWVs48j3/edit?usp=sharing&ouid=116756509398927554311&rtpof=true&sd=true))**
* 📄 **[Ver Informe Técnico Final en PDF](./docs/Informe_QA_Franco_Nieva.pdf)**

---

## 👤 Autor
**Franco Nieva**  
QA Tester Trainee / Junior
