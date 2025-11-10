## 📊 Challenge Alura Store Latam: Análisis de Eficiencia de Tiendas 🚀

Este proyecto es el resultado del Challenge de Data Science propuesto por Alura Latam.

### 📝 Descripción del Proyecto

El objetivo principal de este proyecto es realizar un análisis exhaustivo de los datos de ventas y rendimiento de cuatro tiendas (`Tienda 1` a `Tienda 4`) para determinar cuál de ellas es la **menos eficiente** en términos globales. El análisis se enfoca en métricas clave para asesorar a un cliente (el Sr. Juan) sobre qué tienda vender para financiar su nuevo emprendimiento.

-----

### 🎯 Objetivos del Análisis

El análisis se centró en evaluar la eficiencia de las tiendas basándose en los siguientes criterios principales:

1.  **Análisis de Facturación:** Determinar los ingresos totales de cada tienda.
2.  **Satisfacción del Cliente:** Evaluar la calificación promedio de las transacciones.
3.  **Diversificación de Ventas:** Medir la concentración de ventas por categoría de producto.
4.  **Costo de Envío Promedio:** Analizar el costo logístico promedio por tienda.

-----

### 💻 Tecnologías y Herramientas

  * **Lenguaje de Programación:** Python
  * **Librerías:**
      * `pandas` para manipulación y análisis de datos.
      * `matplotlib.pyplot` para la visualización de datos (ej. histogramas de costo de envío).
  * **Entorno:** Jupyter Notebook / Google Colab (Mencionado en la metadata del archivo).

-----

### 📁 Estructura de Datos

El proyecto utiliza cuatro archivos de datos en formato CSV (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`), cargados desde URLs de GitHub.

Cada conjunto de datos contiene la siguiente información por transacción:

| Columna | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| **Producto** | `object` | Nombre del producto vendido. |
| **Categoría del Producto** | `object` | Categoría a la que pertenece el producto. |
| **Precio** | `float64` | Precio de venta del producto. |
| **Costo de envío** | `float64` | Costo de envío de la transacción. |
| **Fecha de Compra** | `object` | Fecha en la que se realizó la compra. |
| **Vendedor** | `object` | Nombre del vendedor. |
| **Lugar de Compra** | `object` | Ciudad donde se realizó la compra. |
| **Calificación** | `int64` | Puntuación de satisfacción del cliente (1 a 5). |
| **Método de pago** | `object` | Método de pago utilizado (Tarjeta de crédito, Nequi, etc.). |
| **Cantidad de cuotas** | `int64` | Número de cuotas para el pago. |
| **lat / lon** | `float64` | Coordenadas geográficas del lugar de compra. |

-----

### 💡 Conclusiones Clave

Tras el análisis de las cuatro tiendas bajo los criterios de ingreso, satisfacción, diversificación y costo de envío, se extrajeron las siguientes conclusiones:

  * **Tienda 3:** Es la tienda con mejor rendimiento global. Destaca por su **alta calificación** de clientes y **buena diversificación** de ventas.
  * **Tienda 1:** Manifiesta los **ingresos más altos**, pero es penalizada por su **calificación baja** y el **costo de envío más alto**.
  * **Tienda 2:** Presenta la **mayor concentración de ventas** en pocos productos.
  * **Tienda 4:** Se identificó como la **menos eficiente** en términos globales. Aunque tiene el menor costo de envío, registra los **ingresos más bajos** y no destaca en satisfacción o diversificación.

#### Recomendación Final:

Se recomienda al **Sr. Juan vender la Tienda 4** para iniciar su nuevo emprendimiento, ya que es la menos eficiente según los criterios evaluados.

-----

### 🧑‍💻 Autor del Proyecto

  * **Alejandro Corona**

### ▶️ ¿Cómo ejecutar el proyecto?

1.  **Clonar el repositorio:**
    ```bash
    git clone https://www.youtube.com/watch?v=44ziZ12rJwU
    cd Challenge-Alura-Store-Latam
    ```
2.  **Instalar dependencias:**
    Asegúrate de tener Python instalado y luego instala las librerías necesarias:
    ```bash
    pip install pandas matplotlib
    ```
3.  **Ejecutar el Notebook:**
    Abre el archivo `Challenge_Alura_Store_Latam(1).ipynb` en tu entorno de Jupyter Notebook o Google Colab y ejecuta todas las celdas secuencialmente para replicar el análisis.
