```python
class DeveloperProfile:
    def __init__(self):
        self.name = "Augusto"
        self.age = 26
        self.job = "python dev at OSDEPYM"
        self.studies = "engineering at UADE"
        self.hobbies = ["music"]
    
    def introduce_myself(self):
        return f"👋 Hi! I'm {self.name}, {self.job}. I study {self.studies} and I love {self.hobbies[0]}."

augusto = DeveloperProfile()
print(augusto.introduce_myself())
```
