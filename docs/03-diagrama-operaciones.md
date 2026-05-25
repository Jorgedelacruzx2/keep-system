# 📊 Diagrama de Flujo - ETAPA OPERACIONES

## 1. Flota Propia

```
┌─────────────────────────────────────────────────────────────────┐
│               ETAPA OPERACIONES                                 │
│                   FLOTA PROPIA                                  │
└─────────────────────────────────────────────────────────────────┘

                              INICIO
                                │
                    ┌───────────▼───────────┐
                    │  Planificación de     │
                    │  Compra de Vehículos  │
                    └───────────┬───────────┘
                                │
                ┌───────────────┼───────────────┐
                │               │               │
                ▼               ▼               ▼
        ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
        │  Motos/      │ │  Vans/       │ │  Camiones    │
        │  Bicicletas  │ │  Pickup      │ │  /Furgones   │
        │  Eléctricas  │ │  Refrigerados│ │  Especiales  │
        └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
                │               │               │
                └───────────────┼───────────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Análisis de          │
                    │  Rentabilidad (ROI)   │
                    └───────────┬───────────┘
                                │
                        ┌───────┴───────┐
                        │               │
                    ✓ VIABLE      ✗ NO VIABLE
                        │               │
                        ▼               ▼
                ┌──────────────┐ ┌──────────────┐
                │  Adquisición │ │  Buscar      │
                │  de Vehículos│ │  Alternativas
                └──────┬───────┘ └──────┬───────┘
                        │               │
                        │    ┌──────────┘
                        │    │
                        ▼    ▼
                    ┌───────────────┐
                    │  Registro en  │
                    │  Sistema      │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Instalación  │
                    │  de Rastreador
                    │  GPS + Cámara │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Asignación a │
                    │  Operario     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Training del │
                    │  Personal     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   Puesta en   │
                    │   Operación   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Mantenimiento│
                    │  Preventivo   │
                    │  (Programas)  │
                    └───────┬───────┘
                            │
                    ┌───────┴───────┐
                    │               │
                ┌─ DIARIO ─┐ ┌─ MENSUAL ─┐
                │           │ │           │
                ▼           ▼ ▼           ▼
        ┌──────────────┐ ┌──────────────┐
        │  Revisión    │ │  Servicios   │
        │  de Operación│ │  Completos   │
        └──────┬───────┘ └──────┬───────┘
                │               │
                │    ┌──────────┘
                │    │
                ▼    ▼
            ┌───────────────┐
            │   Reportes de │
            │   Desempeño   │
            └───────────────┘
```

---

## 2. Flota Fidelizada (Asociados)

```
┌─────────────────────────────────────────────────────────────────┐
│              FLOTA FIDELIZADA - ASOCIADOS                       │
└─────────────────────────────────────────────────────────────────┘

                              INICIO
                                │
                    ┌───────────▼───────────┐
                    │  Identificación de    │
                    │  Potenciales Asociados│
                    └───────────┬───────────┘
                                │
                ┌───────────────┼───────────────┐
                │               │               │
                ▼               ▼               ▼
        ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
        │  Operarios   │ │  Negocios    │ │  Transportistas
        │  Independ.  │ │  Pequeños    │ │  Formales    │
        └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
                │               │               │
                └───────────────┼───────────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Evaluación de        │
                    │  Capacidades          │
                    └───────────┬───────────┘
                                │
                        ┌───────┴───────┐
                        │               │
                    ✓ CUMPLE      ✗ NO CUMPLE
                        │               │
                        ▼               ▼
                ┌──────────────┐ ┌──────────────┐
                │  Envío de    │ │  Retroalimen
                │  Propuesta   │ │  tación y    │
                │  Comercial   │ │  Archivo    │
                └──────┬───────┘ └──────┬───────┘
                        │               │
                        │    ┌──────────┘
                        │    │
                        ▼    ▼
                    ┌───────────────┐
                    │  Firma de     │
                    │  Contrato     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Certificación
                    │  de Capacidades
                    │  (Cursos)     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Instalación  │
                    │  de Tecnología
                    │  (App, GPS)   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Asignación   │
                    │  de Rutas     │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Monitoreo de │
                    │  Desempeño    │
                    │  y KPI's      │
                    └───────┬───────┘
                            │
                    ┌───────┴───────┐
                    │               │
                ✓ EXITOSO    ✗ PROBLEMAS
                    │               │
                    ▼               ▼
            ┌──────────────┐ ┌──────────────┐
            │  Renovación  │ │  Intervención
            │  de Contrato │ │  y Capacita- │
            │  Anual       │ │  ción Extra  │
            └──────────────┘ └──────────────┘
```

---

## 3. Flota Tercera / Base de Datos (Tipo Startups)

```
┌─────────────────────────────────────────────────────────────────┐
│    FLOTA TERCERA / BASE DE DATOS - STARTUPS LOGÍSTICAS         │
└─────────────────────────────────────────────────────────────────┘

                              INICIO
                                │
                    ┌───────────▼───────────┐
                    │  Creación de Base de  │
                    │  Datos de Flotistas   │
                    └───────────┬───────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Integración con      │
                    │  Plataforma           │
                    └───────────┬───────────┘
                                │
                ┌───────────────┼───────────────┐
                │               │               │
                ▼               ▼               ▼
        ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
        │  Validación  │ │  Documentos  │ │  Referencias │
        │  de Datos    │ │  Legales     │ │  Empresariales
        │  (Seguros)   │ │  (RUC, etc)  │ │  y Técnicas  │
        └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
                │               │               │
                └───────────────┼───────────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Validación de        │
                    │  Capacidades          │
                    │  Operativas           │
                    └───────────┬───────────┘
                                │
                        ┌───────┴───────┐
                        │               │
                    ✓ APROBADO   ✗ RECHAZADO
                        │               │
                        ▼               ▼
                ┌──────────────┐ ┌──────────────┐
                │  Integración │ │  Solicitar   │
                │  Operativa   │ │  Correcciones
                │  (API)       │ │  y Reenvío  │
                └──────┬───────┘ └──────┬───────┘
                        │               │
                        │    ┌──────────┘
                        │    │
                        ▼    ▼
                    ┌───────────────┐
                    │  Configuración│
                    │  de Tarifas y │
                    │  Comisiones   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Publicación  │
                    │  en Marketplace
                    │  Interno      │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Asignación   │
                    │  Automática   │
                    │  de Envíos    │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Monitoreo    │
                    │  Calidad de   │
                    │  Servicio     │
                    └───────┬───────┘
                            │
                    ┌───────┴───────┐
                    │               │
                ✓ EXCELENTE  ✗ PROBLEMAS
                    │               │
                    ▼               ▼
            ┌──────────────┐ ┌──────────────┐
            │ Renovación   │ │ Intervención │
            │ de Acuerdo   │ │ o Exclusión  │
            └──────────────┘ └──────────────┘
```

---

## 4. Seguros (Cobertura de Operaciones)

```
┌─────────────────────────────────────────────────────────────────┐
│                  SEGUROS - COBERTURA OPERATIVA                  │
└─────────────────────────────────────────────────────────────────┘

                              INICIO
                                │
                    ┌───────────▼───────────┐
                    │  Análisis de Riesgos  │
                    │  Operacionales        │
                    └───────────┬───────────┘
                                │
                ┌───────────────┼───────────────┐
                │               │               │
                ▼               ▼               ▼
        ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
        │   Pérdida de │ │   Daño en    │ │  Accidentes  │
        │   Paquetes   │ │   Tránsito   │ │  Vehículos   │
        │   (Robo)     │ │  (Golpes)    │ │  (Choque)    │
        └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
                │               │               │
                └───────────────┼───────────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Selección de         │
                    │  Proveedores de       │
                    │  Seguros              │
                    └───────────┬───────────┘
                                │
                ┌───────────────┼───────────────┐
                │               │               │
                ▼               ▼               ▼
        ┌──────────────┐ ┌──────────────┐ ┌──────────────┐
        │  Responsabilidad
        │  Civil         │ │  Cobertura   │ │  Seguros     │
        │  (Terceros)    │ │  Todo Riesgo │ │  Especiales  │
        └──────┬───────┘ └──────┬───────┘ └──────┬───────┘
                │               │               │
                └───────────────┼───────────────┘
                                │
                    ┌───────────▼───────────┐
                    │  Negociación de       │
                    │  Pólizas y Primas     │
                    └───────────┬───────────┘
                                │
                        ┌───────┴───────┐
                        │               │
                    ✓ ACUERDO    ✗ RENEGOCIAR
                        │               │
                        ▼               ▼
                ┌──────────────┐ ┌──────────────┐
                │ Contratación │ │ Búsqueda de  │
                │ de Pólizas   │ │ Mejores      │
                │              │ │ Alternativas │
                └──────┬───────┘ └──────┬───────┘
                        │               │
                        │    ┌──────────┘
                        │    │
                        ▼    ▼
                    ┌───────────────┐
                    │  Entrenamiento│
                    │  en Protocolos│
                    │  de Siniestros
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Activación   │
                    │  de Pólizas   │
                    │  en Sistema   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │  Gestión de   │
                    │  Reclamos y   │
                    │  Siniestros   │
                    └───────────────┘
```

---

## 🔑 Componentes Clave de Operaciones

| Componente | Descripción | Responsable |
|-----------|-----------|-----------|
| **Flota Propia** | Vehículos de propiedad | Operations Manager |
| **Flota Fidelizada** | Asociados contractuales | Partnership Manager |
| **Flota Tercera** | Marketplace de flotistas | Platform Manager |
| **Mantenimiento** | Servicio preventivo | Logistics Manager |
| **Seguros** | Cobertura de riesgos | Risk Manager |

---

## ✅ Criterios de Éxito - Operaciones

- ✓ Utilización de flota > 85%
- ✓ Mantenimiento preventivo al 100%
- ✓ Asociados fidelizados > 200
- ✓ Cobertura de seguros al 100%
- ✓ Downtime de flota < 5%

---

**Última actualización:** 2026-05-25
