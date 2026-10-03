# Control de Puesto

Inventario y caja para puestos de comida: stock en unidades y kg, compras, combos, ventas del día, cierre con diferencias y reportes. Funciona sin internet; los datos se guardan en el teléfono.

## Funciones
Catálogo (productos y combos) · Compras · Ventas con descuento automático de stock · Cierre del día · Reportes (hoy/7/30 días) · Copia de seguridad · Exportación copiando a Excel.

## Tecnologías
HTML, CSS y JavaScript sin dependencias · localStorage · Service Worker · Web App Manifest.

## Publicar gratis (GitHub Pages)
1. Crea un repositorio en github.com y sube todos los archivos de esta carpeta.
2. Settings > Pages > Branch: `main` / carpeta `/ (root)` > Save.
3. Abre la URL `https://TU-USUARIO.github.io/NOMBRE-REPO/` en Chrome del teléfono.
4. Menú ⋮ > **Instalar aplicación** (o "Agregar a pantalla de inicio"). Ábrela una vez con internet; después funciona sin conexión.
Alternativa: arrastrar la carpeta a app.netlify.com/drop.

## Generar un APK (opcional)
1. Con la app publicada, entra a pwabuilder.com e ingresa la URL.
2. Elige **Android > Generate Package** y descarga el APK.
3. Pásalo al teléfono e instálalo (permite "orígenes desconocidos").

## Pruebas manuales
- Crear producto sin nombre: debe avisar.
- Vender un combo: el stock baja según sus ingredientes.
- Comprar mercancía: se suma al stock.
- Cierre con un conteo menor: aparece la diferencia negativa.
- Reportes: los totales coinciden con lo vendido.
- Copia de seguridad: copiar, borrar datos y restaurar.
- Modo avión: la app abre y funciona.

## Limitaciones
- Datos solo en el navegador/teléfono: usa la copia de seguridad con frecuencia.
- Un solo usuario, sin cuentas.
- La ganancia es una estimación con el costo actual.

## Mejoras futuras
Varios usuarios y sucursales, sincronización en la nube (Supabase), gastos fijos, gráficos por producto, escáner de códigos.

## Texto para portafolio
**Problema:** control en papel o de memoria en un puesto de comida. **Solución:** app instalable y offline que lleva stock, combos, ventas, cierre y reportes. **Tecnologías:** JavaScript, PWA, Service Worker. **Destacado:** descuento automático de ingredientes por combo y detección de diferencias en el cierre. **Beneficio:** saber qué comprar y cuánto se generó cada día.
