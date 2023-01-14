## :hand: Hi there!

### :round_pushpin: Frontend Developer

```javascript
class Developer {
  constructor(name, techStacks, experiences) {
    this.name = name;
    this.techStacks = techStacks;
    this.experiences = experiences;
  }

  introduction() {
    const commonConsoleStyle = 'color: #2985db; font-size: large';
      
    console.group(`%c1. ${this.name}'s Tech Stacks`, commonConsoleStyle);
    Object.entries(this.techStacks).forEach(([priority, techStacks], index) => {
      console.log(`(${index + 1}) ${priority}: ${techStacks.join(', ')}`)
    });
    console.groupEnd();

    console.group(`%c2. ${this.name}'s Experiences (The Latest Order)`, commonConsoleStyle);
    console.table(experiences.reduce((acc, curr, index) => ({ ...acc, [`(${index + 1})`]: curr }), {}));
    console.groupEnd();
  }
}

const name = 'wally-wally';
const techStacks = {
  main: ['Vue.js', 'Javascript', 'Typescript', 'HTML', 'CSS', 'Sass'],
  sub: ['React', 'Python'],
};
const experiences = [
  { title: 'Gabia Inc. Frontend Developer & Unit Leader', date: '2020.10 ~ ing' },
  { title: 'Finish course of Samsung Software Academy for Youth(SSAFY)', date: '2019.07 ~ 2020.06' },
  { title: 'Bachelor of Science in Electornic Engineering', date: '2013.03 ~ 2019.02' },
];

const wally = new Developer(name, techStacks, experiences);
wally.introduction();
```

<br>

### :round_pushpin: Contact Me! <a href="https://wally-wally.kr" target="_blank">(:man_office_worker: More About Me)</a>

[![Gmail Badge](https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=mailto:wallys0213@gmail.com)](mailto:wallys0213@gmail.com) [![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=Instagram&logoColor=white)](https://www.instagram.com/wally.213/) 

