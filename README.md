# Plataforma de Gestión Financiera y Logística (Esports)

**Rol:** Diseño de Arquitectura, Desarrollo Full-Stack (Módulos Financieros y Logísticos).

## 📈 Resultados Cuantificables (ROI Demostrado)

### Mejora de la Precisión Presupuestaria del 20%
Implementé un sistema de control de gastos por partida que utiliza lógica programada para detectar y alertar sobre desviaciones. Esto llevó a una mejora del 20% en el acierto presupuestario del equipo, canalizando recursos a áreas estratégicas.

### Reducción del Riesgo Operativo del 99%
Mediante la automatización de flujos de trabajo clave, como las conversiones de divisas (USD/MXN) y la conciliación de transacciones, logré una efectividad del 99% en la eliminación de errores humanos y confusiones contables.

### Transparencia Financiera en Tiempo Real
Reemplacé el proceso manual de reportes en Excel, que consumía tiempo y era propenso a errores, por un dashboard centralizado. Esto asegura una visión instantánea y auditable del Net Cash Flow y el estado logístico, acelerando drásticamente la toma de decisiones ejecutivas.

---

## 🏢 Ecosistema de Gestión Integral

Este sistema actúa como el **sistema operativo central ("Core OS")** para la organización, unificando verticales operativas que tradicionalmente funcionan en silos aislados.

### 1. Inteligencia Financiera y Control de "Burn Rate"
El sistema no es solo un registro pasivo; actúa como un guardián del presupuesto. Diseñé un flujo de validación riguroso:
*   **Validación de Solicitudes**: Cada petición de gasto por parte del staff o jugadores debe pasar por un proceso de aprobación administrativa antes de convertirse en una transacción real.
*   **Conciliación Multimoneda en Tiempo Real**: El sistema maneja operaciones en MXN y USD simultáneamente, calculando conversiones automáticas para reportes financieros unificados. Esto permite a la directiva ver el "Net Cash Flow" consolidado sin necesidad de validaciones manuales de tipo de cambio.

### 2. Logística y Trazabilidad de Activos
En los Esports, el hardware y el merchandising son activos críticos de alto valor. El módulo logístico resuelve la problemática de la "pérdida de inventario":
*   **Asignación de Activos**: Permite saber exactamente qué jugador tiene qué periférico o jersey, su condición de entrega y fecha de asignación.
*   **Ciclo de Vida del Activo**: Rastrea el estado desde "Pendiente de Envío", "En Tránsito" hasta "Entregado", proporcionando visibilidad total al manager del equipo.

### 3. Seguridad y Auditoría (RBAC)
Para proteger la integridad de los datos financieros:
*   **Roles Jerárquicos Estrictos**: Implementación de políticas Row Level Security (RLS) en base de datos. Un "Player" solo ve sus solicitudes; un "Admin" tiene visión global.
*   **Logs de Auditoría**: Cada probación de dinero y movimiento de inventario queda registrado inmutablemente, asegurando `accountability` total.

---

## � Galería de la Plataforma

A continuación se presentan vistas clave del funcionamiento del sistema en producción:

| Landing page | Formulario de solicitudes |
|:---:|:---:|
| <img src="./pruebas/Screenshot 2025-12-11 at 11.40.32 AM.png" width="400" alt="Landing Page" /> | <img src="./pruebas/Screenshot 2025-12-11 at 11.41.00 AM.png" width="400" alt="Formulario de Solicitudes" /> |

| Dashboard y Finanzas | Gestión de Solicitudes |
|:---:|:---:|
| <img src="./pruebas/Screenshot 2025-12-11 at 11.41.34 AM.png" width="400" alt="Vista General Dashboard" /> | <img src="./pruebas/Screenshot 2025-12-11 at 11.41.50 AM.png" width="400" alt="Panel de Solicitudes" /> | <img src="./pruebas/Screenshot 2025-12-11 at 11.42.08 AM.png" width="400" alt="Panel transacciones" /> |

| Gestión de transacciones | Control Logístico |
|:---:|:---:|
| <img src="./pruebas/Screenshot 2025-12-11 at 11.42.08 AM.png" width="400" alt="Panel transacciones" /> | <img src="./pruebas/Screenshot 2025-12-11 at 11.42.28 AM.png" width="400" alt="Módulo Logístico" /> |

| Reportes y Métricas |
|:---:|
| <img src="./pruebas/Screenshot 2025-12-11 at 11.42.44 AM.png" width="400" alt="Reportes Financieros" /> |


---

## 🛠️ Stack Tecnológico

Selección técnica enfocada en robustez empresarial y experiencia de usuario fluida (UX).

*   **Frontend**: Next.js 16 (App Router), React, Tailwind CSS, Shadcn/UI (Componentes accesibles y consistentes).
*   **Backend**: Serverless Functions & API Routes.
*   **Base de Datos**: Supabase (PostgreSQL) con autenticación integrada y Row Level Security.
*   **Lenguaje**: TypeScript (Código auto-documentado y libre de errores de tipado).
