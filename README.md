# BlazorApp GlobalAzure Demo

Una aplicación web Blazor Server desarrollada como demostración para el evento Global Azure, que proporciona acceso fácil a las transmisiones en vivo de las sesiones del evento.

## 📋 Descripción

Esta aplicación Blazor permite a los usuarios acceder rápidamente a las transmisiones de YouTube de Global Azure. La aplicación presenta una interfaz limpia y moderna que muestra los enlaces a las sesiones de ambos días del evento, facilitando el acceso a todo el contenido educativo.

## 🛠️ Requisitos Previos

Para ejecutar este proyecto necesitas tener instalado:

- **.NET 8.0 SDK** o superior
  - Puedes descargarlo desde [https://dotnet.microsoft.com/download](https://dotnet.microsoft.com/download)
- **Un navegador web moderno** (Chrome, Firefox, Edge, Safari)
- **Git** (para clonar el repositorio)

## 🚀 Instalación y Uso

### Clonar el repositorio

```bash
git clone https://github.com/ppiova/BlazorApp-GlobalAzure-Demo.git
cd BlazorApp-GlobalAzure-Demo
```

### Restaurar dependencias y compilar

```bash
dotnet restore
dotnet build
```

### Ejecutar la aplicación

```bash
cd BlazorApp-GlobalAzure-Demo
dotnet run
```

La aplicación estará disponible en:
- **HTTPS**: `https://localhost:5001`
- **HTTP**: `http://localhost:5000`

### Modo de desarrollo

Para ejecutar en modo de desarrollo con recarga automática:

```bash
dotnet watch run
```

## 🌟 Características

- **Interfaz moderna**: Diseño responsive usando Bootstrap
- **Enlaces directos**: Acceso rápido a las transmisiones de YouTube
- **Navegación intuitiva**: Organización clara por días del evento
- **Blazor Server**: Tecnología moderna de Microsoft para aplicaciones web interactivas

## 📺 Contenido del Evento

La aplicación proporciona acceso a:

- **Día 1 (Viernes)**: Sesiones del primer día de Global Azure
- **Día 2 (Sábado)**: Sesiones del segundo día de Global Azure

Cada día incluye enlaces directos a las transmisiones en vivo de YouTube.

## 🏗️ Estructura del Proyecto

```
BlazorApp-GlobalAzure-Demo/
├── Components/
│   ├── Layout/           # Componentes de diseño
│   ├── Pages/            # Páginas de la aplicación
│   └── _Imports.razor    # Imports globales
├── wwwroot/              # Archivos estáticos
├── Program.cs            # Punto de entrada de la aplicación
└── appsettings.json      # Configuración
```

## 🤝 Contribución

Las contribuciones son bienvenidas. Para contribuir:

1. **Fork** el repositorio
2. Crea una **rama feature** (`git checkout -b feature/NuevaCaracteristica`)
3. **Commit** tus cambios (`git commit -am 'Agregar nueva característica'`)
4. **Push** a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un **Pull Request**

### Guías de contribución

- Sigue las convenciones de código existentes
- Asegúrate de que el código compile sin errores
- Incluye comentarios cuando sea necesario
- Mantén los commits pequeños y descriptivos

## 📝 Licencia

Este proyecto está licenciado bajo la **Licencia MIT**. Ver el archivo [LICENSE.txt](LICENSE.txt) para más detalles.

## 👥 Créditos

Desarrollado como demostración para el evento **Global Azure**.

## 🔗 Enlaces Útiles

- [Global Azure](https://globalazure.net/) - Sitio oficial del evento
- [Microsoft Blazor](https://blazor.net/) - Documentación oficial de Blazor
- [.NET Documentation](https://docs.microsoft.com/dotnet/) - Documentación de .NET
- [Bootstrap](https://getbootstrap.com/) - Framework CSS utilizado
- [Azure Documentation](https://docs.microsoft.com/azure/) - Documentación de Microsoft Azure

## 🐛 Reporte de Problemas

Si encuentras algún problema o tienes una sugerencia, por favor:

1. Verifica que no exista ya un issue similar
2. Crea un nuevo issue con:
   - Descripción clara del problema
   - Pasos para reproducir (si aplica)
   - Información del entorno (OS, versión de .NET, navegador)

## 📊 Estado del Proyecto

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![.NET Version](https://img.shields.io/badge/.NET-8.0-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE.txt)

---

⭐ Si este proyecto te resultó útil, ¡no olvides darle una estrella!