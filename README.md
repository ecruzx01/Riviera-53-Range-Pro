# ⚓ Riviera 53 (RIY53032D415) - Range Estimator Pro

Consola de control y estimación de autonomía para el Riviera 53. Esta herramienta calcula el **Safe Range** basándose en datos reales de consumo, aplicando un margen de seguridad del 10%.

## 📈 Tabla de Referencia de Rendimiento
| Engine RPM | Speed (Knots) | Total Burn (GPH) | Efficiency (NMPG) | Range (NM)* |
| :--- | :--- | :--- | :--- | :--- |
| **600** | 6.0 | 2.5 | 2.40 | 1,998 |
| **1000** | 9.0 | 8.0 | 1.13 | 936 |
| **1500** | 12.0 | 22.0 | 0.55 | 454 |
| **1800** | 17.5 | 36.0 | 0.49 | 405 |
| **2000** | 22.5 | 46.0 | 0.49 | 407 |
| **2100 (Crucero)** | 24.8 | 51.0 | 0.49 | 405 |
| **2200** | 27.2 | 58.0 | 0.47 | 390 |
| **2300** | 29.5 | 64.0 | 0.46 | 383 |
| **2500 (WOT)** | 33.5 | 74.0 | 0.45 | 377 |

*Datos extraídos del manual de rendimiento oficial para el casco RIY53032D415.

## 🛠️ Funciones de la App
* **Sync RPM:** Sincronización automática de revoluciones entre motores PORT y STBD.
* **Independent GPH:** Consumo de combustible independiente por motor para máxima precisión.
* **Safety Margin:** Cálculo automático de autonomía restando 10% de reserva.
* **Imbalance Alert:** Alerta visual si existe un desbalance de consumo mayor al 10% entre motores.
