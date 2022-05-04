# Vulnerable API

Basado en: https://github.com/mattvaldes/vulnerable-api

## Advertencia

No use este código en producción, este código sólo debe ser usado para propósitos educativos.

## Uso

	$ docker build -t vulnerable-api .

	$ docker run -dp 8081:8081 vulnerable-api

	$ curl -v http://localhost:8081/
