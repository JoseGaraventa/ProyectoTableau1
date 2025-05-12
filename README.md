# 📊 Análisis de Ventas y Márgenes en un Restaurante - Proyecto Tableau

## 📌 Objetivo del Proyecto

El objetivo de este análisis es comprender la dinámica de ventas y márgenes de ganancia en un restaurante ficticio llamado **Bocado Data**. Se busca identificar oportunidades de mejora a través del análisis de:

- Categorías de productos
- Tipo de cliente (nuevo vs. repetido)
- Desempeño de cada mesero

Esto permite proyectar ventas, optimizar estrategias de fidelización y maximizar ingresos y satisfacción del cliente.

---

## 🗂 Fuente de Datos

Este dataset fue obtenido de un curso de Excel que decidí no iniciar. Soy **Licenciado en Turismo**, y mi intención fue utilizar un caso cercano a mi campo profesional (hospitalidad y gastronomía) para desarrollar habilidades en análisis de datos aplicados.

Intenté inicialmente encontrar un dataset relevante en **SINTA** y **Kaggle**, pero terminé eligiendo este conjunto por su estructura manejable y su aplicabilidad al análisis que quería realizar.

---

## 🧭 Proceso de Análisis

### 1. Data Discovery

- Exploración inicial en Excel y Python (pandas).
- Uso de `describe()` para obtener estadísticas básicas.
- Identificación de variables clave.
- Análisis visual realizado en Tableau.

### 2. Usuarios Objetivo

- Gerentes y administradores del restaurante.
- Profesionales del sector gastronómico interesados en fidelización y rentabilidad.
- Analistas de datos que buscan ejemplos de storytelling aplicado.

---

## 🧠 Proceso Creativo y Dashboards

El proyecto fue desarrollado en **tres dashboards principales**:

1. **Análisis de Ventas y Clientes**  
   Visualiza ventas mensuales por tipo de cliente y categoría de producto.

2. **Análisis de Márgenes de Ganancia**  
   Evalúa los márgenes por producto y tipo de cliente.

3. **Conclusiones Finales**  
   Incluye gráficos sobre desempeño de meseros, productos clave y comportamiento del cliente.

---

## 🔧 Campos Calculados

Se desarrollaron **10 campos calculados** para enriquecer el análisis:

- Color por Tipo de Cliente  
- Filtro Dinámico de Cliente  
- Selección de Análisis  
- Selección de Dimensión  
- Condicional KPI  
- Ingreso Promedio por Cliente  
- Margen de Ganancia (valor)  
- Margen de Ganancia (porcentaje)  
- Porcentaje de Ventas por Categoría  
- Propina en Pesos  

---

## 🧩 Conjuntos y Parámetros

### Conjuntos

- **Mesero Mauricio**  
  Filtra solo sus ventas para análisis puntual.
- **Productos de Alta Ganancia**  
  Focaliza en productos más rentables.

### Parámetros Interactivos

- Cambiar de dimensión (producto, mesero, tipo de cliente)  
- Filtro por tipo de cliente  
- Rango de margen de ganancia  
- Tipo de análisis (ventas, márgenes, propinas)

---

## 🧾 Conclusiones

Este análisis permite visualizar claramente el comportamiento de ventas, los márgenes por producto y el rendimiento de los meseros. La estructura de dashboards facilita la toma de decisiones, permitiendo a los usuarios:

- Identificar productos más rentables
- Mejorar estrategias de fidelización
- Evaluar el desempeño del equipo de atención

---
