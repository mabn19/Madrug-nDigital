# 🧵 Madrugón Digital - Plataforma de E-commerce Inclusivo

> **Marketplace digital para comerciantes tradicionales del Madrugón de San Victorino (Bogotá)**  
> *Prototipo desarrollado para hackathon - Sistema completo de e-commerce con cadena de distribución*

## 🎯 Descripción del Proyecto

**Madrugón Digital** es una plataforma web que busca **reducir la brecha digital** y **mejorar las condiciones económicas** de los comerciantes del tradicional Madrugón de San Victorino en Bogotá, permitiéndoles gestionar pedidos en línea, organizar entregas y llegar a más clientes sin depender únicamente de las aglomeraciones presenciales.

### 🌟 Problemática Solucionada

- **🔒 Inseguridad:** Aglomeraciones en el centro de Bogotá
- **📱 Exclusión digital:** Comerciantes sin acceso a plataformas digitales  
- **🚚 Logística ineficiente:** Sistemas de entrega no optimizados
- **📉 Alcance limitado:** Clientela restringida a compradores presenciales

## 🏗️ Arquitectura del Sistema

### 👥 Roles de Usuario

| Rol | Descripción | Funcionalidades Principales |
|-----|-------------|----------------------------|
| **👤 Cliente** | Compradores finales | Registro, catálogo, carrito, pedidos, seguimiento |
| **🏪 Comerciante** | Vendedores del Madrugón | Gestión de productos, pedidos, especificación de volumen |
| **🚚 Distribuidor** | Gestor de logística | Gestión de envíos, flota vehicular, asignación automática |
| **⚙️ Administrador** | Superusuario del sistema | Gestión global, estadísticas, creación de usuarios |

### 🔄 Flujos de Trabajo
Cliente registrado → Explora catálogo → Realiza pedido
→ Comerciante procesa → Especifica volumen del paquete
→ Sistema crea envío automático → Distribuidor asigna vehículo
→ Entrega completada → Cliente recibe producto

## 🛠️ Tecnologías Utilizadas

### Frontend
- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño responsive
- **Tailwind CSS** - Framework de utilidades
- **JavaScript (ES6+)** - Lógica de cliente
- **Paradigma POO** - Arquitectura modular y escalable

### Características Técnicas
- ✅ **Arquitectura modular** por roles
- ✅ **Persistencia local** sin necesidad de base de datos
- ✅ **Interfaz responsive** para móviles y desktop
- ✅ **Validaciones en tiempo real**
- ✅ **Sistema de autenticación** por roles
- ✅ **Flujos de trabajo completos** integrados

## 🚀 Instalación y Ejecución

### Prerrequisitos
- Node.js 14+ instalado
- Navegador web moderno

### Pasos para Ejecutar
```bash
# 1. Clonar o descargar el proyecto
git clone <url-del-repositorio>
cd madrugon-digital

# 2. Instalar dependencias
npm install

# 3. Ejecutar servidor de desarrollo
node server.js

# 4. Abrir en navegador
# http://localhost:3000
