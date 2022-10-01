# pungen
Python Username Generator - for all your random username needs!


pungen is a simple to use Python script which generates "usernames" on demand.
The usernames are created on the spot using some pre-defined word-creating formulas.
Don't worry. It's way less complicated than I'm making it sound.


## Usage

### As a script

The format for generating usernames from command line is:

`pungen.py [length // range] [count]`

#### Example:
```console
$ pyngen.py
Debezofotopp
sanebusti9
hidewenehiixo
nerefida
Dateter
nodastoremo
toppatefen
rastari29
Stitalirere
canduzeretii

$ pungen.py 5
Nnote
naral
Hoo59
coge8
ta402
Tuluz
tures
danuf
modot
tohia

$ pungen.py 4-9 3
Sasut379
deseete
toijomono
```

### As a library

You can also use pungen as a library. <sub><sup>*(Backward compatibility is not guaranteed)*</sub></sup>
```python
from pungen import UsernameGenerator

username_gen = UsernameGenerator(7, 13) # min, max = None

username = username_gen.generate()
print(username)
# Outputs sinoqanodo
```
