# sprint7-final-project
Proyecto del Sprint Numero 7 - TripleTen Analista De Datos Bootcamp

# 📊 Análisis de Datos - Everpeak Retail

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento de compra de los clientes de Everpeak Retail, identificando patrones en el volumen de compra, métodos de pago y segmentación de clientes para generar insights útiles para áreas como marketing y finanzas.

---

## 📁 Datasets Utilizados

Se utilizaron los siguientes archivos:

- `everpeak_clean.csv` → Dataset limpio con información de clientes y compras.
- `everpeak_retail.csv` → Dataset con información de transacciones y métodos de pago.

Ambos contienen variables clave como:
- `quantity` (cantidad de productos comprados)
- `order_value` (valor de la orden)
- `customer_age` (edad del cliente)
- `payment_method` (método de pago)

---

## 🔎 Etapas del Análisis

El análisis se desarrolló en las siguientes etapas:

1. **Exploración de datos (EDA)**
   - Revisión de estructura
   - Identificación de valores nulos
   - Análisis de variables clave

2. **Estadística descriptiva**
   - Cálculo de media, mediana y percentiles
   - Identificación de outliers (ej. percentil 99)

3. **Segmentación de clientes**
   - Segmentación por volumen de compra (alto, medio, bajo)
   - Segmentación por edad (Jr. vs Sr.)
   - Segmentación combinada (edad + volumen)

4. **Análisis de métodos de pago**
   - Clasificación entre pagos con tarjeta y sin tarjeta
   - Relación entre método de pago y volumen de compra

5. **Feature Engineering**
   - Creación de nuevas columnas como:
     - `volume_segment`
     - `payment_segment`

