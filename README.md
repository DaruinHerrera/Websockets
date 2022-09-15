# Imagenes utilizadas
```
Web: Flask
```
```
Crossbar: crossbario/crossbar
```
## Instalar dependencias local - opcional
```
pip install -r requirements.txt
```

# Construir
```
docker-compose build
```

# Construir desde cero - opcional
```
docker-compose build --no-cache
```

# Cargar
```
docker-compose up
```

# Se crean dos contenedotes
# Ingresamos al que contiene el servicio web
```
docker exec -ti nombreContenedor bash
```

## Ejecutar dentro del contenedor
```
python client_component_publish.py 
```

# Ejecutar desde la consola sin ingresar al contenedor - opcional
```
docker exec -ti contenedor python client_component_publish.py
```

# Valide la consola del navegador para el servicio web en el puerto 5000
# Creditos
```
http://fcarrizalest.com/creando-app-en-tiempo-real-con-python-vuejs
```
