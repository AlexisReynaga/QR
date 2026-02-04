# Generador de QR

Un generador de códigos QR interactivo y fácil de usar, desarrollado con HTML, CSS y JavaScript.

## 📋 Descripción

Esta aplicación web permite generar códigos QR a partir de texto o URLs. Ofrece opciones de personalización como diferentes tamaños y la capacidad de descargar el código QR generado en formato de imagen.

## ✨ Características

- **Generación instantánea**: Crea códigos QR en tiempo real mientras escribes
- **Múltiples tamaños**: Selecciona entre 128px, 192px, 256px y 320px
- **Descarga de imagen**: Guarda el código QR como archivo PNG
- **Interfaz responsiva**: Compatible con dispositivos móviles y de escritorio
- **Diseño moderno**: Interfaz limpia con Tailwind CSS

## 🚀 Inicio Rápido

1. **Clona o descarga el proyecto**
   ```bash
   git clone <repo-url>
   cd QR
   ```

2. **Abre el archivo**
   - Abre directamente `index.html` en tu navegador
   - O usa un servidor local:
   ```bash
   # Con Python 3
   python -m http.server 8000
   
   # Con Node.js
   npx serve
   ```

3. **Usa la aplicación**
   - Escribe un texto o URL en el campo de entrada
   - Selecciona el tamaño deseado
   - El código QR se generará automáticamente
   - Descárgalo si lo necesitas

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de la aplicación
- **Tailwind CSS**: Estilos y diseño responsivo (CDN)
- **JavaScript**: Lógica interactiva
- **QR Code JS**: Librería para generar códigos QR (CDN)

## 📦 Dependencias Externas

- [Tailwind CSS Browser](https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4)
- [QR Code JS](https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js)

## 📸 Funcionalidades

### Entrada de Texto
- Campo de entrada para URLs o texto
- Generación en tiempo real

### Selección de Tamaño
- 128px - Pequeño
- 192px - Mediano
- 256px - Grande
- 320px - Extragrande

### Descarga
- Botón para descargar el código QR como imagen PNG

## 💡 Casos de Uso

- Crear códigos QR para URLs de tu sitio web
- Compartir información de contacto
- Generar códigos para eventos o promociones
- Uso en materiales de marketing digital

## 📝 Estructura del Proyecto

```
QR/
├── index.html      # Archivo principal
└── README.md       # Este archivo
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si encuentras un error o tienes una mejora, siéntete libre de:

1. Reportar problemas
2. Sugerir mejoras
3. Enviar pull requests

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👤 Autor

**Alexis Reynaga** - [GitHub](https://github.com/alexisreynaga)

---

¿Preguntas? ¡No dudes en contactarme!
