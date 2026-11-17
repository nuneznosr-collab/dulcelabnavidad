# DulceLab Navidad – sitio estático

## Publicar en Render (IMPORTANTE)
1. En Render pulsa **New → Static Site** (NO Web Service y NO Docker).
2. Conecta el repositorio de GitHub que contiene el contenido de esta carpeta.
3. Branch: `main`.
4. Root Directory: vacío.
5. Build Command: vacío.
6. Publish Directory: `.`
7. Pulsa **Create Static Site**. No se necesita `requirements.txt`, `Dockerfile`, ni Start Command.

## GitHub
Descomprime este ZIP y sube el CONTENIDO de `DulceLab_Navidad_2026` al nivel principal del repositorio, de modo que `index.html`, `styles.css`, `script.js` y `assets/` queden visibles en la raíz. No subas solamente el ZIP.

## Configurar WhatsApp
Abre `script.js` y busca `const CONFIG={whatsapp:'',currency:'S/'};`. Coloca el número comercial con código de país, solo dígitos, sin `+` ni espacios. Ejemplo de formato: `519XXXXXXXX`. No se ha inventado ningún número. Mientras esté vacío, el formulario no abrirá WhatsApp y mostrará un aviso.

## Logotipo
El logotipo original no estaba adjunto a esta entrega. El encabezado utiliza una marca tipográfica provisional. Cuando compartas el archivo original, reemplaza ese bloque por la imagen oficial sin reconstruirla.

## Precios y condiciones
Los precios están centralizados en `script.js` y son referenciales, según el encargo. Validarlos con fichas de costos antes de vender. El sistema no procesa pagos ni confirma pedidos. El pedido se envía como solicitud por WhatsApp cuando se configure el número comercial.

## Contenido y seguridad
Las fotografías de productos son ilustrativas. Ingredientes, alérgenos, conservación, pesos y fechas deben completarse con información verificada en las etiquetas y fichas reales. Choco Lab incluye leche en polvo en ambas variantes.

## Archivos
- `index.html`: página principal y modales de compra.
- `styles.css`: diseño responsive.
- `script.js`: catálogo central, configuradores, carrito persistente y solicitud de pedido.
- `pages/passport.html`: Pasaporte DulceLab digital.
- `pages/*.html`: rutas de acceso a cada detalle de producto.
- `assets/hero-navidad.png`: fotografía principal generada para la colección.
