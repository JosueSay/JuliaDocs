# ⚙️ Configuración de Julia en Windows

## 📥 Descarga e instalación

1. Descarga Julia desde el [sitio oficial](https://julialang.org/downloads/), seleccionando el instalador correspondiente para Windows.
2. Ejecuta el archivo `.exe` descargado y sigue las instrucciones del instalador.
3. **Opcional pero recomendado**: marca la casilla que permite agregar Julia al **PATH del sistema**.

Una vez instalada, podrás abrir la interfaz de Julia (REPL) desde el menú de inicio o ejecutar Julia desde la **PowerShell** usando:

```powershell
julia --version
```

Este comando mostrará la versión instalada de Julia.

## 🧪 Uso de Julia como kernel en Jupyter

Para utilizar Julia como kernel en notebooks de Jupyter, debes instalar el paquete `IJulia`. Esto se hace desde la terminal interactiva de Julia (REPL):

1. Abre Julia.

2. Presiona la tecla `]` para ingresar al modo de paquetes. Verás un prompt como:

   ```bash
   (@v1.11) pkg>
   ```

3. Escribe el siguiente comando para instalar el paquete necesario:

   ```bash
   add IJulia
   ```

Esto instalará y configurará Julia como kernel de Jupyter automáticamente.

## 🧠 Uso en Visual Studio Code (VS Code)

1. Instala la **extensión oficial de Julia** desde la tienda de extensiones de VS Code.
2. Crea o abre un archivo `.ipynb`.
3. Haz clic en la opción `Kernel > Seleccionar Kernel` y elige el kernel de Julia (aparecerá como `Julia x.x.x` si `IJulia` está correctamente instalado).
