![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Language](https://img.shields.io/badge/Language-JSON-orange)

# rodalytics-ux-kit

Un sistema de diseño y herramientas funcionales para analistas de datos, diseñado bajo una lógica de ingeniería de interfaces y storytelling de alto impacto.

## 🚀 Filosofía
`rodalytics-ux-kit` nace para resolver la brecha entre la extracción de datos y la visualización final. Este repositorio no solo ofrece recursos estéticos, sino un **framework jerárquico** para construir dashboards que sean intuitivos, modernos y profesionalmente consistentes.

## 🎨 Design System: Sistema de Color
Cada paleta en este kit ha sido curada siguiendo una lógica funcional de 5 niveles, asegurando coherencia visual en cualquier plataforma (Tableau, Power BI, R Shiny, Python):

- **[Base]**: Banners, navegación y encabezados de alto impacto.
- **[Fondo]**: Limpieza visual y áreas de separación.
- **[Acento]**: Links, interacciones y KPIs clave.
- **[Borde]**: Líneas sutiles y detalles graduales.
- **[Relleno]**: Estados inactivos o selección en gráficos.

*La primera version incluye 16 paletas temáticas inspiradas en la identidad, geografía y cultura chilena.*
*El reporsitorio sera actualizado con nuevas paletas, udf, de manera semanal para generar contenido para su uso.*

## 📂 Estructura del Repositorio
```text

rodalytics_ux_kit/
├── assets/          # Imágenes y recursos visuales
├── data/            # Datasets maestros (Chile, Mundo, Calendarios, etc.)
├── palettes/        # Definiciones en formato .json para integración multiplataforma
├── src/             # Funciones (UDF), scripts de automatización y lógica
├── templates/       # Estructuras base para Dashboards y reportes
├── .gitignore       # Configuración para un repositorio limpio
└── LICENSE          # Licencia MIT
