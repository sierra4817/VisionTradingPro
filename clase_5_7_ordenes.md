# Clase 5.7: Gestión de órdenes pendientes para entrar tras la confirmación de la figura
## Módulo 5: Patrones de Reversión Gráfica (Chartismo de Giro)

*   **Activo de Referencia:** S&P 500 (US500) en H1.
*   **Enfoque Visual:** MetaTrader 4 (MT4) con fondo negro, velas alcistas verdes y bajistas rojas.

---

### Guion Oficial (500 palabras)

**1. INTRODUCCIÓN Y CONTEXTO VISUAL EN MT4**
Abre tu terminal de la plataforma de ejecución de órdenes de la terminal MetaTrader 4 para escritorio. Configura el gráfico con fondo completamente negro, cuadrícula de fondo desactivada por completo en la configuración, velas alcistas en color verde brillante y velas bajistas en rojo intenso. Selecciona el activo de alta liquidez del índice SP500, identificado como US500, en la temporalidad de una hora de H1. Traza una línea horizontal de color gris de resistencia utilizando la herramienta de líneas de la barra superior de herramientas gráficas de la plataforma, ubicando el cursor en las tres últimas velas cerradas que forman el patrón en tu pantalla de análisis.

**2. EXPLICACIÓN TEÓRICA DEL PATRÓN**
La gestión de órdenes pendientes de entrada es una técnica indispensable para todos los operadores profesionales que buscan entrar al mercado únicamente tras la confirmación definitiva de una figura gráfica. Las órdenes pendientes, como Buy Stop y Sell Stop en MT4, evitan que entremos de forma apresurada e impulsiva al mercado llevados por la emoción o el FOMO de perder la oportunidad. La lógica transaccional de estas órdenes se basa en que solo queremos participar en el movimiento cuando el precio demuestra que tiene la fuerza necesaria para romper un nivel clave de soporte o resistencia y continuar en esa dirección. Al colocar una orden pendiente por encima del máximo o por debajo del mínimo de confirmación, nos aseguramos de que si el precio no realiza la ruptura y regresa en nuestra contra del movimiento inicial, la orden nunca se activará, protegiendo nuestro capital de pérdidas innecesarias.

**3. REGLAS DE ENTRADA, STOP LOSS Y TAKE PROFIT**
Para programar tus órdenes en la plataforma MetaTrader 4 de escritorio, presiona la tecla F9 de tu teclado para abrir la ventana de nueva orden de ejecución de la terminal. Selecciona el tipo de orden pendiente a ejecutar en el menú desplegable. Para una ruptura alcista, configura una orden de tipo Buy Stop tres pips por encima del máximo alcanzado de la vela de ruptura. Ubica tu Stop Loss de protección inicial diez pips por debajo del soporte del patrón, resguardando tu capital total disponible ante giros inesperados. Proyecta el Take Profit objetivo midiendo la altura vertical de la figura. Multiplica este valor por tres y proyecta esta distancia en pips hacia arriba desde el nivel de entrada, estableciendo tu límite Take Profit en MetaTrader 4.

**4. GESTIÓN DE RIESGO Y FILTRO DE FALSAS RUPTURAS**
Filtra la operación evitando mantener la orden pendiente de compra si la estructura gráfica del patrón es invalidada o si el precio rompe en la dirección opuesta antes de activar nuestra posición. Si el volumen transaccional registrado en MetaTrader 4 no acompaña la ruptura alcista, cancela la orden Buy Stop de inmediato. En la gestión de capital, arriesga estrictamente solo y únicamente el uno por ciento del saldo líquido neto de tu cuenta de trading por operación individual en el mercado financiero. Cuando el precio avance cubriendo una distancia igual a tu Stop Loss de protección en puntos, protege tu posición moviendo tu nivel de Stop Loss de protección al precio de entrada original en MetaTrader 4, eliminando el riesgo.
