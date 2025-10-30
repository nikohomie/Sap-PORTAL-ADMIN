# 🎓 Portal de Capacitación SAP HANA

Portal web interactivo para acceder a videos de capacitación en SAP HANA, organizado por módulos y unidades.

## 🌟 Características

- ✅ **12 Módulos de Capacitación** con videos embebidos
- ✅ **Panel de Administración** para gestionar videos
- ✅ **Búsqueda y Filtros** por módulo y palabra clave
- ✅ **Diseño Responsive** - funciona en móviles, tablets y desktop
- ✅ **Interfaz Moderna** estilo streaming
- ✅ **Sistema de Progreso** con seguimiento de videos vistos
- ✅ **Gestión de Videos** - agregar, editar y eliminar
- ✅ **Exportar/Importar** datos de respaldo

## 🚀 Acceso Rápido

Visita el portal en: `https://TU-USUARIO.github.io/TU-REPOSITORIO/`

(Reemplaza con tu URL de GitHub Pages una vez publicado)

## 📦 Estructura del Proyecto

```
sap-portal/
├── index.html          # Portal principal (archivo único)
└── README.md          # Este archivo
```

## 🌐 Cómo Publicar en GitHub

### Paso 1: Crear un Repositorio en GitHub

1. Ve a [GitHub](https://github.com) e inicia sesión
2. Haz clic en el botón **"New"** (o "Nuevo repositorio")
3. Nombra tu repositorio, por ejemplo: `portal-sap-capacitacion`
4. Selecciona **"Public"** (para que sea accesible)
5. **NO** inicialices con README (ya tienes uno)
6. Haz clic en **"Create repository"**

### Paso 2: Subir los Archivos

**Opción A: Desde la Web (Más Fácil)**

1. En tu nuevo repositorio, haz clic en **"uploading an existing file"**
2. Arrastra los archivos `index.html` y `README.md`
3. Escribe un mensaje de commit: "Subir portal SAP"
4. Haz clic en **"Commit changes"**

**Opción B: Desde la Terminal (Git)**

```bash
git init
git add .
git commit -m "Portal SAP inicial"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repositorio, ve a **Settings** (Configuración)
2. En el menú lateral, busca **"Pages"**
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona **"main"** y carpeta **"/ (root)"**
5. Haz clic en **"Save"**
6. ¡Espera 1-2 minutos y tu sitio estará publicado!

Tu portal estará disponible en:
```
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```

## 🔐 Panel de Administración

### Acceso Inicial

- **Contraseña por defecto:** `admin123`
- Para acceder: Haz clic en el botón **"🔒 Admin"** en la parte superior

### Funciones del Panel

- 📹 **Agregar Videos:** Ingresa código numérico y URL de YouTube
- ✏️ **Editar Videos:** Modifica URLs existentes
- 🗑️ **Eliminar Videos:** Borra videos del portal
- 📊 **Estadísticas:** Visualiza progreso y módulos completados
- 📤 **Exportar:** Descarga backup en formato JSON
- 📥 **Importar:** Restaura desde archivo de respaldo
- 🔑 **Cambiar Contraseña:** Actualiza tu contraseña de admin

### Formato de URLs de YouTube

El sistema acepta cualquier formato de URL de YouTube:

```
https://www.youtube.com/watch?v=VIDEO_ID
https://youtu.be/VIDEO_ID
https://www.youtube.com/embed/VIDEO_ID
```

### Códigos de Video

- **1-10:** Módulo 1
- **11-20:** Módulo 2
- **21-30:** Módulo 3
- **31-40:** Módulo 4
- **41-50:** Módulo 5
- **51-60:** Módulo 6
- **61-70:** Módulo 7
- **71-80:** Módulo 8
- **81-90:** Módulo 9
- **91-120:** Módulo 10
- **121-150:** Módulo 11
- **151-165:** Módulo 12

## 💾 Almacenamiento de Datos

Los datos se guardan en **localStorage** del navegador:

- ✅ **Ventaja:** Funciona sin servidor ni base de datos
- ⚠️ **Importante:** Los datos son por navegador/dispositivo
- 💡 **Recomendación:** Exporta backups periódicamente

## 📱 Compatibilidad

- ✅ Chrome, Firefox, Safari, Edge (últimas versiones)
- ✅ Dispositivos móviles iOS y Android
- ✅ Tablets y computadoras de escritorio
- ⚠️ Requiere JavaScript habilitado

## 🔄 Actualizar el Portal

Para actualizar contenido:

1. Edita el archivo `index.html` localmente
2. Súbelo nuevamente a GitHub (reemplaza el anterior)
3. O usa Git:
```bash
git add index.html
git commit -m "Actualización del portal"
git push
```

GitHub Pages se actualizará automáticamente en 1-2 minutos.

## 🛠️ Personalización

### Cambiar Colores

Busca en `index.html` la sección `<style>` y modifica:

```css
/* Colores principales */
--primary-color: #ff6b6b;
--secondary-color: #4ecdc4;
--accent-color: #00d4ff;
```

### Cambiar Logo

Reemplaza la URL del logo en la línea del `<img>` dentro de `.company-logo`

### Modificar Módulos

Edita los módulos en la sección de JavaScript donde dice `moduleData`

## ❓ Solución de Problemas

### El sitio no carga
- Verifica que GitHub Pages esté activado
- Revisa que el archivo se llame `index.html`
- Espera 1-2 minutos después de subir cambios

### Los videos no se reproducen
- Verifica que las URLs de YouTube sean correctas
- Asegúrate de que los videos no estén privados
- Algunos videos tienen restricciones de embebido

### Olvidé mi contraseña de admin
- Presiona el botón **"¿Olvidaste tu contraseña?"**
- O borra el localStorage desde la consola del navegador:
```javascript
localStorage.removeItem('sap_admin_password');
```

## 📞 Soporte

Para dudas o problemas:
- Crea un **Issue** en este repositorio
- O contacta al administrador del curso

## 📄 Licencia

Este proyecto es de uso interno para capacitación.

---

**Desarrollado para el curso de capacitación SAP HANA** 🎓

¡Disfruta aprendiendo! 🚀
