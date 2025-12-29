# 📊 Análisis de Ventas de Tienda Retail en Estados Unidos

## 🧩 Contexto
Este proyecto tiene como objetivo realizar un **análisis descriptivo de las ventas** de una tienda retail ubicada en Estados Unidos, con el fin de comprender el desempeño de las sucursales en distintas **Regiones y Estados** entre los años **2015 y 2018**.

El análisis busca apoyar la **toma de decisiones estratégicas** mediante el uso de datos y visualizaciones.

---

## 🎯 Pregunta de negocio
El objetivo de este análisis es presentar, en la reunión de cierre de año de una empresa retail que opera en Estados Unidos, un **resumen de las ventas entre los años 2015 y 2018** en los distintos estados de operación, separadas por regiones.

Las principales preguntas que se buscan responder son:

- ¿Cómo se comportan las ventas a lo largo del tiempo?
- ¿Qué regiones y estados aportan más a las ventas de la empresa?

---

## 📁 Fuentes de datos
Los datos utilizados provienen de un **archivo CSV**, que contiene información relacionada con las ventas de la tienda retail en Estados Unidos.

---

## 🧹 Limpieza y preparación de datos
El archivo CSV fue importado a **Jupyter Notebook** para realizar la limpieza y preparación de los datos utilizando **Python**.

- El dataset **no presentaba datos duplicados**.
- Solo se identificaron valores nulos en la columna **Postal Code**, la cual no es relevante para responder las preguntas del negocio.
- Debido a lo anterior, **no fue necesario eliminar registros** del dataset.

---

## 📈 Visualización y Dashboard
El dashboard fue desarrollado en **Tableau Public**, donde se analizaron las ventas por:

- Mes  
- Año  
- Región  
- Estado  

Se compararon los totales de ventas para estas divisiones mediante distintos tipos de gráficos, permitiendo identificar **tendencias relevantes** para la toma de decisiones del negocio.

🔗 **Link al Dashboard:**  
[Análisis de Ventas de Tienda Retail - Tableau Public](https://public.tableau.com/views/AnlisisdeVentasdetiendaRetail/AnlisisdeVentas?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📝 Conclusiones
Este análisis permite:

- Identificar los **meses con mayores ventas**, facilitando una mejor planificación de stock.
- Detectar **estados y períodos con menores ventas**, lo que abre oportunidades de mejora en la estrategia comercial.
- Optimizar decisiones relacionadas con **precios, descuentos y estrategias de marketing**, con el objetivo de incrementar las ventas.

---

## 🛠️ Herramientas utilizadas
- **Python** (Jupyter Notebook)
- **Pandas**
- **Tableau Public**
