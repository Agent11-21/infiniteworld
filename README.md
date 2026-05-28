# infiniteworld

is a pip package for a infinite world generator

## Installation

```bash
pip install .
```

## Utilisation

```python
from infiniteworld import World

world = World()

chunk = world.get_chunk(0, 0)

print(chunk[0][:10])

world.preload_around(0, 0)
```
