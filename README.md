```python
from dataclasses import dataclass
from typing import Tuple

@dataclass
class Danny:
  name : str = "Danny Boland"
  employer : str = "Bloom & Wild"
  role : str = "Lead Data Scientist / Engineer"
  location : str = "Edinburgh, Scotland"
  languages : Tuple[str] = ("Python", "Rust")
  pronouns : Tuple[str] = ("He", "Him")
  website : str = "https://boland.dev"
  social : str = "https://linkedin.com/in/dannyboland"
  ```
