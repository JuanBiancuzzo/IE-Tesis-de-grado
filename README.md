# Tesis de Grado - Ingeniería Electrónica
Creando un sistema de redundancia para robots móviles autónomos

Se incluye en este ropositorio los informes necesarios para esta tesis
 * [Plan de Trabajo](https://github.com/JuanBiancuzzo/IE-Tesis-de-grado/releases/download/informe/Plan.de.Trabajo.-.Tesis.de.Grado.de.Ingenieria.Electronica.-.Juan.Ignacio.Biancuzzo.pdf)
 * [Informe final](https://github.com/JuanBiancuzzo/IE-Tesis-de-grado/releases/download/informe/Informe.final.-.Tesis.de.Grado.de.Ingenieria.Electronica.-.Juan.Ignacio.Biancuzzo.pdf)

## Crearlos localmente
Utilizando este repositorio se puede ejecutar, por medio de docker, los informes con la siguiente linea
```bash
docker run --mount type=bind,source=./[carpeta],target=/latex juanbiancuzzo/latex:latest 1>/dev/null
```

Donde se tiene que cambiar el nombre de la carpeta que indique que informe crear
