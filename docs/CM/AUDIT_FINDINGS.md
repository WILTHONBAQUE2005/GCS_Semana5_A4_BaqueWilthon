\# Auditoría de configuración - ISSUE-1



Fecha: 2026-08-15



\## Hallazgos



1\. Tag v1.0 sin formato completo de SemVer.

2\. Tag release-1.1 con una convención distinta.

3\. config/.env quedó bajo seguimiento de Git.

4\. El commit "update stuff" no describía el cambio.

5\. REQ-003 fue agregado sin Issue ni criterios de aceptación.

6\. El hotfix no estaba vinculado a una incidencia.

7\. CHANGELOG no representaba claramente las versiones.

8\. No existía un registro formal de estados de los EC.



\## Decisiones



\- v1.0.0 conserva la baseline inicial.

\- v1.0.1 registra la corrección de configuración y documentación.

\- v1.1.0 incorpora el registro de estados y la trazabilidad del proceso.

\- REQ-003 queda como propuesta fuera de las versiones liberadas.

