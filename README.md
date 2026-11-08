# ⚡ ARGO · EcoVolt

> **Gestión Energética Inteligente y Ahorro en la Factura Eléctrica**  
> Prototipo funcional interactivo enmarcado en interfaz móvil para optimizar el consumo del hogar en el mercado eléctrico español (PVPC 2.0TD y mercado libre).

---

## 🚀 Demo en Vivo
Puedes probar la aplicación directamente desde el navegador:  
👉 **[Ver Demo en GitHub Pages](https://Juanma265.github.io/ecovolt-app/)**

---

## 📱 Módulos de la Aplicación

1. **📄 Mi Factura (OCR & Desglose Simple)**
   - Traducción de facturas complejas a lenguaje comprensible.
   - Separación visual entre potencia contratada (término fijo), energía consumida e impuestos/alquiler.
   - **Diagnóstico ARGO:** Detección de sobrecontratación de potencia con estimación de ahorro anual.

2. **🕐 Horas Baratas (Optimizador de Electrodomésticos)**
   - Monitor de precios en tiempo real con semáforo inteligente (Valle, Llano y Punta).
   - Compatible con **PVPC (tarifa regulada)** y **Mercado Libre** (3 tramos o precio fijo 24h).
   - Curva horaria interactiva con Chart.js.
   - Calculadora de **ventanas continuas óptimas** según potencia y duración de cada aparato (lavadora, lavavajillas, coche eléctrico, etc.).
   - Programación de avisos con recordatorios personalizables.

3. **🔌 Electro G (Cazador de Vampiros Energéticos)**
   - Auditoría de electrodomésticos antiguos (etiquetas F y G).
   - Simulador de sustitución por modelos eficientes (Clase A o B).
   - Cálculo automático de kWh reducidos, ahorro en €/año y periodo de amortización (*Payback* en años y meses).

4. **🏠 Hogar IA (Telemetría & Agente Autónomo)**
   - Monitorización en vivo multi-suministro: Electricidad (W), Agua (L/min) y Gas (m³).
   - Interruptores de control para enchufes inteligentes simulados.
   - Selector de modos: *Ahorro Agresivo*, *Confort Equilibrado* y *Modo Manual*.
   - Feed de decisiones tomadas de forma autónoma por el agente inteligente.

---

## 🛠️ Tecnologías Utilizadas

- **Frontend:** React 18 (SPA interactiva sin dependencias locales pesadas).
- **Estilos:** CSS3 / Variables de diseño responsivo emulando viewport nativo móvil (390px).
- **Gráficos:** [Chart.js](https://www.chartjs.org/) (curva horaria de precios y gráficos donut).
- **Tipografías:** Cinzel & Inter (Google Fonts).

---

## 💻 Ejecución Local

No requiere instalación de Node.js ni empaquetadores:

1. Clona el repositorio:
   git clone https://github.com/Juanma265/ecovolt-app.git
2. Abre el archivo `index.html` directamente en cualquier navegador web.
