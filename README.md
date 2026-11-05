# Finanzas Ospino

Página para llevar el control de ingresos y gastos.

- Registra ingresos y gastos con categoría, fecha y medio de pago.
- Resumen del mes, saldo acumulado, gastos por categoría y resumen del año.
- Inicio de sesión con Google; los datos se guardan en Firebase (Firestore) y se sincronizan entre dispositivos.
- Solo el dueño de cada cuenta puede leer o escribir sus movimientos (reglas de Firestore).
- Copia de seguridad en .json y exportación a Excel (.csv).

## Publicar con GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)` → Save.
