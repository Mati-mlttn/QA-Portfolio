# Test Summary

## Resumen

Se realizó una ejecución de pruebas funcionales, de integración, carga y stress sobre Rescuetrack, sistema de gestión de vehículos de emergencia, cubriendo tanto la aplicación web como la aplicación móvil.

## Información de la ejecución

- Proyecto: académico, desarrollado en equipo
- Equipo: Benjamín Mendoza (Scrum Master) · Beatriz Orellana (Tester QA) · Matius Alcaino (Tester QA)
- Plataformas evaluadas: Web y Móvil
- Módulos ejecutados por Matius Alcaino: Registro de usuarios, Vehículos y Reportes de costos (Web) · Login, mantenciones, notificaciones y costos (Móvil)

## Alcance

- **Web:** Login, Registro y gestión de usuarios, Vehículos, Reportes de costos y mantención
- **Móvil:** Login, Vehículos y mantenciones, Notificaciones, Costos

## Resultados

| Métrica               | Web   | Móvil |
| --------------------- | ----- | ----- |
| Test cases ejecutados | 30    | 23    |
| ✅ Passed             | 28    | 12    |
| ❌ Failed             | 0     | 4     |
| ⏳ No ejecutados      | 0     | 7     |
| 🚫 Obsoletos          | 2     | 0     |
| % de avance           | 93,3% | 69,6% |

## Defectos encontrados (Móvil)

- Búsqueda de vehículos por patente incorrecta no muestra el mensaje esperado — Severidad: Medio
- Validación de datos incompletos al registrar mantenciones no muestra el mensaje esperado — Severidad: Leve
- Actualización de datos de costos no se refleja correctamente en pantalla — Severidad: Leve
- Exportación de costos sin datos disponibles no muestra el mensaje de error esperado — Severidad: Leve

## Conclusión

La versión web mostró un comportamiento estable, con 93,3% de los casos aprobados y solo 2 casos obsoletos por un cambio de funcionalidad (el buscador fue reemplazado por un filtro dinámico y trasladado a la versión móvil). La versión móvil se encuentra en una etapa más temprana de validación (69,6% de avance), con 4 fallas identificadas —principalmente en mensajes de error y validaciones— y 7 casos aún pendientes de ejecución, en su mayoría pruebas de carga y stress. La sincronización de datos entre la app móvil y la web se validó correctamente.
