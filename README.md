# pungen
Python Username Generator - for all your random username needs!


pungen is a simple to use Python script which generates usernames on demand.
The usernames are created on the spot using some pre-defined word-creating formulas.
Don't worry. It's way less complicated than I'm making it sound.


## How to use

### As a script

To generate usernames in the terminal, `cd` into the repository folder and use this command:

`python3 pungen.py [length / range] [count]`

#### Example:
```console
$ python3 pungen.py
Debezofotopp

$ python3 pungen.py 5
naral

$ python3 pungen.py 4-9 3
Sasut379
deseete
toijomono

$ python3 pungen.py 7-13 10
baheimu
Monuhot
fenuhieheb
tiutenenis
hotito299
Cituditofon
Adipunanis7
Harut722
Nutilanu330
Thondimefo
```

### As a module

You can also use pungen as a module in your python code. <sub><sup>*(Though, backwards compatibility is not guaranteed)*</sub></sup>
```python
from pungen import UsernameGenerator

username_gen = UsernameGenerator(7, 13)

username = username_gen.generate()
print(username)
# sinoqanodo
```
