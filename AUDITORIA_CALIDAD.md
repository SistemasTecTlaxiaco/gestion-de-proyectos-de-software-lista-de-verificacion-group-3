# Auditoría de Calidad de Software

## 1. Datos del proyecto

**Proyecto:** Hub Mixteca  
**Organización beneficiaria:** Costuras de Tijaltepec  
**Problemática:** Falta de canales de comercialización y visibilidad de mercado.  
**Repositorio:** gestion-de-proyectos-de-software-lista-de-verificacion-group-3  
**Herramienta de auditoría:** GitHub  
**Estándares de referencia:** CMMI y MoProSoft  

---

## 2. Objetivo

Diseñar y aplicar una herramienta de auditoría de calidad en GitHub para el proyecto Hub Mixteca, con el propósito de comprobar de manera verificable el control de cambios, la trazabilidad de los requisitos, la verificación, la validación y la documentación de evidencias.

La auditoría adapta principios de CMMI y MoProSoft a las características del proyecto y utiliza las funcionalidades de GitHub, como Issues, commits, archivos Markdown e historial de cambios, para registrar y comprobar las actividades de calidad.

---

## 3. Alcance

La auditoría comprende la revisión de los elementos relacionados con la calidad del proyecto Hub Mixteca, principalmente:

- Historias de usuario.
- Criterios de aceptación.
- Plan de calidad.
- Control y trazabilidad de cambios.
- Issues de GitHub.
- Commits e historial de modificaciones.
- Evidencias de verificación.
- Evidencias de validación.
- Registro y corrección de problemas.
- Consideraciones del contexto de uso de Costuras de Tijaltepec.

La auditoría no pretende sustituir una auditoría formal de CMMI o MoProSoft. Su finalidad es adaptar principios de estos modelos a una herramienta práctica de control de calidad dentro de GitHub.

---

## 4. Contexto del proyecto

Hub Mixteca busca atender la problemática de falta de canales de comercialización y visibilidad de mercado para Costuras de Tijaltepec.

Debido a este contexto, la calidad del software no se limita a comprobar que una funcionalidad exista técnicamente. También es necesario verificar que las funcionalidades respondan a los requisitos definidos y que exista evidencia de su validación.

Por esta razón, la auditoría considera aspectos de trazabilidad, control de cambios, validación de requisitos, evidencia de pruebas y adaptación al contexto de uso.

---

## 5. Adaptación de CMMI y MoProSoft a GitHub

| Área de calidad | Adaptación al proyecto Hub Mixteca | Evidencia en GitHub |
|---|---|---|
| Gestión de requisitos | Control de historias de usuario y criterios de aceptación | Issues y documentación |
| Gestión de cambios | Registro de modificaciones realizadas al proyecto | Issues, commits e historial |
| Verificación | Comprobación de que una funcionalidad cumple los criterios establecidos | Evidencias de pruebas |
| Validación | Comprobación de que la funcionalidad responde a la necesidad planteada | Evidencia de validación |
| Aseguramiento de calidad | Revisión mediante lista de verificación | AUDITORIA_CALIDAD.md |
| Gestión de riesgos | Identificación y seguimiento de riesgos del proyecto | Issues o documentación |
| Mejora continua | Corrección de hallazgos y nueva revisión | Issues, commits y segunda auditoría |

---

# 6. Lista de verificación de auditoría

Cada criterio será evaluado mediante evidencia observable en GitHub.

### Estados

- ☑ **Cumple:** existe evidencia suficiente y verificable.
- ◐ **Parcial:** existe evidencia, pero requiere complemento o corrección.
- ☐ **No cumple:** no existe evidencia suficiente.
- N/A: no aplica al alcance de la auditoría.

| ID | Criterio de auditoría | Referencia | Evidencia requerida | Estado |
|---|---|---|---|---|
| AUD-01 | Las historias de usuario del proyecto tienen criterios de aceptación definidos. | CMMI REQM / MoProSoft | Historia de usuario y criterios de aceptación | ☐ |
| AUD-02 | Los cambios realizados en las historias de usuario quedan registrados. | CMMI REQM | Issue, commit o historial de cambios | ☐ |
| AUD-03 | Los cambios importantes tienen una justificación documentada. | CMMI REQM | Descripción de cambio o Issue | ☐ |
| AUD-04 | Existe trazabilidad entre el requisito y el cambio realizado. | CMMI REQM | Issue, commit y requisito relacionado | ☐ |
| AUD-05 | La funcionalidad correspondiente a un requisito cuenta con evidencia de verificación. | CMMI VER | Prueba, captura o evidencia técnica | ☐ |
| AUD-06 | Las funcionalidades son revisadas respecto a las necesidades de Costuras de Tijaltepec. | CMMI VAL | Evidencia de validación | ☐ |
| AUD-07 | Los problemas o incumplimientos detectados durante la revisión quedan registrados. | CMMI PPQA | Issue de hallazgo | ☐ |
| AUD-08 | Las acciones correctivas quedan documentadas y relacionadas con el problema detectado. | CMMI PPQA | Issue + commit + evidencia | ☐ |
| AUD-09 | Los riesgos que pueden afectar la calidad del proyecto están identificados. | CMMI RSKM | Registro o Issue de riesgo | ☐ |
| AUD-10 | La solución considera las condiciones de conectividad y contexto de uso de la región Mixteca. | Adaptación contextual | Evidencia de diseño, prueba o documentación | ☐ |
| AUD-11 | Se consideran aspectos de usabilidad y acceso desde dispositivos utilizados por los usuarios. | Calidad del producto | Evidencia de revisión o prueba | ☐ |
| AUD-12 | Los cambios relevantes cuentan con evidencia verificable y trazable hasta el requisito correspondiente. | CMMI REQM / VER | Issue + commit + evidencia | ☐ |

---

# 7. Control de cambios

Todo cambio relevante relacionado con los requisitos o funcionalidades del proyecto deberá poder rastrearse mediante GitHub.

La trazabilidad propuesta será:

**Requisito → Issue → Cambio → Commit → Evidencia → Verificación → Validación**

Para considerar un cambio como correctamente controlado deberá existir información suficiente para responder:

1. ¿Qué requisito fue afectado?
2. ¿Qué cambió?
3. ¿Por qué fue necesario el cambio?
4. ¿Dónde se registró?
5. ¿Qué evidencia demuestra la modificación?
6. ¿La modificación fue verificada?
7. ¿La modificación fue validada cuando correspondía?

---

# 8. Sistema de evaluación

La lista contiene 12 criterios.

Para establecer una progresión medible se utilizarán los siguientes niveles:

### 🥉 Insignia Bronce — Control de cambios

Se obtiene cuando la auditoría demuestra al menos:

- 8 de 12 criterios cumplidos.
- Evidencia de control básico de cambios.
- Existencia de trazabilidad en los cambios revisados.
- Registro de los principales hallazgos.

Representa el nivel de **control y trazabilidad**.

---

### 🥈 Insignia Plata — Calidad verificada

Se obtiene cuando la auditoría demuestra:

- 10 de 12 criterios cumplidos.
- Evidencia de control de cambios.
- Evidencia de verificación.
- Evidencia de validación.
- Registro de problemas y acciones correctivas.
- Identificación de riesgos relevantes.

Representa el nivel de **control + verificación + validación**.

---

### 🥇 Insignia Oro — Auditoría integral

Se obtiene cuando la auditoría demuestra:

- 12 de 12 criterios cumplidos.
- Trazabilidad completa de los cambios relevantes.
- Evidencia de verificación.
- Evidencia de validación.
- Registro y corrección de hallazgos.
- Riesgos identificados.
- Adaptación al contexto del proyecto.
- Una acción de mejora documentada y comprobable.

Representa el nivel de **control + verificación + validación + mejora continua**.

---

# 9. Regla para obtener la insignia

La insignia no será asignada previamente.

Primero se realizará la auditoría del repositorio y posteriormente se determinará el nivel alcanzado de acuerdo con la evidencia disponible.

| Resultado de auditoría | Insignia |
|---|---|
| 8–9 criterios cumplidos | 🥉 Bronce |
| 10–11 criterios cumplidos | 🥈 Plata |
| 12 criterios cumplidos + mejora documentada | 🥇 Oro |

La insignia registrada deberá corresponder al resultado real de la auditoría.

---

# 10. Registro de resultados

## Primera auditoría

| Elemento | Resultado |
|---|---|
| Criterios evaluados | 12 |
| Criterios cumplidos | Pendiente de auditoría |
| Criterios parciales | Pendiente de auditoría |
| Criterios no cumplidos | Pendiente de auditoría |
| Hallazgos encontrados | Pendiente de auditoría |
| Insignia inicial | Pendiente de auditoría |
| Fecha | Pendiente |
| Responsable | Equipo del proyecto |

---

# 11. Registro de hallazgos

Los criterios que no cumplan completamente serán registrados mediante Issues de GitHub.

Cada hallazgo deberá contener:

- ID del criterio afectado.
- Descripción del problema.
- Evidencia encontrada.
- Acción correctiva propuesta.
- Responsable.
- Commit relacionado cuando se realice la corrección.
- Estado de la corrección.

### Formato de hallazgo

**Criterio:** AUD-XX  
**Problema:** Pendiente de auditoría.  
**Evidencia:** Pendiente de auditoría.  
**Acción correctiva:** Pendiente.  
**Issue:** Pendiente.  
**Commit:** Pendiente.  
**Estado:** Pendiente.

---

# 12. Acciones correctivas

Los incumplimientos encontrados durante la primera auditoría deberán convertirse en acciones de mejora.

La acción correctiva deberá seguir el proceso:

**Hallazgo → Issue → Corrección → Commit → Evidencia → Nueva revisión**

Una corrección solamente se considerará cerrada cuando exista evidencia suficiente de que el problema fue atendido.

---

# 13. Segunda auditoría

Después de aplicar las acciones correctivas se realizará una segunda auditoría.

La segunda revisión permitirá comparar los resultados obtenidos inicialmente con el resultado posterior a las correcciones.

| Criterio | Primera auditoría | Segunda auditoría |
|---|---|---|
| AUD-01 | Pendiente | Pendiente |
| AUD-02 | Pendiente | Pendiente |
| AUD-03 | Pendiente | Pendiente |
| AUD-04 | Pendiente | Pendiente |
| AUD-05 | Pendiente | Pendiente |
| AUD-06 | Pendiente | Pendiente |
| AUD-07 | Pendiente | Pendiente |
| AUD-08 | Pendiente | Pendiente |
| AUD-09 | Pendiente | Pendiente |
| AUD-10 | Pendiente | Pendiente |
| AUD-11 | Pendiente | Pendiente |
| AUD-12 | Pendiente | Pendiente |

---

# 14. Resultado final

Después de completar la segunda auditoría se registrará el resultado real obtenido.

| Elemento | Resultado final |
|---|---|
| Criterios evaluados | 12 |
| Criterios cumplidos | Pendiente |
| Criterios parciales | Pendiente |
| Criterios no cumplidos | Pendiente |
| Acciones correctivas realizadas | Pendiente |
| Mejora documentada | Pendiente |
| Insignia final | Pendiente |
| Fecha | Pendiente |

---

# 15. Evidencias

Las evidencias de la auditoría podrán incluir:

- Issues de GitHub.
- Commits.
- Historial de cambios.
- Historias de usuario.
- Criterios de aceptación.
- Evidencias de pruebas.
- Evidencias de validación.
- Registro de problemas.
- Acciones correctivas.
- Documentación del proyecto.

Las evidencias deberán permitir comprobar objetivamente el estado de cada criterio.

---

# 16. Principio de honestidad académica

La insignia obtenida será determinada a partir de la evidencia real disponible en el repositorio.

No se considerará cumplido un criterio únicamente porque exista un documento que lo mencione. Será necesario contar con evidencia verificable cuando el criterio lo requiera.

De esta manera, la auditoría representa el estado real del proyecto y permite identificar oportunidades de mejora.

---

# 17. Conclusión

La lista de verificación convierte las prácticas de calidad de CMMI y MoProSoft en criterios que pueden ser revisados mediante las herramientas de GitHub.

El sistema de insignias establece una progresión basada en evidencias:

**🥉 Control de cambios → 🥈 Calidad verificada → 🥇 Auditoría integral y mejora continua**

La propuesta permite utilizar GitHub no solamente como repositorio, sino también como herramienta para documentar, verificar y dar seguimiento a la calidad del proyecto Hub Mixteca.
