```python
from dataclasses import dataclass
from typing import Tuple

@dataclass
class Danny:
  name : str = "Danny Boland"
  employer : str = "Zoe"
  role : str = "Lead Engineer"
  location : str = "Edinburgh, Scotland"
  languages : Tuple[str] = ("Kotlin", "Python")
  pronouns : Tuple[str] = ("He", "Him")
  website : str = "https://boland.dev"
  social : str = "https://linkedin.com/in/dannyboland"
  ```
