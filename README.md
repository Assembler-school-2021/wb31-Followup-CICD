# wb31-Followup-CICD

Instalamos con este tutorial
https://tecadmin.net/setup-selenium-with-chromedriver-on-debian/

Descargamos el geckodriver tambien:
```
wget https://github.com/mozilla/geckodriver/releases/download/v0.29.1/geckodriver-v0.29.1-linux64.tar.gz
tar -xvzf geckodriver*
chmod +x geckodriver
mv geckodriver /usr/bin
```

> Pregunta 1 : Mira como puedes publicar los resultados del junit test en el pipeline. Si lo haces bien deberas ver algo así :

> Pregunta 2 : Añade al pipeline el TestNG que hemos hecho anteriormente.
