# {{cookiecutter.project_name}}

Descripción: {{cookiecutter.description}}

## Antes de empezar:
1. Cambiar el nombre del archivo `env.sample` a `.env`

2. Navegar al directorio donde se quiere crear el proyecto. 

3. Levantar el contenedor de Docker.

En la consola escribir:

```
docker compose up (si tenemos docker compose V2)
docker-compose up (si tenemos docker compose V1)
```
ó 
```
make jupyter (ejecuta versión de docker compose V2)
```

4. Instalar el paquete src.

- Abrir jupyter lab, 
- Abrir una consola
- Ejecutar las siguiente línea:

```
pip install -e .
```
ó desde el notebook `00-demo.ipynb`: 

```
pip install -e ..
```

#### Contacto
{{cookiecutter.author_name}} : {{cookiecutter.email}}