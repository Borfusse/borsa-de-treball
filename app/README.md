# Contenidor Dinàmic de la Borsa de treball

En aquesta carpeta disposeu de la versió dinàmica amb PHP de l'aplicació de borsa de treball de l'IES Jaume II.

L'aplicació està preparada per llençar-la des d'aquesta mateixa carpeta mitjançant un contenidor amb Docker, de manera que no necessitem configurar un servidor web al nostre equip.

Per tal de llençar l'aplicació, farem, des d'aquest directori `app`:

```sh
app$ docker-compose up
```

I amb això ja tindrem disponible l'aplicació al port `8080` de l'adreça local, a través de `http://127.0.0.1:8080`.