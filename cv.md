# Roman Kavalenka

<img src="https://avatars.githubusercontent.com/u/36262773?s…00&u=57a758424697edbbc3104f9ee42b15f31ec5547e&v=4" alt="photo" width="200" />

***

#### Contacts

* Email: romaaak0748@gmail.com
* Discord: RomanKavalenka(@RomaaaK)

***

#### About Me
Programming is my hobby.
I enjoy solving problems and dealing with difficulties.

***

#### Skils

* HTML
* CSS, SCSS
* JavaScript
* React, Vue

***

#### Languages

* Russian - Native
* English - Basic

***

#### Projects

* [CV task](https://github.com/RomaaaK/rsschool-cv)
* to be continued

***

#### Code example

Write a function, which takes a non-negative integer (seconds) as input and returns the time in a human-readable format (```HH:MM:SS```)

* ```HH``` = hours, padded to 2 digits, range: 00 - 99
* ```MM``` = minutes, padded to 2 digits, range: 00 - 59
* ```SS```= seconds, padded to 2 digits, range: 00 - 59

The maximum time never exceeds 359999 (```99:59:59```)

```
function humanReadable(seconds) {
  let hh = String('0' + Math.trunc(seconds / 60 / 60)).slice(-2);
  let mm = String('0' + Math.trunc(seconds / 60 % 60)).slice(-2);
  let ss = String('0' + Math.trunc(seconds % 60 % 60)).slice(-2);
  return `${hh}:${mm}:${ss}`;
}
```

***

#### Courses and book

* RS Schools Course «JavaScript/Front-end. Stage 0»
* learnjavascript.ru
* HTML, CSS for practice