# Para ejecutar app:
1. Crear ambiente virtual: `python3 -m venv .venv`
2. Activar ambiente virtual: `source .venv/bin/activate`
3. Validar en la consola que se tiene activo el ambiente virtual, para desactivar env: `deactivate`
4. Instalar requirements: `python3 -m pip install -r requirements.txt`
5. Colocar la variable de entorno: `export FLASK_APP=market.py` y para hacer cambios sin reiniciar el servicio: `export FLASK_DEBUG=1`
6. Correr aplicación: `flask run`

## Comando utiles Linux:
- Para ver variables de entorno: `printenv | less` y `printenv HOME`
