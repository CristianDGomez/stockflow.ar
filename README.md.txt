# 📦 StockFlow AR — ERP & Punto de Venta Offline con Conversión USD/ARS

**StockFlow AR** es una aplicación web ligera y autocontenida diseñada para resolver la gestión de inventario, control de ingresos/egresos de mercadería y actualización dinámica de precios frente a la volatilidad cambiaria (Dólar → Peso Argentino), operando **100% sin conexión a internet**.

---

## 🚀 Características Principales

* **Conversión Cambiaria en Tiempo Real (USD → ARS):** Permite actualizar la cotización del dólar desde la barra superior y recalcula automáticamente costos, precios de venta y valuación total del inventario.
* **Arquitectura 100% Offline (Zero-Dependencies):** Desarrollado en HTML5, CSS3 y Vanilla JavaScript puro en un único archivo ejecutable, sin servidores externos ni latencia.
* **Integración Nativa con Excel (`.csv`):**
  * Descarga de plantilla estructurada.
  * Importación masiva por selección o arrastrar y soltar (*Drag & Drop*) con actualización inteligente por SKU.
  * Exportación de inventario valuado y reportes de movimientos listos para Excel.
* **Punto de Venta (POS) y Auditoría de Stock:** Registro rápido de ventas (egresos) y reposiciones (ingresos) con descuento automático de stock y alertas visuales de stock crítico.
* **Persistencia Local:** Almacenamiento automático en el navegador (`localStorage`) para mantener la información segura entre sesiones.

---

## 🛠️ Stack Tecnológico

* **Frontend:** HTML5 Semántico, CSS3 (Grid / Flexbox / Variables CSS), JavaScript (ES6+).
* **Procesamiento de Datos:** Parser CSV nativo con soporte de encoding UTF-8 para compatibilidad directa con Microsoft Excel.
* **Almacenamiento:** Web Storage API (`localStorage`).

---

## 💻 Cómo usarlo localmente

1. Descarga o clona este repositorio:
   ```bash
   git clone [https://github.com/CristianDGomez/stockflow-ar.git](https://github.com/CristianDGomez/stockflow-ar.git)