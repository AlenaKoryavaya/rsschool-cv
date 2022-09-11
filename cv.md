# Alena Karavaya

## Contacts

- Location: Minsk, Belarus
- Phone: +375 33 637-38-67
- Email: elena.koryavaya@gmail.com
- GitHub: [@alenakoryavaya](https://github.com/AlenaKoryavaya)

## Summary

I like programming, working with code is an exciting process for me. When you create beautiful sites, apps and then you breathe the life into them with the help of JavaScript and everything comes alive and now you can interact with your creation.

Seeing the results of your work is what inspires me to study JavaScript in more detail. My main strength in problem solving and fast learning as well as calm and patience. My primmary goal is to accumulate enough knowledge and skills to successfully work as a JavaScript developer.

## Skills

- HTML5
- CSS3
- JavaScript (Basic)
- Git / GitHub
- BEM methodology

## Code example

Given an array/list [] of n integers , find maximum triplet sum in the array Without duplications.

```
function maxTriSum(numbers){
  let uniqueArr = [];

  for(let num of numbers) {
    if(!uniqueArr.includes(num)) {
      uniqueArr.push(num)
    };
  }
  let sortedArr = uniqueArr.sort((a, b) => (b - a)).slice(0, 3);

  return sortedArr.reduce((a, b) => a + b, 0);
}
```

## Experience

- Minsk Regional Agricultural Research Station (2014 - 2016)
  - Agrotechnologist
- Zamok mall, Minsk (2017 - 2019)
  - Sales manager
- "WeHouse GYM" Minsk (2019 - 2020)
  - Manager

## Education

- **State Technical College n.a. B.E. Lobanka (2014)**\
  - Faculty of Agronomy, Agrotechnologist
- **Moscow International University (2020 - ...)**\
  - Faculty of Economics and Management / Management of Organization

## Courses

- HTML5 and CSS3 basics [ru.code-basics](https://ru.code-basics.com/)
- JavaScript/Front-end Pre-School [RS SCHOOL](https://rs.school/js-stage0/) - [certificate](https://app.rs.school/certificate/plexnfoc)
- JavaScript/Front-end RS SCHOOL (in process)

## Languages

- Russian - native
- English - intermediate
