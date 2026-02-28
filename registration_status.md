# 🦅 Sociedad VeriPago: Protocolo de Mando
**Socio Goyo (Mando) | Socio Antigravity (Técnico) | Socio Claude (Auditor)**

---

## 📋 Pendientes Próxima Sesión

| Ítem | Responsable | Estado | Observaciones |
| :--- | :--- | :--- | :--- |
| **Notificar Admin** | Antigravity | 🔴 Pendiente | Habilitar + monto_esperado. |
| **RESP_IR_A_PAGO** | Goyo | 🔴 Pendiente | Verificar Expression en sesion_id. |
| **Sincronización Precios** | Goyo | 🟡 Pendiente | $5 o $29 en correo OTP. |
| **Job Limpieza DB** | Goyo | 🟡 Pendiente | Borrar registros antiguos (>24h). |
| **Bug OTP (Activación)** | Goyo | ⏸️ Standby | En pausa por lógica de Instagram. |

---

## ✅ Cerrado (27 Feb 2026)
- **Frontend blindado:** `isVerified`, [handlePlanChange](cci:1://file:///d:/z-DOCKER/UnificarProyectos/frontendBotGrilo/web-botgrilo/src/app/veripago/registro/_hooks/useRegistration.ts:125:4-128:6), [handleResetToStep1](cci:1://file:///d:/z-DOCKER/UnificarProyectos/frontendBotGrilo/web-botgrilo/src/app/veripago/registro/_hooks/useRegistration.ts:130:4-134:6) operativos.
- **VALIDAR_ADMIN (n8n):** Versión blindada activa (Header + $env).
- **Infraestructura GitHub:** Repositorio público bitácora + repo privado sistema configurados.

---

## 🚫 Registro de Decisiones Rechazadas
1. **Validación por Body en `activar`:** RECHAZADA por insegura.
2. **Llaves Hardcodeadas en n8n:** RECHAZADAS por insegura.

---
*Bitácora oficial sincronizada para auditoría.*
