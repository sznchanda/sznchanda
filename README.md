<center> <h1>Hello, I'm Steeve 👋🏾 </h1> </center>

``` Python
#!/usr/bin/env python3

class AboutMe:
    def __init__(self):
        self.name = "Steeve Nchanda"

        self.occupation = {
            "Cyber Security Apprentice @ Alstom"
            "AI Technologist"
        }

        self.education = {
            "B.A.Sc.(Hons) Digital Technologies @ YorkU" 
            "B.Sc. Mathematics & Statistics @ UY1" 
        }

        self.certification = "CompTIA Security+"

        self.interets = {
            "Aritficial Intelligence": [
                "Machine Learning",
                "Deep Learning",
                "LLMs",

            ]
            "Cloud Engineering": [
                "AWS",
                "Azure",
                "GCP",
            ]
            
            "Programming": [
                "Python",
                "Java",
                "C++"
            ]

        self.skills = {
            "Soft": [
                "Lifelong Learner",
                "Strong self-starter",
                "Excellent communicator",
            ]
            "Technical": [
                "Vibe Coding"
                "Prompt Engineering",
            ]
    
    def say_hello(self, name: str):
        print(f"Hello, {name}!")

if __name__ == "__main__":
    steeve_nchanda = AboutMe()
    steeve_nchanda.say_hello("world")

``` 
