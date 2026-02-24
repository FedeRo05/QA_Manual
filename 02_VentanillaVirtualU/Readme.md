#  QA Report: Ventanilla Virtual Universitaria

Este proyecto detalla las pruebas funcionales y de seguridad realizadas en el portal de Ventanilla Virtual. El objetivo fue validar la integridad del manejo de archivos y la estabilidad de las sesiones de usuario.

##  Casos de Prueba Ejecutados

| ID | Caso de Prueba | Resultado | Observaciones |
| :--- | :--- | :--- | :--- |
| TC-UNI-01 | Carga de archivos pesados | **PASSED** ✅ | El sistema limita correctamente el peso y arroja alerta clara. |
| TC-UNI-02 | Expiración de Sesión | **PASSED** ✅ | Al detectar inactividad, el sistema redirige al Login por seguridad. |
| TC-UNI-03 | Visualización en Móvil | **PASSED** ✅ | La interfaz es responsiva; los botones de trámites son accesibles. |

##  Conclusión Técnica
El portal presenta una alta robustez en el manejo de sesiones y filtros de seguridad en la carga de documentos. No se detectaron vulnerabilidades críticas durante la ejecución de las pruebas negativas.
