# Guía de Instalación de Python y Visual Studio Code

## Introducción

Esta guía te ayudará a instalar Python y Visual Studio Code (VS Code) en tu computadora. Python es un lenguaje de programación poderoso y fácil de aprender, y VS Code es un editor de código fuente muy popular que ofrece una amplia gama de herramientas y extensiones para desarrolladores.

## Requisitos Previos

- Una computadora con acceso a internet.
- Permisos de administrador para instalar software.

## Instalación de Python

### Paso 1: Descargar el Instalador de Python

1. Abre tu navegador web y ve al sitio web oficial de Python: [python.org](https://www.python.org/)
2. Haz clic en el botón "Download" en la página principal.
3. Selecciona la versión más reciente de Python compatible con tu sistema operativo (Windows, macOS, Linux).

### Paso 2: Ejecutar el Instalador

1. Abre el archivo de instalación que descargaste.
2. **Importante:** Marca la casilla que dice "Add Python to PATH" antes de continuar.
3. Selecciona "Install Now" para una instalación rápida y sencilla.

### Paso 3: Verificar la Instalación

1. Abre una terminal (Command Prompt en Windows, Terminal en macOS y Linux).
2. Escribe `python --version` y presiona Enter. Deberías ver la versión de Python que instalaste.
3. Escribe `pip --version` para verificar que el gestor de paquetes de Python también se ha instalado correctamente.

## Instalación de Visual Studio Code

### Paso 1: Descargar el Instalador de Visual Studio Code

1. Ve al sitio web oficial de Visual Studio Code: [code.visualstudio.com](https://code.visualstudio.com/)
2. Haz clic en el botón "Download" en la página principal.
3. Selecciona la versión adecuada para tu sistema operativo.

### Paso 2: Ejecutar el Instalador

1. Abre el archivo de instalación que descargaste.
2. Sigue las instrucciones del asistente de instalación. Puedes dejar las opciones predeterminadas a menos que necesites configuraciones específicas.
3. Una vez completada la instalación, abre VS Code.

## Configuración de Visual Studio Code para Python

### Paso 1: Instalar la Extensión de Python

1. Abre Visual Studio Code.
2. Ve a la pestaña de Extensiones (ícono de cuadrados en la barra lateral izquierda) o presiona `Ctrl+Shift+X`.
3. Busca "Python" en la barra de búsqueda.
4. Instala la extensión desarrollada por Microsoft.

### Paso 2: Configurar el Entorno de Python

1. Abre un archivo o proyecto de Python en VS Code.
2. Si es la primera vez que abres un archivo `.py`, VS Code te pedirá que selecciones un intérprete de Python. Elige la versión de Python que instalaste.
3. Si no ves esta opción, puedes seleccionarla manualmente haciendo clic en el ícono de Python en la esquina inferior izquierda de la ventana de VS Code y seleccionando el intérprete correcto.

## Verificación Final

1. Crea un nuevo archivo con la extensión `.py` en VS Code.
2. Escribe el siguiente código de ejemplo:

   ```python
   print("¡Hola, mundo!")
   ```

3. Guarda el archivo y presiona `F5` para ejecutar el código.
4. Deberías ver el mensaje "¡Hola, mundo!" en la terminal integrada de VS Code.
