# 🏠 RE/MAX Martín Obregón - Sitio Web + Redirección WhatsApp

Sitio web para Martín Obregón, asesor inmobiliario de RE/MAX Boulevard Córdoba.  
Incluye catálogo de propiedades, panel admin con Google Auth, y redirección WhatsApp para Meta Lead Forms.

## 📁 Estructura

```
public/
├── index.html      → Página principal (landing + catálogo)
├── gracias.html    → Redirección WhatsApp (Meta Lead Forms)
└── admin.html      → Panel de administración (Google Auth)
vercel.json         → Configuración de rutas Vercel
```

## 🚀 URLs

| Ruta | Descripción |
|------|-------------|
| `/` | Landing page con info de Martín y catálogo de propiedades |
| `/gracias?nombre=...&preaprobacion=...&cuando=...` | Redirect a WhatsApp con datos del lead |
| `/admin` | Panel admin (solo martinobregon72@gmail.com) |

## 🔧 Setup Firebase + Vercel

Ver instrucciones completas más abajo.
