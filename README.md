# Readme

Notas del curso (nondegree) de vehiculos autonomos de Udacity
Notes for the autonomous car nanodegree from Udacity (**carnd**)

## Instalacion

Instalado siguiendo las instrucciones de: https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md

### 1) Se instala miniconda

https://conda.io/docs/install/quick.html#os-x-miniconda-install

### 2) Se descarga el respositorio para generar el environment de carnd

Primer problema en instalacion:
Al ejecutar 

```
git clone https://github.com/udacity/CarND-Term1-Starter-Kit.git
```

Da el error

```
xcrun: error: invalid active developer path
```

Resuelto con:
https://apple.stackexchange.com/questions/254380/macos-sierra-invalid-active-developer-path

### 3) Se instala el _environment_ modelo de carnd

```
conda env create -f environment.yml 
```

Esto tarda un rato (se bajan muchos paquetes)
