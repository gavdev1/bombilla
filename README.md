# 💡 Proyecto: Interruptor de Bombilla (Light Toggle)

Este proyecto simula el funcionamiento de un interruptor eléctrico. Al activar el switch, no solo cambia el color de la página, sino que visualmente "encendemos" una bombilla mediante clases de CSS dinámicas.

## 📸 Representación Visual

## 🧠 Lógica del Proyecto

El corazón del proyecto es un pequeño script de JavaScript que actúa como el cableado eléctrico entre el interruptor físico y la bombilla.

### El "Cableado" (JavaScript)

```javascript
// Seleccionamos el interruptor del DOM
const toggleSwitch = document.querySelector('#toggleSwitch');

// Creamos la conexión: cuando el usuario hace "clic", la luz reacciona
toggleSwitch.addEventListener('change', () => {
    // La clase 'light-on' aplica el brillo y el color
    document.body.classList.toggle('light-on');
});

```

---

## 🛠️ Cómo instalarlo

1. Clona este repositorio.
2. Abre el archivo `index.html` en tu navegador.
3. ¡Haz clic en el switch y observa cómo se hace la luz!

---

