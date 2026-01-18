```python
from typing import List, Dict


class Profile:
    """
    while not done:
        do_it_yourself()  # KISS
    """

    def __init__(self):
        self.stack: List[str] = ["python", "typescript", "csharp", "javascript", "visualbasic"]
        self.tech: Dict[str, List[str]] = {
            "backend": ["django", "fastapi", "nodejs", "aspnetcore"],
            "frontend": ["angular", "sass", "blazor", "webforms"],
            "database": ["postgresql", "mongodb", "oracle", "mssql"],
            "other": ["machine_learning", "generative_ai", "automation", "azure"],
        }

    @property
    def exploration(self) -> Dict[str, List[str]]:
        return {
            "iot": ["raspberrypi", "arduino"],
            "mobile": ["flutter", "swiftui"],
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
