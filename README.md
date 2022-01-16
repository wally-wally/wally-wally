## :hand: Hi there [![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:wallys0213@gmail.com)](mailto:wallys0213@gmail.com) <a href="https://wally-wally.kr" target="_blank">(:arrow_upper_right: More About Me)</a>

### :round_pushpin: Frontend Developer

```javascript
class Developer {
  constructor(name, experiences, subject, techStack) {
    this.name = name;
    this.experiences = experiences;
    this.subject = subject;
    this.techStack = techStack;
  }

  introduction() {
    console.log(`${this.name}'s Experience`);
    this.experiences.forEach((experience, index) => console.log(`${index + 1}. ${experience}`));
    console.log(`${this.name}'s ${this.subject} tech stack`);
    console.log(this.techStack.join(' / '));
  }
}

const name = 'wally-wally';
const experiences = [
  'Gabia Inc. Frontend Developer(2020.10 ~ ing)',
  'Complete SSAFY Overseas Training Program(India Delhi)(2019.12)',
  'Finish course of Samsung Software Academy for Youth(SSAFY)(2019.07 ~ 2020.06)',
  'Bachelor of Science in Electornic Engineering(2013.03 ~ 2019.02)'
];
const subject = 'Frontend';
const techStack = ['Vue.js', 'Javascript', 'Typescript', 'HTML', 'CSS', 'Sass'];
const wally = new Developer(name, experiences, subject, techStack);

wally.introduction();
```
