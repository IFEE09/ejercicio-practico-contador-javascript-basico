# 🧮 Ejercicio: Contador Interactivo con Colores

## 📋 Descripción

Crea una página web interactiva que implemente un contador dinámico con cambios de color según el valor actual.

## 🎯 Objetivos de Aprendizaje

- Manipulación del DOM con JavaScript
- Manejo de eventos (click)
- Aplicación dinámica de estilos CSS
- Estructura básica HTML
- Lógica condicional en JavaScript

## 📝 Requisitos

### HTML
Crear una página que contenga:

- [x] Un título principal: **"Mi Contador"**
- [x] Un elemento para mostrar el número (iniciar en **0**)
- [x] Tres botones interactivos:
  - `Aumentar` ➕
  - `Disminuir` ➖
  - `Reiniciar` 🔄

### CSS
Implementar los siguientes estilos:

- [x] **Página centrada** con buen espaciado
- [x] **Fuente grande** para el número del contador
- [x] **Botones atractivos** con efectos hover
- [x] **Colores dinámicos** para el contador:
  - 🟢 **Verde** → Números positivos
  - 🔴 **Rojo** → Números negativos
  - ⚫ **Negro** → Valor cero

### JavaScript
Programar la siguiente funcionalidad:

- [x] **Botón "Aumentar"**: Suma +1 al contador
- [x] **Botón "Disminuir"**: Resta -1 al contador  
- [x] **Botón "Reiniciar"**: Vuelve el contador a 0
- [x] **Cambio automático de colores** según el valor actual

## 🏗️ Estructura Sugerida

```
proyecto/
│
├── index.html
├── styles.css
└── script.js
```

## 💡 Consejos

> **Tip 1**: Usa `document.querySelector()` para seleccionar elementos del DOM
> 
> **Tip 2**: Los `addEventListener()` te ayudarán con los eventos de click
> 
> **Tip 3**: Cambia las clases CSS con `classList.add()` y `classList.remove()`

## 🎨 Bonus (Opcional)

- Añadir animaciones CSS en las transiciones de color
- Implementar un límite máximo y mínimo para el contador
- Agregar sonidos en cada click
- Crear un historial de los últimos valores

## 🚀 ¿Listo para el desafío?

¡Manos a la obra! Este ejercicio te ayudará a dominar los fundamentos de la interactividad web.

---

**¡Feliz codificación!** 🎉