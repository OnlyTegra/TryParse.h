# TryParse.h

Una libreria che fornisce metodi **TryParse** simili a quelli di C# in C++.

## !!! LEGGI LA WIKI PER LE NOVITÀ IN ARRIVO !!!

## Metodi

- **TryParseInt**    - Converte una stringa in un `int`
- **TryParseFloat**  - Converte una stringa in un `float`
- **TryParseDouble** - Converte una stringa in un `double`
- **TryParseBool**   - Converte una stringa in un `bool`

## Come Usare

La funzione restituisce un valore `bool` che indica se la conversione è avvenuta con successo.  
Prende come parametri la stringa di input e una variabile di output:

```cpp
bool TryParse(input_string, output_variable);
```

### Installazione

1. Includi i due file nella cartella principale del tuo progetto.
2. Aggiungi nel file `.cpp`:

```cpp
#include "TryParse.h"
```

3. Compila il progetto con:

```bash
g++ main.cpp -L. -ltryparse -o output
```
