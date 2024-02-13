#!/usr/bin/env python3

class AboutMe:
    def __init__(self):
        self.name = "Steeve Nchanda"
        self.occupation = "Cyber Security Apprentice @ Alstom"
        self.education = "BASc(Hons) Digital Technologies @ YorkU"
        self.interets = {
            "Security": [
                "Threat Hunting",
                "Penetration Testing",
                "Incident Response",
                "Cloud Security",
            ],
            "Programming": [
                "Python",
                "Java",
            ]
        }
    
    def say_hello(self, name: str):
        print(f"Hello, {name}!")

if __name__ == "__main__":
    steeve_nchanda = AboutMe()
    steeve_nchanda.say_hello("world")
