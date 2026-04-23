# Analisis de Embudo de Conversión y Retención de Usuarios

## 📊 Descripción del Proyecto
Análisis completo del embudo de conversión de MercadoLibre para identificar  puntos críticos de abandono y optimizar la retención de usuarios a través de análisis de cohortes y métricas de producto.

## 🎯 Objetivos Estratégicos
- Mapear el embudo completo de conversión (7 etapas clave)
- Identificar los principales puntos de fuga de usuarios
- Analizar retención por cohortes (D7, D14, D21, D28)
- Proponer mejoras accionables basadas en datos
- Evaluar performance por país y dispositivo

- ## 🛠️ Herramientas y Metodología
- **SQL Avanzado**: CTEs, Window Functions, Análisis de Cohortes
- **Python**: pandas, matplotlib, seaborn para visualizaciones
- **Análisis de Embudo**: Conversión multietapa
- **Análisis de Retención**: Cohortes temporales

- ## 📈 Embudo de Conversión Analizado
1. 🟢 **Descubrimiento** → `first_visit`
2. 🟡 **Interés** → `select_item`
3. 🟠 **Intención** → `add_to_cart`
4. 🔵 **Inicio Compra** → `begin_checkout`
5. 🟣 **Info Envío** → `add_shipping_info`
6. 🟤 **Info Pago** → `add_payment_info`
7. 🔴 **Conversión** → `purchase`

8. ## 📊 Hallazgos Principales
- **Mayor caída**: [X]% entre [select_item] y [add_to_cart]
- **Retención D7**: [X]% de usuarios activos
- **País con mejor conversión**: [Uruguay]

## 🎯 Recomendaciones Estratégicas
- Optimizar proceso de [etapa crítica]
- Implementar notificaciones push para retención D7
- Personalizar experiencia por país/dispositivo
- [Otras recomendaciones específicas]
