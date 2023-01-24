# neero_backend_prueba
En este repositorio se encuentra el archivo empleado para la prueba de Neero, al cargo de backend developer.


conda deactivate

python3 -m venv venv

source venv/bin/activate

pip install fastapi

pip install "uvicorn[standard]"

pip install tortoise-orm

uvicorn main.py --reload

pip install "passlib[bcrypt]"

pip install fastapi-mail

touch .gitignore

pip install python-dotenv

pip install pyjwt

pip install certifi

pip install python-multipart

python3 -m pip install --upgrade Pillow

pip install aiofiles

pip freeze > requirements.txt
