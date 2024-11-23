# Type Hints

## Type Hints

Neuere Versionen von Python unterstützen optionale Typenannotationen

Typenannotationen können die IDE - z.B. durch das Bereitstellen zusätzlicher Fehlermeldungen

## Typechecker

- pyright (wird von VS Coe extension _pylance_ verwendet)
- mypy

VS Code Extensions für beide verfügbar

## Variablen

Variablen:

```py
i: int = 3
```

## Funktionen

Funktionen:

```py
def double(n: int) -> int:
    return 2 * n
```

## Kollektionen

```py
from typing import List, Set, Dict, Tuple

names: List[str] = ['Anna', 'Bernd', 'Caro']
person: Tuple[str, str, int] = ('Anna', 'Berger', 1990)
roman_numerals: Dict[int, str] = {1: 'I', 2: 'II', 3: 'III', 4: 'IV'}
```

```py
from typing import Iterable

names: Iterable[str] = ...
```
