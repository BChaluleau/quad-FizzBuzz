# quad-FizzBuzz
Template de projet pour TDD

## Mise en place
- Ajouter le projet sous Pycharm
- Ne pas oublier de déclarer un venv
- Si pycharm ne détecte pas le requirements.txt utiliser
```commandline
virtualenv venv
# sous Linux / MacOS
. venv/bin/activate

# sous Windows
venv\Scripts\activate.bat
```
- Vérifier que le test (stupide) s'exécute avec une couverture de 100%
```commandline
# Linux / MacOS
python -m pytest tests/unit --cov=.

# Windows
python -m pytest tests\unit --cov=.

```
