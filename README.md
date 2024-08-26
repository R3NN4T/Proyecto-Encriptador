# Encriptador de Texto /Descripcion

Este proyecto es una aplicación web simple que permite encriptar y desencriptar textos basados en ciertas reglas de sustitución de caracteres. Es ideal para aprender conceptos básicos de JavaScript, HTML y CSS, y cómo interactúan entre sí para construir una interfaz de usuario responsiva.

## Características

- **Encriptación:** Convierte las vocales en el texto ingresado a cadenas específicas.
  - La letra "e" se convierte en "enter"
  - La letra "i" se convierte en "imes"
  - La letra "a" se convierte en "ai"
  - La letra "o" se convierte en "ober"
  - La letra "u" se convierte en "ufat"
  
- **Desencriptación:** Revertir el proceso de encriptación para obtener el texto original.

- **Responsividad:** La interfaz se adapta tanto a pantallas de escritorio como a dispositivos móviles. En la vista móvil, se oculta la imagen del resultado y el texto se ajusta para ser completamente visible.

- **Validaciones:** 
  - El usuario no puede ingresar texto vacío.
  - No se permiten mayúsculas ni caracteres acentuados.

- **Copiar al Portapapeles:** El texto encriptado o desencriptado puede copiarse al portapapeles con un solo clic.

## Tecnologías Utilizadas

- **HTML:** Estructura básica del proyecto.
- **CSS:** Estilización y diseño responsivo.
- **JavaScript:** Lógica para encriptar, desencriptar y gestionar la interfaz de usuario.

## Estructura del Proyecto

&nbsp;&nbsp;&nbsp;&nbsp;Proyecto Encriptador/   
&nbsp;&nbsp;&nbsp;&nbsp;│  
&nbsp;&nbsp;&nbsp;&nbsp;├── index.html : Estructura principal de la aplicación   
&nbsp;&nbsp;&nbsp;&nbsp;├── styles.css : Estilos para la interfaz  
&nbsp;&nbsp;&nbsp;&nbsp;├── script.js  : Lógica de encriptación, desencriptación y manejo de eventos   
&nbsp;&nbsp;&nbsp;&nbsp;└── /img  : Carpeta con imagenes que se usan en la aplicacion.  
&nbsp;&nbsp;&nbsp;&nbsp;└── README.md  : Información del proyecto  


## Cómo Usar

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/R3NN4T/Proyecto-Encriptador.git
2. **Abrir el proyecto:**

Navega al directorio del proyecto y abre el archivo index.html en tu navegador preferido.

3. **Interacción:**

- Ingresa un texto en el área de entrada.
- Haz clic en "Encriptar" para ver el texto encriptado en el área de resultado.
- Haz clic en "Desencriptar" para revertir el proceso.
- Usa el botón "Copiar" para copiar el resultado al portapapeles.
- Si borras el texto en el área de entrada, la imagen y el texto inicial volverán a mostrarse.
