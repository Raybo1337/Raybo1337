```py
from typing import Tuple, List, Dict, Any

ContactTuple = Tuple[str, str, str]
CodingTuple = Tuple[Dict[str, List[str]], List[str], List[str]]
ProjectsTuple = Tuple[List[str], List[str], List[str], List[str], List[str]]

class Raybo:
    def __init__(self):
        pass
    
    @staticmethod
    def contact() -> ContactTuple:
        discord: str = "trusted#0514"
        tg: str = "t.me/Rayb00"

        return discord, tg

    @staticmethod
    def coding() -> CodingTuple:
        langs: Dict[str, List[str]] = {
            'experienced': ['python'],
            'competent': ['java', 'js'],
            'inexperienced': ['c++', 'rust']
        }
        specialities: List[str] = ['software reverse engineering', 'web reverse engineering']
        environnement: List[str] = ['vs', 'vscode', 'pycharm', 'intellij']

        return langs, specialities, environnement

    @staticmethod
    def ventures() -> ProjectsTuple:
        discord: List[str] = ['Member boosting', 'Unlocked generation tools']
        instagram: List[str] = ['Account generation', 'Botting']

        return discord, instagram
    
    def run(self) -> Dict[str, Any]:
      try:
          json = {
              "Contact": self.contact(),
              "Coding": self.coding(),
              "Projects": self.projects(),
          }
      except Exception as e:
          json = {"Error": str(e)}
      return json
```

[![Stats](https://github-readme-stats.vercel.app/api?username=Raybo1337&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

<p> <img src="https://komarev.com/ghpvc/?username=Raybo1337&color=7303FC" alt="Raybo1337" /> </p> (started December 20th, 2022)
