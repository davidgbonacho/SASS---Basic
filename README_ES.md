## SASS
# ¿Qué es sass?
sass es un sistema para escribir estilos css .scss (que no es interpretado por un navegador, ya que éste interpreta .css)
por lo que se trata de un código preprocesado que hay que compilar (a .css) para que se pueda ver en un navegador

# instalar sass a nivel general
```
npm install -g sass
```

# para compilar .scss a .css una vez
se puede realizar una compilación concreta de .scss a .css. 
```
sass css/estilos.scss css/estilos.css
```

# abrir watch para compilar cualquier cambio
También es posible abrir un procedimiento para que, constantemente, se compile lo que vaya realizándose en .scss a .css
para que cualquier cambio en el .scss se autocompile al guardarlo se incluye --watch
```
sass --watch css/estilos.scss css/estilos.css
```
`--watch estará abierto durante la sesión hasta incluir CTRL-C para detenerlo`

# Usar sass con VSC
con VSC es posible utilizar sass (sin instalarlo) y compilar directamente los ficheros .scss sin tener que usar --watch
`con la extensión: Live Sass Compiler (para que funcione es necesario tener también la extensión Live Server)`

[Text in Englisth here](README.MD)

---
`título:` sass \  [`SimPIL`] 27/03/26\
`autor:` David G. Bonacho &nbsp;&nbsp;  [www.tizedit.com](https://www.tizedit.com)