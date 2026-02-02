```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class SoftwareEngineer:
    def __init__(self):
        self.name = "Abdirahman Farah"
        self.role = "Software Engineer"
        self.location = "Kenya"
        self.languages_spoken = [
            "Somali",
            "English",
            "Swahili",
            "German"
        ]
        self.skills = [
            "Python",
            "JavaScript",
            "React",
            "Node.js",
            "SQL",
            "Django"
        ]
        self.self_learning = [
            "Data Science",
            "Machine Learning"
        ]
        self.learning = [
            "React Native",
            "System Design"
        ]
        self.open_to = [
            "Collaboration",
            "Open Source",
            "Internships"
        ]

    def say_hi(self):
        print(f"Hi 👋, I'm {self.name}")
        print(f"Role: {self.role}")
        print(f"Location: {self.location}")
        print(f"Languages: {', '.join(self.languages_spoken)}")
        print(f"Self-learning: {', '.join(self.self_learning)}")
        print("Thanks for visiting my GitHub! 🚀")

me = SoftwareEngineer()
me.say_hi()
