# AdventureWorks: Análisis de ROI por país (SQL)

Análisis de rentabilidad sobre la base comercial de AdventureWorks para responder una pregunta de negocio concreta: ¿en qué países conviene invertir y en cuáles se está perdiendo margen?

## Business Question

La dirección comercial necesitaba saber dónde concentrar el presupuesto de expansión. La venta bruta por país no basta, porque un mercado puede vender mucho y dejar poco margen. El objetivo fue medir el retorno real (ROI) por país y priorizar con criterio financiero, no por volumen.

## Stack

- **SQL** (consultas, joins entre ventas, costos y territorio, agregaciones y funciones de ventana)
- Modelo de datos relacional tipo estrella (ventas, producto, territorio, costo)

## Approach

1. Integré ventas, costos de producto y territorio con joins sobre la base transaccional.
2. Calculé ingreso, costo y margen por país, y a partir de ahí el ROI.
3. Ordené y segmenté los países por retorno para separar los que aportan margen de los que solo aportan volumen.

## Key Findings

- Países con alta venta bruta pero ROI bajo, donde el volumen escondía márgenes pobres.
- Mercados pequeños en facturación pero con retorno alto, candidatos claros a recibir más inversión.
- Recomendación accionable: redistribuir presupuesto hacia los mercados de mayor ROI en lugar de premiar el volumen.

## Qué demuestra este proyecto

Capacidad de traducir una base transaccional en una decisión de asignación de presupuesto, usando el lenguaje de negocio (margen, ROI, priorización) y no solo el técnico.

## Portafolio completo

Narrativa extendida, capturas y contexto de los cuatro proyectos:
https://carnation-valley-5b8.notion.site/Portafolio-Miguel-Villanueva-Analista-de-Datos-Jr-39b96a34a82b814ebc81f59d3e5c833e

## Contacto

Miguel Villanueva Herrera, Analista de Datos Jr.
Correo: ing.miguelvillanuevaherrera@gmail.com
LinkedIn: https://www.linkedin.com/in/miguel-villanueva-784421309
