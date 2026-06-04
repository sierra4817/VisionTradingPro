# Clase 8.5: Caza de Stops (Stop Hunts): Barridos institucionales de liquidez
## Módulo 8: Análisis Avanzado y Dinámica Institucional

*   **Activo de Referencia:** Oro (XAUUSD) en H1.
*   **Enfoque Visual:** MetaTrader 4 (MT4) con fondo negro, velas alcistas verdes y bajistas rojas.

---

### Guion Oficial (500 palabras)

**1. INTRODUCCIÓN Y CONTEXTO VISUAL EN MT4**
Abre tu terminal de la plataforma de ejecución de órdenes de la terminal MetaTrader 4 para escritorio. Configura el gráfico con fondo completamente negro, cuadrícula de fondo desactivada por completo en la configuración de pantalla, velas alcistas en color verde brillante y velas bajistas en rojo intenso. Selecciona el activo de alta liquidez del Oro, identificado como XAUUSD, en la temporalidad de una hora de H1. Traza una línea horizontal de color gris de soporte que enmarque los mínimos iguales formados en las últimas cuarenta y ocho horas de cotización del activo utilizando la herramienta de líneas de la barra superior en tu pantalla.

**2. EXPLICACIÓN TEÓRICA DEL PATRÓN**
La caza de stops o Stop Hunt es la maniobra institucional más común para capturar la liquidez necesaria antes de iniciar un movimiento expansivo fuerte de tendencia en el mercado. Los creadores de mercado conocen que los operadores minoristas colocan sus Stop Losses agrupados justo debajo de los soportes obvios y por encima de las resistencias horizontales. La psicología operativa de esta maniobra consiste en empujar temporalmente el precio por debajo del soporte para hacer creer a las masas que el nivel ha fallado y que el precio seguirá cayendo. Esto fuerza a los compradores minoristas a cerrar sus posiciones con pérdidas y activa las órdenes Sell Stop a mercado. Las instituciones financieras absorben todas estas ventas baratas de pánico activando sus propias compras masivas en la zona de descuento. El resultado es una mecha muy larga de rechazo en tu gráfico negro de MetaTrader 4, confirmando la absorción de liquidez.

**3. REGLAS DE ENTRADA, STOP LOSS Y TAKE PROFIT**
Para operar la caza de stops en la plataforma MetaTrader 4 de escritorio, presiona la tecla F9 de tu teclado para abrir la ventana de nueva orden de ejecución de la terminal de MetaTrader 4. Espera el barrido violento del nivel de soporte horizontal y el cierre de la vela H1 de reacción alcista en tu pantalla. Coloca una orden programada de tipo Buy Stop tres pips por encima de la vela de reacción que dejó la mecha larga. Configura tu Stop Loss de protección diez pips por debajo del mínimo de la mecha de barrido, resguardando tu capital total de operaciones. Proyecta tu Take Profit midiendo la distancia desde el mínimo de la mecha hasta la resistencia superior. Multiplica este valor por tres y prográmalo en MetaTrader 4.

**4. GESTIÓN DE RIESGO Y FILTRO DE FALSAS RUPTURAS**
Filtra la operación evitando comprar si la vela de barrido cierra con cuerpo sólido por debajo de la línea horizontal de soporte, lo que indicaría un quiebre bajista real de tendencia y no una caza de stops. Si el volumen en MetaTrader 4 no supera el promedio durante el barrido, cancela tu orden pendiente Buy Stop de forma inmediata en la plataforma. En tu gestión de capital, arriesga estrictamente solo el uno por ciento del saldo disponible líquido de tu cuenta de trading por operación individual. Protege tu posición moviendo tu nivel de Stop Loss al precio de entrada original en MetaTrader 4 cuando el precio de cotización del activo cubra tu riesgo inicial de pérdida.
