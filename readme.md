# LB 324

## Aufgabe 2

Erklären Sie hier, wie man `pre-commit` installiert.

python installieren (https://www.python.org/downloads/)

pip installieren:

```
python get-pip.py
or
python -m ensurepip --upgrade
```

Pre-commit installieren:

```
pip install pre-commit
```

Pre-commit ausführen:

```
pre-commit install
```

Nun kann man die .pre-commit-config.yaml-Datei erstellen und dort den Code hineinschreiben.

## Aufgabe 4

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

1. Auf Azure eine Webapp erstellen, indem man einen Service erstellt (https://portal.azure.com/cobrand/)
2. App Services > MyAweSomeWebApp > Configuration
3. "New application setting" drücken
4. Name: PASSWORT, Value: matteo-jakob
5. Speichern

## Link zur Webseite

https://jakobmatteolb-324.azurewebsites.net/
