# Montaje y Mantenimiento de Equipos
### Proyecto Intermodular — David Tío Vallejo
 
---
 
## Descripción
 
Este repositorio contiene el proyecto del módulo de **Montaje y Mantenimiento de Equipos (0221)**, donde se ha diseñado y justificado la infraestructura hardware necesaria para una empresa de dos plantas con distintos perfiles de uso: ofimática básica y alto rendimiento (producción y ciberseguridad).
 
---
 
## Contexto de la empresa
 
La empresa consta de **2 plantas** y un total de aproximadamente **20-25 equipos**. Los puestos se dividen en dos categorías principales:
 
- **Ofimática** (RRHH, Administración, Recepción, Marketing, Gerencia): 17 equipos para tareas básicas como bases de datos, navegación web y gestión documental.
- **Alto rendimiento** (Producción y Ciberseguridad): 6 equipos para virtualización masiva, pentesting y mantenimiento de servidores.
---
 
## Estructura del repositorio
 
```
📦 montaje-mantenimiento-equipos
 ┣ 📄 README.md
 ┣ 📄 Documentacion.docx         → Documento principal con todo el proyecto
 ┣ 📊 Presentacion.pptx          → Presentación del proyecto
```
 
---
 
## Configuraciones de hardware
 
### Equipo de Ofimática (17 unidades)
| Componente | Modelo |
|---|---|
| CPU | Intel Core i5-12400 (6 núcleos, 2.5 GHz) |
| RAM | 16 GB DDR4 3200 MHz |
| Almacenamiento | SSD SATA 512 GB |
| Gráficos | Integrados en CPU |
| Placa base | ASUS Prime B760M-A D4-CSM |
| Fuente | 500 W |
 
### Equipo de Alto Rendimiento — Producción/Ciberseguridad (6 unidades)
| Componente | Modelo |
|---|---|
| CPU | Intel Core i9 13ª Gen (hasta 5.50 GHz) |
| RAM | 32 GB DDR5 5200 MHz |
| Almacenamiento | SSD NVMe 2 TB Samsung |
| GPU | Gigabyte AERO OC GeForce RTX 5060 8 GB GDDR7 |
| Placa base | Gigabyte B760 DS3H LGA 1700 DDR5 |
| Chasis | Corsair 3000D AIRFLOW |
| Fuente | 850 W Full Modular |
 
---
 
## Proceso de montaje
 
El montaje sigue estos pasos principales:
 
1. Preparación antiestática y colocación de la caja sobre superficie no conductora
2. Instalación del procesador en la placa base (socket LGA, triángulo alineado)
3. Instalación de la RAM en slots A2 y B2 para configuración Dual Channel
4. Fijación de la placa base en los standoffs del chasis
5. Instalación del disipador de CPU
6. Colocación de discos en bahías y conexión de cables SATA y alimentación
7. Instalación de la fuente de alimentación (giro de 90º para alineación)
8. Conexión de ventiladores y panel frontal a la placa base
9. Primer encendido y verificación mediante pitidos POST de la placa base
---
 
## Mantenimiento de los equipos
 
El mantenimiento no se limita a la limpieza física. Incluye:
 
- **Limpieza periódica** del polvo interior para evitar sobrecalentamiento y ralentización
- **Test de memoria RAM** con **Memtest86** (USB booteable, mínimo 2 pasadas)
- **Salud del disco duro** con **CrystalDiskInfo** (temperatura, vida útil, estado S.M.A.R.T.)
- **Monitorización de temperaturas** con **Open Hardware Monitor** (CPU, GPU, RAM, núcleos)
- **Creación de USB booteable** con **Rufus** (individual) o **Ventoy** (multi-boot)
---
 
## Inventario de equipos
 
| ID | Equipo | Ubicación | Cantidad | Estado |
|---|---|---|---|---|
| 01 | PC Ofimática | RR.HH. – Planta 1 | 5 | Activo |
| 02 | PC Ofimática | Administración – Planta 2 | 4 | Activo |
| 03 | PC Ofimática | Recepción – Planta 1 | 2 | Activo |
| 04 | PC Ofimática | Marketing – Planta 2 | 3 | Activo |
| 05 | PC Ofimática | Gerencia – Planta 2 | 3 | Activo |
| 06 | PC Alto Rendimiento | Producción – Planta 2 | 3 | Activo |
| 07 | PC Alto Rendimiento | Ciberseguridad – Planta 2 | 3 | Activo |
| 08 | Servidor Principal | CPD – Planta 1 | 1 | Activo |
| 09 | Servidor Respaldo | CPD – Planta 1 | 1 | Activo |
| 10-11 | Impresoras de red | Planta 1 y 2 | 2+2 | Activo |
| 12-14 | Monitores 27" Eye Care | Todos los puestos + almacén | 35 | Activo/Almacén |
| 15-16 | Teclado y ratón Logitech | Todos los puestos | 23+23 | Activo |
 
---
 
## Autor
 
**David Tío Vallejo**
Módulo: Montaje y Mantenimiento de Equipos (0221)
Proyecto Intermodular — 2025/2026
