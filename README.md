# Copper GI — Portal Inmobiliario

Sitio web inmobiliario estilo Zillow para **Copper Gestión Inmobiliaria**, Copiapó, Chile.

## 🌐 Ver Sitio en Vivo

- **Frontend (sitio público):** https://realtape.github.io/properties1/
- **Panel Admin:** https://realtape.github.io/properties1/#admin — usuario: `admin`, contraseña: `admin`

## 📦 Estructura

```
index.html   → Sitio completo (frontend + admin en un solo archivo)
```

## ✨ Características

### Sitio Público
- Hero con buscador inteligente (estilo Zillow)
- Filtros por operación, tipo, sector y precio
- Grid de propiedades con cards, fotos, badges y favoritos
- Vista de detalle por propiedad con formulario de contacto
- Diseño responsive y moderno

### Panel Admin (`admin` / `admin`)
- Dashboard con KPIs en vivo
- CRUD completo de propiedades
- Subida de imágenes por URL
- Gestión de consultas recibidas
- Exportar / Importar base de datos (JSON)

## 💾 Base de Datos

Los datos se almacenan en `localStorage` del navegador. Para migrar a una base de datos real, usa el botón **Exportar** del panel admin.

---
© 2026 Copper Gestión Inmobiliaria — Copiapó, Chile
