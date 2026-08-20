# Luana — sitio AI Whisperers (proyecto personal)

**Para:** Luana Lopez (diseño)  
**De:** AI Whisperers (Kyrian Weiss van der Pol)  
**Fecha:** 20 de agosto de 2026  
**Qué es:** un brief para que rediseñes **nuestra** página de empresa. No es un cliente. No se cobra. Queremos ver cómo harías la marca si fuera tuya.

Repo de este brief (para entregas): [Ai-Whisperers/luana-aiw-homepage](https://github.com/Ai-Whisperers/luana-aiw-homepage) — `docs/LUANA.md`  
Código actual del sitio: [Ai-Whisperers/ai-whisperers.org](https://github.com/Ai-Whisperers/ai-whisperers.org) (público, Next.js)

---

## En una frase

La home de ai-whisperers.org se ve como plantilla genérica de “startup de IA”. Los datos del JSON están mal. Vos proponés cómo debería verse de verdad. Nosotros implementamos si nos gusta.

El dominio [https://ai-whisperers.org](https://ai-whisperers.org) ahora da **404**. Eso es infra (Kyrian / Iván), no es tu ticket. Diseñá sobre este brief + el repo.

---

## Qué hay hoy (el problema)

El sitio salió de una plantilla (Next.js 16 + JSON en `content/`). Se nota:

- Paleta indigo / violeta / Inter, look “SaaS genérico”
- Copy de brochure: “AI que Transforma tu Negocio”, análisis de sentimiento, procesamiento de documentos
- Datos de mentira en `content/es/site.json`: teléfono `+595 981 000 000`, RUC `8000000-1`, mail que no usamos en quotes

Eso no es AI Whisperers. AI Whisperers es una empresa **paraguaya** que arma sitios y operación con agentes, cobra por WhatsApp, y habla claro.

---

## Tu trabajo

Propuesta visual de:

1. **Home** (obligatorio) — desktop + celular
2. **Servicios** y **Contacto** (si te da el tiempo)

**Podés cambiar:** layout, tipo, color, fotos, jerarquía, tono visual, cómo se lee el hero.  
**No implementás** el Next.js. No necesitás `npm install`. No publicás a producción.

Entregá Figma, HTML/CSS estático, o PDF de alta. Carpeta: `propuesta/` en el repo de este brief (o Drive, como te quede mejor).

---

## Datos fijos (no se inventan)

| Campo | Valor |
|---|---|
| Marca | **AI Whisperers** (nunca “Erebus”) |
| Dominio | **ai-whisperers.org** (con s) |
| Contacto | Kyrian Weiss · **0985 724 135** (`+595 985 724 135`) |
| CTA | WhatsApp. Número en grande o QR. No alias ni banco |
| Dónde | Paraguay · LATAM |
| Color de papelería actual | `#1F4E79` (navy de cartas/presupuestos). Podés evolucionar la paleta; este es el ancla |

No pongas RUC, no pongas un mail si no te lo confirmamos, no pongas `+595 981 000 000` ni `+595 991 501444`.

---

## Qué vendemos (si aparece en la home)

Copy corto, paraguayo, “vos”. Precios solo si los mostrás — estos, no otros:

| Producto | Cómo decirlo | Precio |
|---|---|---|
| Sitio + operación | Planes mensuales (Básico / Crecimiento / Profesional) | Gs. **290.000** / **490.000** / **890.000** por mes |
| Extra (fuera de plan) | Cambios o trabajo extra | **USD 50/h** |
| paragu-ai CV | CV web para estudiantes (página + PDF + tarjeta con QR) | Gs. **200.000** pago único |

No armes un catálogo de “análisis de sentimiento / loyalty / gift cards”. Eso es basura de la plantilla.

WhatsApp del flyer de CV: `https://wa.me/595985724135?text=Hola%2C%20quiero%20un%20CV%20web`  
WhatsApp general del sitio: `https://wa.me/595985724135?text=Hola%2C%20quiero%20hablar%20con%20AI%20Whisperers`

---

## Dirección visual

- Se lee en 5 segundos: quiénes somos, para quién, qué hacer ahora (escribir).
- AI como **herramienta**, no robot caricaturesco ni cerebro de neón.
- Creíble para un negocio en Asunción / San Lorenzo, no para un VC de San Francisco.
- Mobile first: la mayoría llega de Instagram o WhatsApp.
- Español (vos). Inglés solo si hay un toggle; el default es ES.

---

## Qué no entra

- Porcentajes, splits, ni cómo cobramos entre nosotros
- Alias de transferencia, C.I., RUC
- Hermes dedicado, deals de familia, ni clientes con nombre (Gabi, Saskia, Nexa, John)
- Arreglar el 404 del dominio
- Admin, blog, dark mode, ecommerce, login

---

## Cómo mirar el código (opcional)

Si querés ver la estructura actual (no hace falta para diseñar):

- Home y rutas: `app/`
- Copy y flags: `content/es/`
- Colores actuales (para romperlos): `content/tokens.json`

El repo usa paquetes privados `@ai-whisperers/*`. Si `npm install` pide token, no sigas por ahí — tu entrega es diseño.

---

## Entrega

| Qué | Dónde |
|---|---|
| Home desktop + mobile | `propuesta/` |
| Servicios / Contacto | Opcional, mismo folder |
| Nota de 5–10 líneas | Qué cambiaste y por qué |

Cuando esté, avisá por WhatsApp. Lo revisamos juntos.

---

*AI Whisperers · se puede compartir con Luana.*
