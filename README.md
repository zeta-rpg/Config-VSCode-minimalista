# Configuración Minimalista de VSCode

Este repositorio contiene mi configuración personal de Visual Studio Code, enfocada en un **entorno minimalista y oscuro**, con navegación fluida y cursor estilo bloque. Ideal para desarrolladores que buscan un editor limpio y enfocado.

---

## 📂 Estructura

- `settings.json` → Archivo principal con la configuración completa de VSCode.

---

## 🎨 Tema y apariencia

- **Tema de color:** One Dark Pro Night Flat  
- **Iconos:** Material Icon Theme  
- **Barras y elementos visibles:**  
  - Barra de actividad y barra de estado ocultas (`hidden`)  
  - Minimapa desactivado  
  - Breadcrumbs desactivados  

---

## ⌨ Editor

- **Cursor:** bloque (`block`), parpadeo sólido (`solid`) y color blanco translúcido  
- **Animación:** caret suave activada  
- **Número de líneas:** relativo (`relative`)  
- **Sangría y guías:** guías de corchetes activas, guías de indentación opcionales con `Indenticator`  
- **Scroll:** vertical oculto, no permite scroll más allá de la última línea  
- **Edición vinculada:** activada (`linkedEditing`)  

---

## 🖥 Terminal

- Terminal integrado con **Git Bash** por defecto  
- Cursor en bloque con parpadeo  
- Comandos especiales (`code`) ignorados en terminal  

---

## 🧩 Extensiones compatibles (opcional)

- [Indenticator](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.indenticator) → para visualización de indentación  
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) → recarga en vivo para desarrollo web  
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)  
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)  

> Nota: Esta configuración funciona perfectamente **sin integración de Neovim**.

---

## ⚡ Tips de uso

- Combina **cursor estilo bloque** con `editor.lineNumbers: relative` para navegación rápida.  
- Atajos nativos de VSCode (`Ctrl+W`, `Ctrl+Tab`, `Shift+Flechas`, etc.) permiten simular flujo estilo Vim.  
- Mantén la barra lateral izquierda para exploración de archivos rápida.  

---

## 📌 Cómo usar

1. Copia el contenido de `settings.json` en tu carpeta de configuración de VSCode:  

- **Windows:** `%APPDATA%\Code\User\settings.json`  
- **Linux:** `$HOME/.config/Code/User/settings.json`  
- **Mac:** `$HOME/Library/Application Support/Code/User/settings.json`  

2. Instala las extensiones opcionales si deseas funcionalidades extras como `Indenticator` o `Live Server`.  

---

Con esta configuración tendrás un **VSCode minimalista, oscuro y enfocado en productividad**, listo para trabajar en proyectos de cualquier lenguaje.


