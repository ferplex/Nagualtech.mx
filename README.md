# TALLER·OS ▣
**Panel de operaciones con IA local para talleres y negocios pequeños**

> Sin internet. Sin suscripción. Sin servidores ajenos.  
> Hecho en Guadalajara, México · [Nautilus Lab](https://nautlab.itch.io)

---

## ¿Qué es?

TALLER·OS es un panel de administración todo-en-uno que corre 100% en tu computadora.
Incluye un asistente de IA por voz y texto (sin internet), inventario, ventas, catálogo de productos y contactos — todo guardado localmente, sin depender de ningún servicio externo.

---

## Módulos incluidos

| Módulo | Descripción |
|---|---|
| 🎛️ **Panel** | Dashboard con ventas (14 días), stock bajo, últimas transacciones y gráfica |
| 💬 **Chat IA** | Asistente Nautilus con voz — conecta a Ollama local, acepta fotos y archivos |
| 🗂️ **Catálogo** | Productos con precio, costo, stock y categoría — importa/exporta CSV |
| 📦 **Inventario** | Historial de entradas, salidas y ajustes de stock |
| 🧾 **Ventas** | Registro de ventas con tickets reimprimibles |
| 👥 **Contactos** | Clientes, proveedores y otros — con teléfono, email y notas |

---

## Funciones del asistente IA

El chat incluye comandos rápidos y consultas en lenguaje natural:

```
/ayuda      → lista todos los comandos disponibles
/stock      → muestra productos con stock bajo
/ventas     → resumen de ventas de los últimos 14 días
/productos  → lista los primeros 12 productos del catálogo
```

También acepta preguntas libres tipo:
- *"¿Qué producto tiene más margen?"*
- *"Escribe una promoción para mis servicios de fin de mes"*
- *"Describe esta imagen"* (requiere modelo con visión como `llava`)

---

## Requisitos

- Windows 10 / 11
- 8 GB RAM mínimo recomendado
- [Ollama](https://ollama.com) — se instala automáticamente con el instalador

**No necesitas cuenta, no necesitas internet, no necesitas configurar nada a mano.**

---

## Instalación

1. Descarga el instalador desde [itch.io](https://nautlab.itch.io)
2. Ejecuta el `.exe` — instala Ollama y descarga el modelo automáticamente
3. Abre TALLER·OS y empieza a usarlo

---

## Temas visuales

TALLER·OS incluye 3 temas seleccionables desde la barra superior:

- 🌸 **Rosa · Dorado** — vibrante, contrastes fuertes
- 🖼️ **Mona Lisa** — cálido, tonos tierra y dorado
- 🐚 **Nautilus** — azul profundo, acento morado

---

## Datos y privacidad

Todos los datos se guardan en `localStorage` del navegador embebido — **nunca salen de tu máquina**.

Para respaldar: usa el botón **⬇ Copiar JSON** en el menú lateral.  
Para limpiar todo: **🗑️ Borrar todos los datos**.

---

## Stack técnico

- HTML + CSS + JavaScript vanilla — sin frameworks, sin dependencias externas
- [Ollama](https://ollama.com) para la IA local (modelos Qwen, LLaMA, LLaVA, etc.)
- Canvas API para las partículas y gráfica de ventas
- Web Speech API para voz (síntesis y reconocimiento)
- `localStorage` para persistencia de datos

---

## Versión

`v2.1` · Nautilus Lab  

---

## Descarga y precio

**[→ Descargar en itch.io](https://nautlab.itch.io)**  
También disponible en [Gumroad](https://nautilulab.gumroad.com) y Ko-fi.

Pago único — licencia permanente — sin suscripción.

---

*Hecho con 🐚 por [ferplex](https://github.com/ferplex) · Nautilus Lab · Guadalajara, México*
