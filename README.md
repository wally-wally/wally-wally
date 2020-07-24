## :hand: wally-wally Github [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fwally-wally)](https://github.com/wally-wally) <a href="https://wally-wally.kr" target="_blank">(:arrow_upper_right: More About Me)</a>

### :pushpin: Getting Started

```javascript
class Person {
  constructor(name, experiences, tectStack) {
    this.name = name;
    this.experiences = experiences;
    this.tectStack = tectStack;
  }

  introduction() {
    console.log(`${this.name}'s Experience`);
    this.experiences.forEach((experience, index) => console.log(`${index + 1}. ${experience}`));
    
    console.log(`${this.name}'s tech stack(frontend)`);
    console.log(this.tectStack.join(' / '));
  }
}

const experiences = ['Bachelor of Science in Electornic Engineering', 'Finish course of Samsung Software Academy for Youth(SSAFY)'];
const tectStack = ['HTML', 'CSS', 'JS', 'Vue.js'];
const wally = new Person('wally-wally', experiences, tectStack);
wally.introduction();
```

