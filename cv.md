# Roman Shashin
#### Junior Frontend Developer
#### Contact information:
**Phone:** +7 999 1219245
**E-mail:** propeller1992@gmail.com
**Telegram:** https://t.me/romanshashin
**GitHub:** https://github.com/shamozavr
#### Briefly About Myself:
After several years of work as a sales manager, I realized that I did not want to develop in this direction. I tried myself in different areas and settled on front-end development. The more knowlege and practice I had the more interesting the development seemed to me. I found myself enjoying creating new web interfaces, especially when the work right away.
For now my only goal is studying.
#### Skills and Proficiency:
* HTML5, CSS3
* BEM
* SASS/SCSS
* JavaScript Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
* Figma

#### Code example:
[Highest Scoring Word KATA from Codewars](https://www.codewars.com/kata/57eb8fcdf670e99d9b000272/train/javascript):
```
function high(x){
  let arrOfWords = x.toLowerCase().split(' ')
  let objOfWords = {};
  for (let i = 0; i < arrOfWords.length; i++) {
    let sum = 0;
    let object = {}
    for(let k = 0; k < arrOfWords[i].length; k++) {
      sum = sum + arrOfWords[i][k].charCodeAt() - 97 + 1
    }
    object['index'] = i;
    object['points'] = sum;
    objOfWords[arrOfWords[i]] = object;
  }
  const entries = Object.entries(objOfWords);
  let resultWord;
  let max = 0;
  for (i = 0; i < entries.length; i++) {
    if (entries[i][1].points > max) {
      max = entries[i][1].points
      resultWord = entries[i][0]
    }
  }
  return resultWord
}
```
#### Education
* Lobachevsky State University of Nizhni Novgorod
    * National Economy, Economist
* Linguistics University of Nizhny Novgorod
    * Faculty of Translation, Translator
* [HTML Academy](https://htmlacademy.ru/)
    * HTML and CSS. Responsive layout and automation
* RS Schools Course
    * «JavaScript/Front-end. Stage 0» (in progress)
