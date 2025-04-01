### Cómo ejecutar el proyecto:

Clona el repositorio y ábrelo en la interfaz de la línea de comandos: 

```
git clone https://github.com/nebius-academy-templates/python_kittygram2plus_es.git
```

```
cd python_kittygram2plus_es
```

Crea y activa un entorno virtual:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Instala las dependencias del archivo requirements.txt

```
pip install -r requirements.txt
```

Ejecuta las migraciones:

```
python3 manage.py migrate
```

Ejecuta el proyecto:

```
python3 manage.py runserver
```
