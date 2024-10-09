---
permalink: /
title: 
---

```python
# Welcome to my portfolio!

class DataScientist:
    def __init__(self, name, skills, interests):
        self.name = name
        self.skills = skills
        self.interests = interests
    
    def introduce(self):
        print(f"👋 Hi, I'm {self.name}!")
        print("I'm a Data Scientist.")
    
    def show_skills(self):
        print("\nMy key skills:")
        for skill in self.skills:
            print(f"- {skill}")
    
    def share_interests(self):
        print("\nI'm passionate about:")
        for interest in self.interests:
            print(f"- {interest}")

# Create my profile
me = DataScientist(
    name="Bruno",
    skills=["Python", "Data Analysis", "Data Visualization", "Machine Learning"],
    interests=["Solving complex and meaningful problems", "Creating AI-powered systems", "Continuous learning"]
)

# Run the introduction
me.introduce()
me.show_skills()
me.share_interests()

print("\nLet's connect and create something amazing together!")
```
👋 Hi, I'm Bruno!
I'm a Data Scientist.

My key skills:
- Python
- Data Analysis
- Data Visualization
- Machine Learning

I'm passionate about:
- Solving complex and meaningful problems
- Creating AI-powered systems
- Continuous learning

Let's connect and create something amazing together!