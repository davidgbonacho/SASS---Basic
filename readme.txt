sass es un sistema para escribir estilos css .scss (que no es interpretado por un navegador, ya que éste interpreta .css)
por lo que se trata de un código preprocesado que hay que compilar (a .css) para que se pueda ver en un navegador

# instalar sass a nivel general
npm install -g sass

# para compilar .scss a .css
sass css/estilos.scss css/estilos.css

# para que cualquier cambio en el .scss se autocompile al guardarlo se incluye --watch
sass --watch css/estilos.scss css/estilos.css

# (--watch estará abierto durante la sesión hasta incluir CTRL-C para detenerlo)




# AHORA, con VSC es posible utilizar sass (sin instalarlo) y compilar directamente los ficheros .scss sin tener que usar --watch
# con la extensión: Live Sass Compiler (para que funcione es necesario tener también la extensión Live Server)