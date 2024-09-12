<center> <h1>Hello, I'm Steeve 👋🏾 </h1> </center>

``` Python
#!/usr/bin/env python3

class AboutMe:
    def __init__(self):
        self.name = "Steeve Nchanda"

        self.occupation = {
            "Cyber Security Apprentice @ Alstom"
            "Former mathematics teacher @ MACSB"
        }

        self.education = {
            "B.A.Sc.(Hons) Digital Technologies @ YorkU" : Current
            "B.Sc. Mathematics & Statistics @ UY1" : Graduated in 2020
        }

        self.certification = "CompTIA Security+"

        self.interets = {
            "Quantitative Finance": [
                "Risk Technolog",
                "Commodities Technology",
                "Equity Technology",
                "Fixed Income Technology",

            ]
            "Cloud Engineering": [
                "AWS",
                "Azure",
                "GCP",
            ]
            
            "Programming": [
                "Python",
                "Java",
            ]
            "Podcasts":[
                "Fancy Quant",
            ]
        }

        self.skills = {
            "Soft": [
                "Lifelong Learner",
                "Strong self-starter",
                "Excellent communicator",
            ]
            "Technical": [
                "Python Data Visualization",
                "Java Object Oriented Programminf",
                "IT Security Policies & Procedures",
            ]
    
    def say_hello(self, name: str):
        print(f"Hello, {name}!")

if __name__ == "__main__":
    steeve_nchanda = AboutMe()
    steeve_nchanda.say_hello("world")

``` 
