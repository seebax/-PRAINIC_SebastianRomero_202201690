# Informe #3: Sistemas Operativos ⚙️
# Manual de Instalación de Ubuntu 24.04 LTS 🐧

Este manual te guiará en la instalación de Ubuntu 24.04 LTS y te proporcionará los comandos básicos para trabajar en la terminal. ¡Vamos a ello! 🚀

---

## 🛠️ Instalación de Ubuntu 24.04 LTS

1. **Descarga la imagen ISO**: 
   - Visita el sitio oficial de [Ubuntu](https://ubuntu.com/download) y descarga la imagen ISO de Ubuntu 24.04 LTS.

2. **Crea un USB booteable**:
   - Usa herramientas como [Rufus](https://rufus.ie/) (Windows)  para crear un USB booteable con la imagen ISO.

3. **Instala Ubuntu**:
   - Conecta el USB a tu computadora y reinicia.
   - Entra en la BIOS/UEFI y selecciona el USB como dispositivo de arranque.
   - Sigue las instrucciones en pantalla para completar la instalación.

---

## 🖥️ Comandos Básicos en la Terminal

### 📂 Navegar entre archivos y directorios
- `cd [ruta]`: Cambia al directorio especificado.
    ```bash
    cd /ruta/al/directorio
- `cd ..`:  Retrocede un nivel en la estructura de directorios.
    ```bash
    cd ..
- `cd ~ `: Te lleva al directorio home del usuario actual.
    ```bash
    cd ~
### 👀 Ver el contenido de un directorio
- `ls`: Lista los archivos y directorios en la ubicación actual.
    ```bash
    ls
    ````

- `ls -l`: Muestra detalles adicionales (permisos, tamaño, etc.).
    ```bash
    ls -l
    ````
- `ls -a`: Muestra archivos ocultos (los que comienzan con .).
    ```bash
    ls -a
    ````
### 📁 Crear carpetas en un directorio

- `mkdir [nombre_carpeta]`: Crea una nueva carpeta.
    ```bash
    mkdir nueva_carpeta
    ```

### 📂 Copiar archivos y carpetas
- `cp [origen] [destino]`: Copia un archivo o carpeta.
    ```bash
    cp archivo.txt /ruta/al/destino/
    ```

- `cp -r [origen] [destino]`: Copia una carpeta y su contenido (recursivo).
    ```bash
    cp -r carpeta /ruta/al/destino/
    ```


### 🚚 Mover archivos y carpetas
- `mv [origen] [destino]`: Mueve un archivo o carpeta.
    ```bash
    mv archivo.txt /ruta/al/destino/
    ```

### 🗑️ Eliminar archivos y carpetas
- `rm [archivo]`: Elimina un archivo.
    ```bash
    rm archivo.txt
    ```

- `rm -r [carpeta]`: Elimina una carpeta y su contenido (recursivo).
    ```bash
    rm -r carpeta
    ```

### 👑 Ingresar como Superusuario (root)
- `sudo -i`: Inicia una sesión como superusuario.
    ```bash
    sudo -i
    ```

- `sudo [comando]`: Ejecuta un comando con permisos de superusuario.
    ```bash
    sudo apt update
    ```

### 🔒 Actualizar permisos de archivos o directorios
- `chmod [permisos] [archivo]`: Cambia los permisos de un archivo o directorio.
    ```bash
    chmod 755 archivo.txt
    ```

- `chown [usuario]:[grupo] [archivo]`: Cambia el propietario y grupo de un archivo.
    ```bash
    chown usuario:grupo archivo.txt
    ```

### 📝 Crear/editar un archivo de texto
- `nano [archivo]`: Abre el archivo en el editor Nano.
    ```bash
    nano archivo.txt
    ```

- `vim [archivo]`: Abre el archivo en el editor Vim.
    ```bash
    vim archivo.txt
    ```

### 📦 Instalar paquetes desde la terminal
- `sudo apt install [paquete]`: Instala un paquete.
    ```bash
    sudo apt install nombre_paquete
    ```

### 🔄 Actualizar paquetes
- `sudo apt update`: Actualiza la lista de paquetes disponibles.
    ```bash
    sudo apt update
    ```

- `sudo apt upgrade`: Actualiza los paquetes instalados.
    ```bash
    sudo apt upgrade
    ```