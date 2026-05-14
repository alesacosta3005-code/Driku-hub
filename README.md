# 🎮 morreira Script Generator

Una aplicación web moderna para generar scripts con interfaz intuitiva y diseño oscuro elegante.

## 📋 Características

- ✨ **Interfaz moderna** - Diseño limpio con tema oscuro
- 🔍 **Búsqueda de Roblox** - Busca usuarios de Roblox fácilmente
- 🧠 **Gestión de Brainrots** - Selecciona y filtra opciones
- 📋 **Copiar código** - Copia el código HTML generado
- 📱 **Responsive** - Adaptado para dispositivos móviles
- ⚡ **Rápido y ligero** - Sin dependencias externas

## 🚀 Cómo usar

1. **Clona el repositorio**
   ```bash
   git clone https://github.com/alesacosta3005-code/Driku-hub.git
   cd Driku-hub
   ```

2. **Abre en tu navegador**
   - Simplemente abre `index.html` en tu navegador favorito
   - O usa un servidor local:
   ```bash
   python -m http.server 8000
   # O con Node.js
   npx http-server
   ```

3. **Accede a la aplicación**
   ```
   http://localhost:8000
   ```

## 📁 Estructura del proyecto

```
Driku-hub/
├── index.html          # Archivo HTML principal
├── styles.css          # Estilos CSS
├── script.js           # Lógica JavaScript
└── README.md           # Este archivo
```

## 🎨 Personalización

### Colores
Edita las variables CSS en `styles.css`:

```css
:root {
    --bg-black: #000000;
    --accent-orange: #FFA500;
    --accent-purple: #6B38FB;
    /* ... más variables ... */
}
```

### Brainrots
Modifica la lista en `script.js`:

```javascript
const brainrots = [
    "Tu brainrot 1",
    "Tu brainrot 2",
    // ...
];
```

## 🔧 Funcionalidades

### Búsqueda de usuario
Ingresa un nombre de usuario de Roblox para generar scripts personalizados.

### Filtrado de Brainrots
- Busca brainrots por nombre
- Filtra por categoría (OG, SECRET)
- Selecciona los que necesites

### Generación de Script
- Haz clic en "GENERATE SCRIPT"
- El script se genera según los parámetros seleccionados

### Copiar Código
- En la sección "DEVELOPER TOOLS"
- Haz clic en "Copiar todo el código HTML"
- El código se copia automáticamente al portapapeles

## 📱 Navegación

- **Inject** - Panel principal
- **Rankings** - Ver rankings
- **Activity** - Actividad reciente
- **Info** - Información

## 🤝 Contribuir

¿Quieres mejorar este proyecto? 

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la licencia MIT. Ver `LICENSE` para más detalles.

## 👤 Autor

**alesacosta3005-code**
- GitHub: [@alesacosta3005-code](https://github.com/alesacosta3005-code)

## 🎯 Roadmap

- [ ] Autenticación de usuarios
- [ ] Base de datos en la nube
- [ ] Historial de scripts generados
- [ ] Compartir scripts con otros usuarios
- [ ] Más opciones de personalización
- [ ] Versión en inglés

---

**SAB SCRIPTS • FROST HUB 2026**
