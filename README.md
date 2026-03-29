# Resiliencia-de-la-caja-de-cristal

📊 Resiliencia de la "Caja de Cristal" (Post-Earnings)
🧠 Descripción

Este análisis identifica un patrón avanzado de comportamiento del mercado tras la publicación de resultados (earnings), donde una aparente señal negativa (gap bajista) es absorbida durante la jornada.

El objetivo es detectar activos que muestran resiliencia intradía, sugiriendo la presencia de compradores institucionales ("manos fuertes").

💡 Hipótesis

No todos los gaps bajistas implican debilidad.

En algunos casos:

El precio abre con un gap negativo
Pero durante el día se recupera fuertemente
Y cierra cerca de los máximos

👉 Esto puede indicar acumulación por parte de inversores sofisticados.

🔍 Lógica del análisis

El modelo identifica acciones que cumplen simultáneamente:

📉 Gap bajista en apertura
Apertura < Cierre del día anterior
📈 Recuperación intradía fuerte
El precio de cierre se ubica en el 30% superior del rango diario

Métrica:

(Close - Low) / (High - Low) > 0.7
⚖️ Momentum positivo subyacente
RSI > 50 → sesgo alcista a pesar del gap
📅 Contexto del evento
Evento corporativo: Ganancias (Earnings)
📊 Output

El query devuelve:

ticker_id → Activo identificado
fecha_reporte → Fecha del evento
posicion_cierre_rango → Posición relativa del cierre dentro del rango diario
rsi_14 → Indicador de momentum
🚀 Interpretación

Este patrón puede interpretarse como:

Absorción de presión vendedora
Reacción exagerada inicial del mercado
Presencia de demanda institucional

👉 En muchos casos, precede movimientos alcistas en los días posteriores.

⚡ Caso de uso
Estrategias event-driven trading
Identificación de acumulación institucional oculta
Filtros avanzados para setups de entrada
Complemento para análisis de price action + indicadores técnicos
🧩 Valor de negocio

✔ Detecta oportunidades donde el mercado "dice una cosa, pero hace otra"
✔ Reduce falsos negativos tras noticias aparentemente malas
✔ Permite anticipar cambios en el sentimiento del mercado

🛠️ Tecnologías utilizadas
SQL (CTEs, subqueries, joins)
Datos de:
Eventos corporativos
Precios diarios (OHLC)
Indicadores técnicos (RSI)
📌 Conclusión

Este enfoque va más allá del análisis tradicional de noticias:

No se trata solo de qué pasó, sino de cómo reaccionó el mercado ante eso.

Y ahí es donde aparecen las verdaderas oportunidades.

***
📉 **¿Noticias negativas… o una oportunidad oculta?**

No todos los gaps bajistas significan debilidad.
A veces, el mercado abre en rojo… pero la historia cambia completamente durante el día.

👉 Analicé un patrón que llamo **“resiliencia post-earnings”**:

Empresas que:

* Abren con **gap bajista** tras resultados
* Pero terminan cerrando en la **parte alta del rango diario**
* Y mantienen un **RSI > 50** (momentum positivo)

💡 **Insight clave:**
En estos casos, lo que parece una mala noticia puede estar siendo **absorbida activamente por compradores fuertes**.

---

📊 **¿Qué está pasando realmente?**

* Venta inicial → reacción emocional o automática
* Compra durante el día → entrada de capital más sofisticado
* Cierre fuerte → señal de **acumulación institucional**

---

🧠 **¿Cómo interpretarlo?**

Este patrón puede indicar:

* Reacción exagerada del mercado
* “Manos fuertes” aprovechando precios bajos
* Posible continuación alcista en los días siguientes

---

⚡ **¿Por qué importa?**

Porque muchas oportunidades no están en seguir la noticia…
sino en detectar cuándo el mercado **no confirma esa narrativa**.

---

📌 Pregunta para la comunidad:
¿Alguna vez operaron contra un gap bajista y encontraron este tipo de resiliencia?

#QuantFinance #Trading #DataScience #StockMarket #Earnings #PriceAction #Alpha #Analytics
