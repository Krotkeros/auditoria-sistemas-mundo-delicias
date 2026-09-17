# Taller: Elección del Marco de Auditoría de Sistemas

**Integrantes:**
Carlos Andrés Laverde Parra
Santiago Garcés Pérez

---

## 1. Organización y Contexto

* **Organización:** Cafetería "Mundo Delicias" (I.U. Pascual Bravo).
* **Contexto:** Establecimiento de 20 m² y 6 a 8 trabajadores que atiende a cientos de estudiantes y empleados en descansos universitarios. Su sistema combina caja registradora, turnos con fichos/pantalla, pagos por transferencias digitales y anotaciones manuales en un cuaderno contable.
* **Principales riesgos:** Colapso de filas en horas pico si fallan los pagos o turnos (servicio), estafas con comprobantes falsos de transferencias (financiero) y pérdida o daño del cuaderno de ventas al no tener copia de respaldo (integridad y disponibilidad).

---

## 2. Marcos Elegidos y Orden de Aplicación

1. **1º ITIL (Gestión de Servicios de TI):** Para asegurar que la atención sea rápida, continua y sin cuellos de botella durante los descansos.
2. **2º ISO/IEC 27001 (Seguridad de la Información):** Para proteger los registros contables físicos y validar la autenticidad de los pagos electrónicos.

> **¿Por qué no COBIT?** COBIT se enfoca en gobierno corporativo y comités directivos de grandes empresas; aplicarlo en un local pequeño generaría burocracia innecesaria.

---

## 3. Justificación de la Elección

* **¿Por qué ITIL primero?:** El valor principal de la cafetería es la velocidad de despacho. Si falla la red móvil para confirmar transferencias o se apaga la pantalla de turnos, la fila se detiene y los clientes se van. ITIL audita la continuidad operativa y la resolución rápida de incidentes.
* **¿Por qué ISO/IEC 27001 segundo?:** Protege la información crítica del negocio. El cuaderno de papel no tiene respaldo (si se moja o pierde, se borra la contabilidad) y los cobros por transferencia dependen de validar capturas de pantalla ajenas sin control formal.

---

## 4. Evidencia Solicitada por Marco elegido

### Para ITIL (Servicio y Disponibilidad)
1. **Plan de contingencia ante fallas técnicas:** Protocolo escrito visible en caja que indique cómo atender y cobrar manualmente cuando se cae el internet, falla la app bancaria o se apaga el visualizador de turnos.
2. **Control de tiempos de entrega en horas pico:** Registro simple de tiempos promedio de despacho y lista de reclamos por turnos embolatados o demoras excesivas entre las 10:00 a.m. y 12:30 p.m.

### Para ISO/IEC 27001 (Seguridad e Integridad)
1. **Verificación de transferencias bancarias:** Procedimiento que demuestre que el cajero valida el ingreso real del dinero en la cuenta del negocio y no solo mirando la pantalla del celular del cliente.
2. **Respaldo diario de ventas:** Fotografías diarias fechadas o digitalización del cuaderno contable al cierre de cada jornada para asegurar la información ante pérdidas o daños físicos.
3. **Estado del sistema de cámaras (Seguridad física):** Verificación de que las cámaras del local graban correctamente hacia la caja y que las grabaciones se guardan por al menos 30 días.