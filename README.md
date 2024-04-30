# Trabajo práctico 1​: Codificación y validaciones​

Para la entrega del trabajo práctico van a tener que configurar un repositorio git siguiendo las instrucciones a continuación:

### 1. Crear repositorio en GitHub
### 2. Instalar git
https://git-scm.com/downloads

### 3. Configurar email y nombre de git
De esta manera se sabe quién realizó cambios en el repositorio
```bash
git config --global user.name "John Doe"
git config --global user.email "johndoe@example.com"
```
### 4. Crear repositorio local con git
#### Navegar a la carpeta donde vamos a trabajar
```bash
cd /path/de/la/carpeta
```
#### Inicializar el repositorio adentro de esa carpeta
```bash
#/path/de/la/carpeta
git init
```
#### Crear un archivo README.md dentro de la carpeta
- Simplemente creen un archivo cualquiera dentro de la carpeta con el nombre README y una extensión .md

#### Añadir los cambios al "área de preparación"
```bash
#/path/de/la/carpeta
git add .
```

#### Hacer el primer "commit"
```bash
#/path/de/la/carpeta
git commit -m "Primer commit"
```

### 5. Conectar repositorio local con el repositorio remoto (GitHub)
```bash
git remote add origin https://github.com/tu-usuario/tu-repositorio.git
```


Nota: pueden hacer uso del lenguaje de marcado "markdown" para darle estilos al documento README.md, GitHub soporta esto de forma nativa:
https://github.com/im-luka/markdown-cheatsheet
