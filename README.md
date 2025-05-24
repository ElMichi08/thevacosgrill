# De Vacos Grill

Aplicación móvil desarrollada en Flutter para el restaurante _The Vacos Grill_.  
Permite gestionar el menú, registrar clientes, crear pedidos y generar comprobantes de venta en PDF/imagen. Los datos se almacenan localmente en SQLite.

## 🚀 Características

- Gestión de **clientes**: alta, edición y búsqueda rápida.  
- Creación y seguimiento de **pedidos** (estado: pendiente, en preparación, listo, entregado).  
- Generación automática de **comprobantes** (PDF o imagen) con opción de envío por QR, correo o WhatsApp.  
- **Dashboard** de estadísticas de ventas.  
- Exportación de datos a CSV.  

## 🔧 Tecnología

- **Frontend:** Flutter (Dart)  
- **Base de datos:** SQLite (sqflite)  
- **Generación de comprobantes:** HTML → PDF/PNG (WeasyPrint / Puppeteer / pdf_render)  
- **CI/CD / Repo:** GitHub

## 📦 Instalación

1. Clona el repositorio  
   ```bash
   git clone https://github.com/tu-usuario/the-vacos-grill.git
