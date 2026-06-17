# Parcial 2 - Software

**Nombre:** Sofia Contini
**Fecha:** 17 de junio de 2026

**Descripción breve del proyecto:**
Proyecto integrador para el Parcial 2 de la materia. Consiste en el despliegue de una página web estática simple utilizando Docker con Nginx, versionado mediante un flujo de trabajo profesional con Git y GitHub.


### Clonar el repositorio
```bash
git clone https://github.com/Sofia98C/parcial2-software.git
cd parcial2-software
```

### Construir la imagen Docker

```bash
docker build -t parcial2-software .
```
### Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name mi-parcial parcial2-software
```
### Ver la aplicación
- Abre tu navegador y accede a: http://localhost:8080