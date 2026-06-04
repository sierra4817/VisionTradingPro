# Clase 9.2: Cálculo matemático del tamaño de la posición: Fórmulas
## Módulo 9: Gestión de Riesgo y Preservación de Capital

*   **Activo de Referencia:** Nasdaq (NAS100) en H1.
*   **Enfoque Visual:** MetaTrader 4 (MT4) con fondo negro, velas alcistas verdes y bajistas rojas. Planilla de cálculo externa de lotaje.

---

### Guion Oficial (500 palabras)

**1. INTRODUCCIÓN Y CONTEXTO VISUAL EN MT4**
Abre tu terminal de la plataforma de ejecución de MetaTrader 4 para escritorio de tu ordenador personal. Configura el gráfico con fondo completamente negro, cuadrícula de fondo desactivada por completo en la configuración de pantalla, velas alcistas en color verde brillante y velas bajistas en rojo intenso. Selecciona el activo del índice Nasdaq, identificado como NAS100, en la temporalidad de una hora de H1 de la terminal de MetaTrader 4. Abre de forma paralela en la pantalla de tu ordenador tu propia hoja de cálculo cuantitativa diseñada para el cálculo del lotaje de tus posiciones en tu pantalla de análisis de mercado.

**2. EXPLICACIÓN TEÓRICA DEL PATRÓN**
El cálculo matemático exacto del tamaño de la posición es el procedimiento operativo y analítico más importante para garantizar que el riesgo de tu cuenta se mantenga constante sin importar la volatilidad. Cada activo financiero e instrumento en el mercado, como el Nasdaq o el Oro, presenta un valor de pip y una volatilidad estructural completamente diferentes. Por lo tanto, operar siempre de forma improvisada con el mismo lotaje fijo es un error técnico grave que expone tu cuenta de trading a pérdidas desproporcionadas. La fórmula exacta para calcular el volumen de tu operación es el capital máximo a arriesgar dividido entre el producto de la distancia del Stop Loss en pips por el valor del pip del activo. Al dominar esta matemática simple, te aseguras de que una pérdida en el Nasdaq con un Stop Loss de cincuenta pips represente exactamente la misma cantidad de dinero que una pérdida en el Oro con un Stop Loss de cien pips.

**3. REGLAS DE ENTRADA, STOP LOSS Y TAKE PROFIT**
Para calcular de forma exacta el lotaje en Nasdaq u Oro utilizando la plataforma de ejecución MetaTrader 4, presiona la tecla F9 de tu teclado para abrir la ventana de nueva orden de ejecución de la terminal. Mide la distancia desde tu punto de entrada hasta tu Stop Loss de protección utilizando la herramienta de cursor en cruz en H1. Si tu balance de cuenta es de diez mil dólares y arriesgas el uno por ciento del capital, tu riesgo es de cien dólares. Divide cien dólares entre tu Stop Loss en pips multiplicado por el valor del pip en tu terminal de MetaTrader 4 para obtener el lotaje. Ingresa este valor en la casilla de volumen. Proyecta tu Take Profit a una relación de riesgo y beneficio de tres a uno.

**4. GESTIÓN DE RIESGO Y FILTRO DE FALSAS RUPTURAS**
Filtra la operación descartando entrar al mercado si el lotaje calculado es menor al mínimo de la plataforma de cero coma cero un lotes en la terminal de MetaTrader 4. Si el volumen en MetaTrader 4 disminuye drásticamente durante tu sesión de trading diaria, suspende tus operaciones para evitar deslizamientos de precio. En tu gestión de capital, arriesga estrictamente el uno por ciento del saldo disponible líquido de tu propia cuenta de trading por operación individual. Mueve tu Stop Loss de protección al punto de entrada o breakeven en MetaTrader 4 una vez que el precio de cotización cubra tu riesgo de pérdida inicial en pips.
