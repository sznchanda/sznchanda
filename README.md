<center> <h1>Hello, I'm Steeve 👋🏾 </h1> </center>

``` Python
#!/usr/bin/env python3

class AboutMe:
    def __init__(self):
        self.name = "Steeve Nchanda"

        self.occupation = "Cyber Security Apprentice @ Alstom"

        self.education = "BASc(Hons) Digital Technologies @ YorkU"

        self.certification = "CompTIA Security+"

        self.interets = {
            "Cyber Security": [
                "Threat Hunting",
                "Penetration Testing",
                "Incident Response",
                "Cloud Security",
            ],
            "Programming": [
                "Python",
                "Java",
            ]
            "Podcasts":[
                "Cybersecurity Magazine Podcast",
                "Cybersecurity Today",
                "Hacker And The Fed",
            ]
        }

        self.skills = {
            "Soft": [
                "Lifelong Learner",
                "Strong self-starter",
                "Excellent communicator",
            ]
            "Technical": [
                "Threat Detection",
                "Malware Analysis",
                "IT Security Policies & Procedures",
            ]
    
    def say_hello(self, name: str):
        print(f"Hello, {name}!")

if __name__ == "__main__":
    steeve_nchanda = AboutMe()
    steeve_nchanda.say_hello("world")

``` 
