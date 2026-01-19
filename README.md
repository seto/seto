```python
from typing import List, Dict


class Profile:
    """
    while not done:
        do_it_yourself()  # KISS
    """

    def __init__(self):
        self.stack: List[str] = ["python", "typescript", "csharp", "javascript"]
        self.tech: Dict[str, List[str]] = {
            "backend": ["django", "fastapi", "nodejs", "aspnetcore"],
            "frontend": ["vue", "angular", "blazor"],
            "database": ["postgresql", "mongodb", "mssql"],
            "other": ["automation", "ai_engineering", "machine_learning", "azure"],
        }

    @property
    def exploration(self) -> Dict[str, List[str]]:
        return {
            "iot": ["raspberrypi", "arduino"],
            "mobile": ["quasar", "flutter", "swiftui"],
        }

    @property
    def interests(self) -> List[str]:
        return ["cyberpunk", "audiophile", "film_buff", "digital_worlds"]
```

<p align="center">
  <a href="http://www.catb.org/hacker-emblem/">
    <img width="22" height="22" src="http://www.catb.org/hacker-emblem/glider.png" alt="Hacker Emblem">
  </a>
</p>
