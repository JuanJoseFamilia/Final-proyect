# Proyecto de CI/CD - Web Application

Este es un proyecto de práctica para implementar un pipeline de CI/CD utilizando **GitHub Actions** para una aplicación web simple. El pipeline automatiza las pruebas y el despliegue a **GitHub Pages**.

## Objetivos

- Implementar un pipeline CI/CD básico para automatizar el proceso de pruebas e integración.
- Realizar el despliegue de una aplicación web en **GitHub Pages** utilizando GitHub Actions.
- Configurar pruebas unitarias e integración para verificar la calidad del código.

## Requisitos

- **Node.js** (instalado localmente)
- **Git** y una cuenta en **GitHub**
- Editor de código como **VSCode**
- Conocimientos básicos de JavaScript y Git

## Estructura del Proyecto

-La estructura de los archivos de este proyecto es la siguiente:
-practica-final/ ├── .github/ │ └── workflows/ │ └── ci-cd.yml # Configuración del pipeline CI/CD ├── coverage/ # Reportes de cobertura de -pruebas ├── dist/ # Archivos generados para despliegue ├── node_modules/ # Dependencias del proyecto ├── public/ │ └── index.html # -Página principal del Frontend ├── src/ │ ├── app.js # Backend en Node.js/Express │ └── sum.js # Función de ejemplo para pruebas unitarias -├── test/ │ ├── app.test.js # Pruebas del servidor Express │ └── sum.test.js # Pruebas unitarias ├── .gitignore # Archivos y carpetas -ignoradas por Git ├── package.json # Dependencias y scripts del proyecto ├── package-lock.json # Archivo de lock de npm └── README.md # -Documentación del proyecto

## Instalación

Para ejecutar este proyecto en tu entorno local, sigue los siguientes pasos:

1. **Clona el repositorio** en tu máquina:

   git clone https://github.com/JuanJoseFamilia/Final-proyect.git
   
