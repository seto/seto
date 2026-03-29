```python
from typing import List, Set


class Profile:
    """
    while not done:
        do_it_yourself()  # KISS
    """

    def __init__(self):
        self.langs: Set[str] = {
            "python", "javascript", "sql",
        }
        self.core: Set[str] = {
            "automation", "ai_engineering", "full_stack",
        }

    @property
    def exploring(self) -> List[str]:
        return [
            "iot", "robotics",
        ]

    @property
    def interests(self) -> List[str]:
        return [
            "cyberpunk", "audiophile", "film_buff", "digital_worlds",
        ]

```

<p align="center">
  <a href="http://www.catb.org/hacker-emblem/">
    <img width="22" height="22" src="http://www.catb.org/hacker-emblem/glider.png" alt="Hacker Emblem">
  </a>
</p>
