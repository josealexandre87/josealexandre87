<h2> Hi, I'm Jose Alexandre! <img src="https://media.giphy.com/media/SF9Z0shNT07T2/giphy.gif?cid=ecf05e47sqlpq8yhggf27v45o2p5p78zuw700a67a390vwbr&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="50"></h2>
<p><em>Software Engineer at <a href="https://www.ampli.com.br/">Anhanguera Pitágoras Ampli University Center</a><img src="https://media.giphy.com/media/10fFT7qzHrN0D6/giphy.gif?cid=ecf05e472j41n37csef1oi5ber72yjll3e9ivgrgsqv9u1rr&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="50">

[![LinkedIn: josealexandre87](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josealexandre87/)
<img align='right' src="https://media.giphy.com/media/oQuiJexT0hB94SIVAx/giphy.gif?cid=ecf05e47moq1thcjfsqjscnyd9lca64adu9wvy893u4vsrvx&ep=v1_gifs_search&rid=giphy.gif&ct=g" width="160">

## Who am I? 
 ```python
class WhoAmI:
    def __init__(self):
        self._user = "Jose Alexandre"
        self._current_work = "Software Engineer at Neuraltronic"
        self._skills = {
            "code": ["HTML", "CSS", "Javascript", "Typescript", "Python", "Java"],
            "tools": ["React", "Django", "Docker"],
        }
        self._hobbies = ["Drawing", "Watching Anime", "Read Manga"]
        self._current_life_projects = [
            self.learn_japanese,
            self.postgraduate_software_engineering,
        ]

    @property
    def user(self):
        return self._user

    @property
    def current_work(self):
        return self._current_work

    @property
    def skills(self):
        return self._skills

    @property
    def hobbies(self):
        return self._hobbies

    @property
    def city(self):
        return "São Gonçalo, RJ"

    @property
    def current_life_projects(self):
        return [project() for project in self._current_life_projects]

    def learn_japanese(self):
        return "Learning Japanese"

    def postgraduate_software_engineering(self):
        return "Postgraduate in Software Engineering"
 ```
---
