```python
class WajdiJomaa:
    def __init__(self):
        self.name = "Wajdi Jomaa"
        self.email = "wajdijomaa9@gmail.com"
        self.linkedin = "https://www.linkedin.com/in/wajdi-jomaa/"
        self.phone = "+96176567261"

    def education(self):
        return "MSc in Software Engineering, Lebanese University"

    def experience(self):
        return {
              "Mobinets": "Junior Backend Developer",
              "ProCCS"  : "Backend Developer internship",
              "DTP"     : "Test Automation internship"
        }

    def skills(self):
        return ["Python", "SQL", "FastApi", "Flask", "JavaScript", "Java", "Linux"]

    def __repr__(self):
        return f"{self.name}-{self.email}"
```
