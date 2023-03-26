
# Slava Baranok

***

## My Contact Info

***

* Address: Belarus, Minsk
* Phone: +375339018435
* E-mail: mr.baranok.slava@gmail.com
* LinkedIn: [Baranok Slava](https://www.linkedin.com/in/slava-baranok/)
* GitHub: [mr-Freeman-S](https://github.com/mr-Freeman-S)
* Telegramm: [mr.Freeman](https://t.me/mrfreeman404)

## Briefly About Myself

***
I'm a front-end developer. I have about a year of experience developing spa apps and robust business problem solving
skills.

At the moment I am developing a mobile application for offline meetings using React Native technology and libraries from
React.

In the future, I plan to develop as a full-stack developer. My strengths are learning new technologies and working in a
team. English at pre-intermediate level. I spend my leisure time on study new technologies and English and solve task on
codewars.com.

## Skills

***

* JavaScript
* TypeScript,
* HTML/CSS
* Sass
* React JS
* React Native
* Redux(reactredux,RTK,Redux-thunk)
* Reactrouter 6
* Formik
* MaterialUI

## Code Example

***

```
function toUnderscore(string) {
    string = string + ''
    if (string.length <= 1) {
        return string.toLowerCase()
    }
    let word = ''
    let answer = []
    for (let i = 0; i < string.length; i++) {
        if (/[A-Z]+/g.test(string[i])) {
            answer.push(word.toLowerCase())
            word = ''
        }
        word += string[i]
        if (i === string.length - 1) {
            answer.push(word.toLowerCase())
            word = ''
        }
    }
    if (/[A-Z]+/g.test(string[0])) {
        answer.shift()
    }

    return answer.join('_')
}
```

## Experience

***

* Jan. 2022 - Sep. 2022 IT - Incubator student
    * [Cards](http://mr-freeman-s.github.io/cards-nya/)
    * [Todolist](https://mr-freeman-s.github.io/ToDoList/)
    * [Social Network](https://mr-freeman-s.github.io/Social-network-Murloc/)
* Sep. 2022 — Present «Intry» (FULL-TIME) React Native Developer
    * Development and implementation of new modules. Maintaining existing code, refactoring and bug fixing.
    * Code refactoring and migration to newer technologies
    * Development of a new feature.

## Education

***

* University:  Belarusian State Agricultural Academy
* Courses:
    * Stepick (HTML/CSS)
    * Freecodecamp (JS)
    * IT - Incubator (TS, React,Redux,RTK,Thunk,React Native, Node JS)

## English

***

* __English__  - Pre-Intermediate/Intermediate in progress
* __Belarusian__  - Native
* __Russian__  - Advanced