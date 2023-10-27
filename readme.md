# LB 324

## Aufgabe 2

Erklären Sie hier, wie man `pre-commit` installiert.

python installieren (https://www.python.org/downloads/)

pip installieren:

```sh
python get-pip.py
```
oder falls der obige nicht funktioniert:
```sh
python -m ensurepip --upgrade
```

Pre-commit installieren:

```sh
pip install pre-commit
```
Nun kann man die .pre-commit-config.yaml-Datei erstellen und dort den Code hineinschreiben und danach:

Pre-commit ausführen:

```sh
pre-commit install
```

Erklärung für `pre-push` installation:

Nachdem die obigen Schritte gemacht wurden, kann man auf seinem lokal Git Repository in `/.git/hooks` gehen und danach eine Datei namens pre-push erstellen.

Darin soll folgender Code stehen:

```sh
#!/bin/sh
python -m pytest
chmod +x .git/hooks/pre-push
```


## Aufgabe 4

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

1. Auf Azure eine Webapp erstellen, indem man einen Service erstellt (https://portal.azure.com/cobrand/)
2. App Services > MyAweSomeWebApp > Configuration
3. "New application setting" drücken
4. Name: PASSWORT, Value: matteo-jakob
5. Speichern

## Link zur Webseite

https://jakobmatteolb-324.azurewebsites.net/
