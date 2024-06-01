# Spatial Statistics Course

This repository holds the notebooks for spatial statistics course with Python.

## Installing dependencies

The dependencies used in this course are managed via Poetry. All documentation to install and start working with Poetry can be found [here](https://python-poetry.org).

### Install Poetry

#### Windows (Powershell)

1. **Open Windows Powershell**: Navigate to your Start menu, type "Powershell", and select "Windows Powershell" from the search results.

2. **Run installation command**: In the Powershell window, paste the following command and press Enter:
   
    Note: If you've installed Python through the Microsoft Store, replace `py` with `python` in the command below.

    ```bash
    (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
    ```

3. **Copy installation PATH**: Once the installation is complete, it will provide you with a path. Copy this path as you'll need to add it to your user environment variables. It will looking something like `C:\Users\<your-username>\AppData\Roaming\Python\Scripts`:

4. **Add Path to environment variables**:
   - Right-click on the Start button and select "System".
   - In the System window, click on "Advanced system settings" on the left sidebar.
   - In the System Properties window, click on the "Environment Variables..." button.
   - In the Environment Variables window, under "User variables for [<your-username>]", find the "Path" variable and select it.
   - Click on the "Edit..." button.
   - In the Edit Environment Variable window, click on "New" and paste the path you copied from the installation process.
   - Click "OK" on all open windows to save your changes.

5. **Close and reopen Powershell**: Close the Powershell window and open a new one.

6. **Verify installation**: In the new Powershell window, type `poetry --version` and press Enter. If Poetry has been successfully installed, you should see its version number printed in the terminal.

#### Install course dependencies

Once you have installed Poetry, you can install all required dependencies for the course into a local environment by running:

```bash
poetry install
```

## Running the notebooks

To run the notebooks using [JupyterLab](https://docs.jupyter.org/en/latest/), just run:

```bash
poetry run jupyter-lab classes
```

# Curso de Estadística Espacial

Este repositorio contiene las notebooks para el curso de estadística espacial con Python.

## Instalando las dependencias

Las dependencias utilizadas en este curso son manejadas a través de Poetry. Toda la documentación para instalar y empezar a trabajar con Poetry se puede encontrar en el siguiente [enlace](https://python-poetry.org).

### Instalando Poetry

#### Windows (Powershell)

1. **Abra Windows Powershell**: navegue hasta el menú Inicio, escriba "Powershell" y seleccione "Windows Powershell" en los resultados de la búsqueda.

2. **Ejecutar comando de instalación**: En la ventana de Powershell, pegue el siguiente comando y presione Enter:

    Nota: Si instaló Python a través de Microsoft Store, reemplace `py` con `python` en el siguiente comando.

    ```bash
    (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -
    ```

3. **Copiar la ruta de instalación**: Una vez que se complete la instalación, le proporcionará una ruta. Copie esta ruta, ya que deberá agregarla a las variables de entorno de su usuario. Tendrá un aspecto similar a `C:\Users\<nombre-de-usuario>\AppData\Roaming\Python\Scripts`:

4. **Agregar la ruta a las variables de entorno**:
 - Haga clic derecho en el botón Inicio y seleccione "Sistema".
 - En la ventana Sistema, haga clic en "Configuración avanzada del sistema" en la barra lateral izquierda.
 - En la ventana Propiedades del sistema, haga clic en el botón "Variables de entorno...".
 - En la ventana Variables de entorno, en "Variables de usuario para [<nombre-de-usuario>]", busque la variable "Path" y selecciónela.
 - Haga clic en el botón "Editar...".
 - En la ventana Editar variable de entorno, haga clic en "Nuevo" y pegue la ruta que copió del proceso de instalación.
 - Haga clic en "Aceptar" en todas las ventanas abiertas para guardar los cambios.

5. **Cerrar y volver a abrir Powershell**: cierre la ventana de Powershell y abra una nueva.

6. **Verificar instalación**: En la nueva ventana de Powershell, escriba `poetry --version` y presione Enter. Si Poetry se ha instalado correctamente, debería ver su número de versión impreso en el terminal.

#### Dependecias del curso

Una vez que haya instalado poetry, puede instalar todas las dependencias necesarias para el curso en un entorno local ejecutando:

```bash
poetry install
```

## Corriendo las notebooks

Para correr las notebooks usando [JupyterLab](https://docs.jupyter.org/en/latest/), sólo se debe correr:

```bash
poetry run jupyter-lab classes
```