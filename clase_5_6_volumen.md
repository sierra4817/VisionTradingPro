# Clase 5.6: Filtrado de falsos giros: El uso del volumen para confirmar el cambio de tendencia
## Módulo 5: Patrones de Reversión Gráfica (Chartismo de Giro)

*   **Activo de Referencia:** Nasdaq (NAS100) en H1.
*   **Enfoque Visual:** MetaTrader 4 (MT4) con fondo negro, velas alcistas verdes y bajistas rojas.

---

### Guion Oficial (500 palabras)

**1. INTRODUCCIÓN Y CONTEXTO VISUAL EN MT4**
Abre tu terminal de la plataforma de ejecución de órdenes de la terminal MetaTrader 4. Configura el gráfico con fondo completamente negro, cuadrícula de fondo desactivada por completo en la configuración, velas alcistas en color verde brillante y velas bajistas en rojo intenso. Selecciona el activo del índice Nasdaq de alta tecnología, identificado como NAS100, en la temporalidad de una hora, H1. Traza una línea horizontal gris de soporte en el mínimo más bajo utilizando la herramienta de líneas de la barra superior de herramientas gráficas. Agrega el indicador de volumen nativo en la parte inferior del gráfico, observando las barras de volumen institucionales en relación a las velas japonesas en tu pantalla de análisis.

**2. EXPLICACIÓN TEÓRICA DEL PATRÓN**
El filtrado de falsos giros es una de las habilidades más difíciles pero necesarias para la consistencia operativa a largo plazo de un trader profesional. La mayoría de los operadores minoristas o retail cometen el error de comprar cualquier soporte o vender cualquier resistencia simplemente porque el precio toca el nivel. Las instituciones financieras conocen este comportamiento y provocan rupturas falsas o sweeps para absorber la liquidez de los stops de protección o Stop Losses acumulados. El volumen de transacciones real en puntos es la única herramienta que revela la presencia de participación institucional en la zona. Un giro de tendencia de alta probabilidad requiere que el volumen disminuya durante el retroceso al nivel clave y aumente sustancialmente cuando la vela reaccione en la dirección del giro, lo que indica la entrada de capital profesional e institucional al mercado.

**3. REGLAS DE ENTRADA, STOP LOSS Y TAKE PROFIT**
Para operar un giro confirmado en la plataforma MetaTrader 4 de escritorio, presiona la tecla F9 de tu teclado para abrir la ventana de nueva orden de ejecución de órdenes del terminal. Espera al cierre definitivo de la vela H1 que reaccione en el soporte con una barra de volumen que supere el promedio de las últimas diez sesiones. Coloca una orden programada de tipo Buy Stop tres pips por debajo del máximo de la vela de ruptura. Ubica tu Stop Loss de protección inicial diez pips por debajo del mínimo de la mecha inferior de la vela de reacción del soporte, resguardando tu capital ante barridos. Para el Take Profit, proyecta el tamaño de la vela de reacción multiplicado por tres hacia arriba, estableciendo tu orden límite Take Profit objetivo en MetaTrader 4.

**4. GESTIÓN DE RIESGO Y FILTRO DE FALSAS RUPTURAS**
Filtra la operación descartando la señal de compra si el precio rompe el nivel de soporte pero el volumen de la ruptura es inferior al promedio, indicando una falta de interés institucional de venta. Si el volumen en MetaTrader 4 no supera el promedio, cancela la orden Buy Stop de inmediato. En la gestión de capital, arriesga estrictamente solo el uno por ciento del saldo líquido neto de tu cuenta de trading por operación individual en el mercado. Cuando el precio avance cubriendo una distancia igual a tu Stop Loss de protección, protege la posición moviendo tu nivel de Stop Loss al precio de entrada original en MetaTrader 4, eliminando el riesgo.
