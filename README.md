## :pushpin: Getting Started [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fwally-wally)](https://github.com/wally-wally) <a href="https://wally-wally.kr" target="_blank">(:arrow_upper_right: More About Me)</a>

```javascript
class Engineer {
  constructor(name, experiences, subject, teckStack) {
    this.name = name;
    this.experiences = experiences;
    this.subject = subject;
    this.teckStack = teckStack;
  }

  introduction() {
    console.log(`${this.name}'s Experience`);
    this.experiences.map((experience, index) => console.log(`${index + 1}. ${experience}`));
    console.log(`${this.name}'s ${this.subject} tech stack`);
    console.log(this.teckStack.join(' / '));
  }
}

const experiences = [
  'Bachelor of Science in Electornic Engineering',
  'Finish course of Samsung Software Academy for Youth(SSAFY)'
];
const subject = 'Frontend';
const teckStack = ['HTML', 'CSS', 'JS', 'Vue.js'];
const wally = new Engineer('wally-wally', experiences, subject, teckStack);
wally.introduction();
```

