# Clase 7.1: Medias Móviles Exponenciales (EMA) de 50 y 200 periodos
## Módulo 7: Indicadores Técnicos como Filtros Estadísticos

*   **Activo de Referencia:** S&P 500 (US500) en H1.
*   **Enfoque Visual:** MetaTrader 4 (MT4) con fondo negro, velas alcistas verdes y bajistas rojas.

---

### Guion Oficial (500 palabras)

**1. INTRODUCCIÓN Y CONTEXTO VISUAL EN MT4**
Abre tu terminal de la plataforma de ejecución de órdenes de la terminal MetaTrader 4 para escritorio. Configura el gráfico con fondo completamente negro, cuadrícula de fondo desactivada por completo en la configuración de pantalla, velas alcistas en color verde brillante y velas bajistas en rojo intenso. Selecciona el activo de alta liquidez del índice S&P 500, identificado como US500, en la temporalidad de una hora de H1. Inserta dos Medias Móviles Exponenciales de la sección de indicadores tendenciales de la plataforma, configurando la primera EMA de cincuenta periodos en color azul brillante y la segunda EMA de doscientos periodos en color amarillo dorado en tu pantalla de análisis de gráficos.

**2. EXPLICACIÓN TEÓRICA DEL PATRÓN**
Las Medias Móviles Exponenciales, o EMA, son herramientas de análisis técnico diseñadas para suavizar la acción del precio y filtrar el ruido transaccional de corto plazo. A diferencia de las medias simples, las EMA otorgan mayor peso a los datos de cotización más recientes, reaccionando con mayor velocidad a los cambios de flujo de órdenes. La combinación de las EMA de cincuenta y doscientos periodos es la herramienta institucional estándar para identificar la dirección macro del mercado financiero. La psicología operativa de estas medias nos muestra zonas de soporte y resistencia dinámicos de alta relevancia. Cuando el precio cotiza de forma sostenida por encima de ambas medias, el momentum dominante del activo es alcista. Las instituciones financieras utilizan la EMA de doscientos periodos como el filtro definitivo de tendencia: solo buscamos compras de alta probabilidad si el precio está por encima, y solo ventas si está por debajo de las medias.

**3. REGLAS DE ENTRADA, STOP LOSS Y TAKE PROFIT**
Para operar utilizando estas medias en la plataforma MetaTrader 4, presiona la tecla F9 para abrir la ventana de nueva orden de ejecución de la terminal. No cometas el error de entrar al mercado simplemente porque las medias se cruzan. Espera a que el precio realice un retroceso ordenado y testee la zona intermedia entre la EMA de cincuenta y la EMA de doscientos periodos en tu gráfico. Coloca una orden programada de tipo Buy Stop tres pips por encima de la primera vela alcista de rechazo que cierre en H1. Configura tu Stop Loss de protección diez pips por debajo de la EMA de doscientos periodos, resguardando tu capital de operaciones. Proyecta tu Take Profit midiendo la distancia al último máximo relevante. Multiplica esta distancia por tres y colócala en MetaTrader 4.

**4. GESTIÓN DE RIESGO Y FILTRO DE FALSAS RUPTURAS**
Filtra la operación evitando comprar si las dos medias móviles se cruzan de forma constante y plana, lo que indica un mercado en rango lateral de acumulación sin tendencia definida. Si el volumen transaccional real registrado es bajo durante el testeo dinámico, cancela tu orden pendiente Buy Stop de forma inmediata. En la gestión de capital, arriesga estrictamente solo el uno por ciento del saldo disponible líquido neto de tu cuenta de trading por operación individual. Cuando el precio avance a tu favor cubriendo una distancia igual a tu Stop Loss, protege la posición moviendo tu Stop Loss al punto de entrada en MetaTrader 4.
