/ _ \ | | () | | | | | | |
/ /\ \ | | | | ___ | | ___ _ __ _ _ ___ ___ | | _ __ _ __ ___ | |
| _ | | '_ | | |/ _ / | / _ | ' | | | |/ / _ \ | | '| ' ` _ \ | ' \
| | | | | |) | | | /_ \ || () | | | | || | (| / | || | | | | | | | | | | |
_| |/ |./|||_||/__/|| ||_,|__| _/| || || || || |_|

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self):
        self.name = "Abdirahman Farah"
        self.role = "Software Engineer"
        self.languages_spoken = ["Somali", "English", "Swahili", "German"]
        self.self_learning = ["Data Science", "Machine Learning"]

    def say_hi(self):
        print(f"Hi, I'm {self.name} — thanks for visiting! 🚀")

me = SoftwareEngineer()
me.say_hi()
