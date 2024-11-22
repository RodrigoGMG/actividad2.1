# Instalación y Configuración de Jekyll

Jekyll es un generador de sitios web estáticos escrito en Ruby que permite convertir texto plano en páginas web.

---
### Paso 1: Instalación de Prerrequisitos en Debian/Ubuntu
Para comprobar si mi lista de paquetes esta actualizada ejecutamos ese comando:

sudo apt-get update -y

---
### Paso 2: Instalar Ruby
Para instalar ruby tienes que ejecutar ese comando:

sudo apt-get install ruby-full

---
### Paso 3: Verificar la instalación
Para verificar la instalacion y que todod este funcionando correctamente tenemos los siguientes comandos:

ruby -v     # Muestra la versión de Ruby instalada
gem -v      # Muestra la versión de RubyGems
gcc -v      # Muestra la versión de GCC
g++ -v      # Muestra la versión de G++
make -v     # Muestra la versión de Make

---
### Paso 4: Configurar rubygems para el usuario
Para intalar las gemas en un directorio de usuario:

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

---
### Paso 5: Instalar Jekyll y Bundler
Para instalarlos tenemos que utilizar este comando:

gem install jekyll bundler

---
### Paso 6: Crear tu primer trabajo en Jekyll
Para crearlo tienes que realizar los siguientes comandos:

jekyll "nombre del proyecto"
cd "nombre del proyecto"
bundle exec jekyll serve

---




