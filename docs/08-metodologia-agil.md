# 🔄 Metodología Ágil - Keep System

## 📌 Marco de Trabajo: Agile (Scrum + Kanban)

El proyecto Keep System utiliza una metodología **Agile Híbrida** que combina:
- **Scrum:** Para desarrollo de funcionalidades (sprints de 2 semanas)
- **Kanban:** Para tareas operacionales y soporte

---

## 🎯 Principios Ágiles del Proyecto

### Valores Fundamentales
1. **Individuos e Interacciones** > Procesos y herramientas
2. **Software Funcional** > Documentación exhaustiva
3. **Colaboración con el Cliente** > Negociación de contratos
4. **Respuesta al Cambio** > Seguir un plan

### Compromisos del Equipo
- ✓ Transparencia total en el progreso
- ✓ Entrega de valor incremental cada 2 semanas
- ✓ Mejora continua (Retrospectivas)
- ✓ Comunicación diaria efectiva

---

## 📅 Estructura de Sprints

### **Sprint Duration: 2 Semanas**

```
┌─────────────────────────────────────┐
│          SPRINT DE 2 SEMANAS        │
├─────────────────────────────────────┤
│ Lunes      │ Sprint Kick-off (2h)   │
│ Martes-Vie │ Desarrollo Activo      │
│ Lunes      │ Sprint Review (1h)     │
│            │ Retrospectiva (1h)     │
└─────────────────────────────────────┘

TOTAL: 10 días laborales de desarrollo
```

### **Reuniones Diarias (Daily Standup)**

**Duración:** 15 minutos  
**Horario:** 9:00 AM  
**Participantes:** Todos los miembros del equipo

**Preguntas:**
1. ¿Qué hice ayer?
2. ¿Qué haré hoy?
3. ¿Hay obstáculos que me impidan avanzar?

---

## 🏗️ Roles Ágiles

### **Product Owner (PO)**
- **Responsabilidad:** Gestionar el Product Backlog
- **Actividades:**
  - Priorización de requerimientos
  - Definición de "Done" (Criterios de Aceptación)
  - Comunicación con Stakeholders
  - Validación de Sprints completados

### **Scrum Master**
- **Responsabilidad:** Facilitar el proceso Scrum
- **Actividades:**
  - Remover impedimentos
  - Facilitar ceremoniasan Ágiles
  - Coaching al equipo
  - Proteger al equipo de interrupciones

### **Equipo de Desarrollo**
- **Responsabilidad:** Entregar incremento de producto
- **Actividades:**
  - Auto-organizarse
  - Estimar tareas
  - Desarrollar funcionalidades
  - Testing y validación

---

## 📊 Gestión del Backlog

### **Product Backlog (Backlog de Producto)**

Prioridades:
1. **CRÍTICO** - Bloquea todo, debe hacerse ya
2. **ALTO** - Impacto significativo en Go-Live
3. **MEDIO** - Mejora el producto
4. **BAJO** - Nice to have, diferenciador

### **Sprint Backlog (Backlog del Sprint)**

```
Ejemplo de Sprint Backlog:

SPRINT 5: Desarrollo de APIs de Tarifas
├── Como cliente, necesito obtener tarifas automáticamente
│   └── Dev: 8 horas | Testing: 2 horas
├── Integración con BD de Tarifas
│   └── Dev: 5 horas | Testing: 1 hora
├── Documentación API de Tarifas
│   └── Doc: 3 horas
└── Testing Funcional Completo
    └── QA: 4 horas

Total Estimado: 23 horas (De 40 disponibles por Dev)
```

---

## 📝 Historias de Usuario (User Stories)

### **Formato Estándar**

```
COMO [tipo de usuario]
QUIERO [acción/funcionalidad]
PARA [beneficio/valor]

CRITERIOS DE ACEPTACIÓN:
- [Criterio 1]
- [Criterio 2]
- [Criterio 3]

NOTAS TÉCNICAS:
- API endpoint: /api/v1/...
- Database: tabla_xyz
- Estimación: X puntos de historia
```

### **Ejemplo: Historia de Crear Envío**

```
COMO cliente
QUIERO crear un nuevo envío en el sistema
PARA poder realizar el reparto

CRITERIOS DE ACEPTACIÓN:
- El cliente ingresa origen y destino
- El sistema calcula automáticamente tarifa
- Se asigna automáticamente SLA según zona
- Se genera número de seguimiento
- Se notifica al cliente por email
- Se envía evento de creación por WebHook

TAMAÑO: 13 puntos de historia
PRIORIDAD: CRÍTICO
```

---

## 🎲 Estimación con Puntos de Historia

### **Escala Fibonacci: 1, 2, 3, 5, 8, 13, 21, 34**

| Puntos | Complejidad | Ejemplos |
|--------|-----------|----------|
| **1** | Trivial | Cambio de texto, corrección menor |
| **2** | Muy Pequeño | Validación simple, campo nuevo |
| **3** | Pequeño | Integración simple, cálculo básico |
| **5** | Mediano | API endpoint, feature clara |
| **8** | Grande | Múltiples endpoints, lógica compleja |
| **13** | Muy Grande | Feature completa, integración externa |
| **21+** | Épica | Deben dividirse en historias menores |

### **Velocidad del Sprint**

Cada sprint el equipo puede completar aproximadamente **40-50 puntos de historia** (según el tamaño del equipo).

---

## 🔄 Ceremoniasás Ágiles

### **1. SPRINT PLANNING** (2 horas)
**Cuándo:** Inicio de cada Sprint (Lunes 10 AM)  
**Quién:** PO, Scrum Master, Equipo Desarrollo

**Agenda:**
- Revisión de Product Backlog prioritario
- Estimación de historias
- Selección de historias para el sprint
- Definir objetivo del sprint
- Desglosar historias en tareas

**Salida:** Sprint Backlog definido

---

### **2. DAILY STANDUP** (15 minutos)
**Cuándo:** Diariamente 9:00 AM  
**Quién:** Todo el equipo

**Agenda:**
1. ¿Qué completé ayer?
2. ¿Qué haré hoy?
3. ¿Hay impedimentos?

**Salida:** Identificar bloqueos, sincronizar equipo

---

### **3. SPRINT REVIEW** (1 hora)
**Cuándo:** Fin de Sprint (Viernes 4 PM)  
**Quién:** Equipo + PO + Stakeholders

**Agenda:**
- Demo de funcionalidades completadas
- Validación de criterios de aceptación
- Feedback del cliente
- Actualización del Backlog

**Salida:** Demostración de valor entregado

---

### **4. RETROSPECTIVA** (1 hora)
**Cuándo:** Fin de Sprint (Viernes 4 PM después de Review)  
**Quién:** Equipo + Scrum Master

**Agenda (What went well, What didn't, What to improve):**
1. ¿Qué salió bien?
2. ¿Qué no salió bien?
3. ¿Qué mejorar para el próximo sprint?

**Salida:** Acciones de mejora para próximo sprint

---

## 📊 Métricas Ágiles de Monitoreo

### **1. Velocity (Velocidad)**
Suma de puntos completados por sprint.

```
Sprint 1: 35 puntos
Sprint 2: 42 puntos
Sprint 3: 45 puntos
Sprint 4: 40 puntos

Velocidad Promedio: 40.5 puntos por sprint
```

### **2. Burndown Chart (Gráfico de Burndown)**

Muestra el trabajo restante vs. tiempo del sprint.

```
Puntos
  |
50|●
  |  ●
40|    ●
  |      ●
30|        ●
  |          ●
20|            ●
  |              ●
10|                ●
  |                  ●●
 0|___________________●
  0 1 2 3 4 5 6 7 8 9 10 Días
```

### **3. Cumplimiento de Sprints**

Meta: ≥ 90% de historias completadas por sprint

```
Sprint 1: 85% (Bajo, revisar)
Sprint 2: 92% (OK)
Sprint 3: 95% (Excelente)
Sprint 4: 90% (OK)
```

---

## 🚀 Proceso de Deployment Ágil

### **Continuous Integration/Continuous Deployment (CI/CD)**

```
1. Developer hace Commit en Git
   ↓
2. Jenkins ejecuta Build automático
   ↓
3. Tests unitarios + Integración corren automáticos
   ↓
4. SonarQube analiza calidad de código
   ↓
5. Si OK → Deploy a Staging automático
   ↓
6. Smoke tests en Staging
   ↓
7. Si OK → Ready for Production
   ↓
8. Deployment manual a Producción (Controlled Release)
```

---

## 📋 Matriz RACI

| Actividad | PO | Scrum Master | Dev Lead | Team | QA |
|-----------|-----|---------|----------|------|-----|
| Backlog Prioritization | **A** | C | C | I | I |
| Sprint Planning | **A** | F | R | R | C |
| Story Definition | **R** | I | C | C | I |
| Estimation | C | **F** | R | R | C |
| Development | I | I | **R** | R | C |
| Testing | I | I | R | **R** | **A** |
| Review | **A** | F | R | R | C |
| Retrospective | C | **F** | R | R | R |
| Deployment | C | **F** | **R** | C | R |

**A = Accountable** | **R = Responsible** | **F = Facilitator** | **C = Consulted** | **I = Informed**

---

## ✅ Definición de "Done" (DoD)

Una historia se considera COMPLETADA solo cuando:

```
TÉCNICO:
☐ Código escrito y revisado (Code Review)
☐ Tests unitarios > 80% coverage
☐ Tests de integración pasan
☐ SonarQube: A+ calidad
☐ Documentado en Swagger/API Docs
☐ Sin deuda técnica

FUNCIONAL:
☐ Criterios de aceptación validados
☐ PO aprueba la funcionalidad
☐ No hay bugs críticos/bloqueadores
☐ Performance acceptable (< 2s)

OPERACIONAL:
☐ Documentación actualizada
☐ Deployment automático funcionando
☐ Monitoreo/alertas configuradas
☐ Incluido en Release Notes
```

---

## 🎓 Herramientas Ágiles Recomendadas

| Herramienta | Uso | Costo |
|-----------|-----|-------|
| **Jira** | Gestión de Backlog y Sprints | $7/user/mes |
| **Confluence** | Documentación Colaborativa | $5.50/user/mes |
| **Git + GitHub** | Control de Versiones | Gratuito |
| **Jenkins** | CI/CD Automation | Gratuito |
| **Slack** | Comunicación del Equipo | $6.67/user/mes |
| **Miro** | Retrospectivas Virtuales | $16/mes |

---

## 📈 Plan de Mejora Continua

### **Retrospectivas Iterativas**

Cada Sprint se ejecuta retrospectiva para mejorar:
1. Procesos internos
2. Comunicación del equipo
3. Herramientas utilizadas
4. Estimación y Velocidad

### **Objetivos de Mejora por Fase**

**FASE 1-2:** Establecer ritmo, sincronizar equipo  
**FASE 3:** Optimizar velocidad, reducir defectos  
**FASE 4:** Estabilizar operaciones, documentar lecciones

---

## 🔐 Riesgos Ágiles y Mitigación

| Riesgo | Probabilidad | Impacto | Mitigación |
|--------|------------|--------|-----------|
| Scope Creep | Alta | Alto | PO riguroso, cambios formales |
| Sprint Interruptions | Media | Medio | Proteger equipo, buffer de 20% |
| Falta de Claridad | Media | Medio | Refinement sessions semanales |
| Dependencias Externas | Media | Alto | Comunicación proactiva |
| Team Burnout | Baja | Alto | Velocidad sostenible, days off |

---

**Última actualización:** 2026-05-25  
**Versión:** 1.0
