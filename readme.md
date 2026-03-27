## SASS

# What is SASS?
SASS is a system for writing CSS styles using .scss (which is not interpreted by a browser, since browsers interpret .css).  
Therefore, it is preprocessed code that must be compiled (to .css) so it can be displayed in a browser.

# Install SASS globally
```
npm install -g sass
```

# Compile .scss to .css once
You can perform a one-time compilation from .scss to .css.
```
sass css/estilos.scss css/estilos.css
```

# Start watch mode to compile changes automatically
It is also possible to start a process that continuously compiles .scss into .css,  
so any change in the .scss file is automatically compiled when saved by using --watch:

```
sass --watch css/estilos.scss css/estilos.css
```
`--watch will remain active during the session until you press CTRL-C to stop it`

# Using SASS with VSC
With VSC, it is possible to use SASS (without installing it globally) and compile .scss files directly without using --watch.  
`with the extension: Live Sass Compiler (requires the Live Server extension to work)`

[Text in English here](README.MD)

---

`title:` sass   [`SimPIL`] 03/27/26\
`author:` David G. Bonacho &nbsp;&nbsp; [www.tizedit.com](https://www.tizedit.com)