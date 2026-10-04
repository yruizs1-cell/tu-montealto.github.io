# ⚡ Monte Alto Electronics

**Movilidad que te impulsa hacia lo alto.**

Landing page oficial de **Monte Alto Electronics**, una empresa familiar de Bogotá (Colombia) dedicada a la venta de **bicicletas eléctricas Evobike y Mobulaa** de ensamble nacional, con repuestos garantizados, seguro contra robo y daño, y soporte posventa especializado.

## 📌 Sobre el proyecto

Sitio web de una sola página (single-page), responsive y de diseño mobile-first, creado para presentar el catálogo, los servicios y las sedes de la empresa, y convertir visitas en contactos por WhatsApp.

La propuesta de valor del sitio se basa en tres ejes:

- **Repuestos asegurados:** marcas con ensambladora nacional.
- **Protección integral:** seguro contra robo y daño para bicicletas y patinetas eléctricas.
- **Posventa confiable:** gestión de garantías, mantenimientos y repuestos con la red de talleres autorizados.

Además explica la normativa colombiana **VELMPU** (≤ 1.000 W, ≤ 40 km/h, una sola plaza), para que los usuarios compren vehículos que puedan circular por la cicloinfraestructura sin matrícula ni SOAT.

## ✨ Características

- Diseño responsive y mobile-first.
- Catálogo de bicicletas eléctricas con filtros por marca (Evobike / Mobulaa) y modal de detalles.
- Botones de WhatsApp en toda la página, con mensaje prellenado según el modelo.
- Sección de seguros contra robo y daño.
- Explicación sencilla de la normativa VELMPU.
- Información de financiación (Addi, Sistecrédito, Vanti, Banco de Bogotá).
- Sección de sedes con botones de WhatsApp, llamada y cómo llegar.
- Indicador "Abierto ahora / Cerrado ahora" por sede (zona horaria America/Bogota).
- Formulario de contacto que redirige a WhatsApp con los datos prellenados.
- Preguntas frecuentes en acordeón.
- SEO optimizado: meta tags, Open Graph y datos estructurados `LocalBusiness`.
- Accesibilidad: contraste AA, atributos ARIA y navegación con teclado.

## 📍 Sedes

| Sede | Dirección | Horario |
|------|-----------|---------|
| **San Andresito de la 38** (principal) | Calle 8 #37A-09, Local 138, Bogotá | Lun a sáb: 9:00 a.m. – 7:00 p.m. · Dom y festivos: 10:00 a.m. – 2:00 p.m. |
| **C.C. Tintal** | Isla frente a Dollar City, Bogotá | Todos los días y festivos: 10:00 a.m. – 7:00 p.m. |

## 🎨 Identidad visual

Basada en el brandbook oficial de la marca.

| Color | Hex | Uso |
|-------|-----|-----|
| Morado (protagonista) | `#7209B7` | Identidad, botones y acentos |
| Negro | `#0B0B0B` | Fondos principales |
| Azul oscuro | `#0D1B2A` | Secciones de respaldo y seguridad |
| Azul | `#0077B6` | Movilidad, detalles secundarios |
| Lila | `#C487FF` | Subtítulos y etiquetas |

**Tipografía:** Montserrat (sans serif, geométrica y legible).

## 🛠️ Tecnologías

- HTML5
- CSS3 (variables CSS, Flexbox y Grid)
- JavaScript (vanilla)
- Google Fonts

## 🚀 Cómo usarlo

1. Clona el repositorio:
```bash
   git clone https://github.com/TU-USUARIO/monte-alto-electronics.git
```
2. Abre `index.html` en tu navegador.
3. Para publicarlo, activa **GitHub Pages** en *Settings → Pages* y selecciona la rama `main`.

## ⚙️ Personalización

Todos los datos editables están en el bloque `CONFIG` al inicio del `<script>`:

```js
const CONFIG = {
  whatsappGeneral: "57XXXXXXXXXX",
  sedes: {
    sanAndresito: { telefono: "...", whatsapp: "...", mapsUrl: "..." },
    tintal:       { telefono: "...", whatsapp: "...", mapsUrl: "..." }
  },
  redes: { instagram: "#", facebook: "#", tiktok: "#" }
};
```

Para completar el sitio, reemplaza:

- `img/logo.png` por el logo oficial.
- Las fotos de `/img/` por imágenes oficiales de Evobike y Mobulaa.
- Los números de WhatsApp y teléfono de cada sede.
- Los enlaces de Google Maps y redes sociales.
- Los modelos y precios por los del catálogo vigente.

## 📁 Estructura

```
monte-alto-electronics/
├── index.html
├── img/
│   ├── logo.png
│   ├── evobike-modelo1.jpg
│   └── mobulaa-modelo1.jpg
└── README.md
```

## 👨‍👩‍👧‍👦 Equipo

Empresa familiar **Ruiz Sánchez**, fundada en 2025:

- Emmanuel Daniel Ruiz Sánchez – Director general
- Yhoah Libeth Ruiz Sánchez – Directora comercial
- Miguel Ángel Ruiz Medina – Director financiero
- Nubia Sofía Sánchez Leiva – Directora administrativa

## 📄 Licencia

© 2026 Monte Alto Electronics. Todos los derechos reservados.
El logo, la identidad de marca y las imágenes de Evobike y Mobulaa son propiedad de sus respectivos titulares.
