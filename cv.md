# Olga Khmaruk
![Olga Khmaruk](https://i.postimg.cc/pT8YHQT1/1556176377.jpg)

## My Contact Info
- Phone: +375 (29) 601-71-88
- E-mail: [athamethedarkest@gmail.com](mailto:athamethedarkest@gmail.com)
- GitHub: [HelgaAthame](https://github.com/HelgaAthame)
- Telegram: HelgaAthame
- Codewars: [Helga Atgame](https://www.codewars.com/users/HelgaAthame)
## About Myself
I started getting interested in programming when I was in high school. \
I have studied Photoshop, HTML, CSS on my own and started making websites.\
I use keep learning.\
I worked as a site administrator for an online store for three years, but I was always interested in programming.\
To increase my knowledge and develop myself different ways I studied [SEO](https://proseo.by/kursy/) and [Performance Optimization](https://training.epam.com/Training/Details/2957?lang=en) courses. \
I am interested in constantly deepening and expanding my knowledge. \
I studied the basics of Software Testing using textbook by S.Kulikov. \
A few of years ago I got interested in Unity and was involved in the development of a mini-game using C# code. \
Over the past six months I have learned JavaScript on my own using [I. Kantor's online tutorial](https://learn.javascript.ru/). I also solved the problems suggested in this tutorial. \
At the same time I was captivated by the exciting process of solving problems on [Codewars](https://www.codewars.com/users/HelgaAthame). I have reached 4 kyu level. \
In recent months, I started learning the React framework using [D. Trepachev's online tutorial.](http://old.code.mu/books/advanced/javascript/react/)\
In addition, I have a master's degree in Art science. It makes me a versatile person.\
I can organize my work schedule rationally and find time for music and exercise.\
I came to RS School to get full and deep knowledge, do an internship, and also find a job as a Junior JS Front-end developer.\

#### My strengths:
- I go to the end when others give up;
- I find answers on my own when others ask too many questions;
- I can work in a team and resolve conflicts;
- I know the value of time and do everything on time.

## Skills:
+ HTML
+ CSS
+ JavaScript
+ React
+ Codewars 4kyu
+ Git/Github
+ VS Code
+ Adobe Photoshop
+ MySQL (basic knowledge)
+ SEO (basic knowledge)
+ Performance Optimization (basic knowledge)
+ Software Testing (basic knowledge)
+ Unity/C# (basic knowledge)

## Code Exaple
#### Permutations (from Codewars 4kyu)
**Description:**
In this kata you have to create all permutations of a non empty input string and remove duplicates, if present. This means, you have to shuffle all letters from the input in all possible orders.

**Solution**
```
function permutations(string) {
  let result = string.split('');
  function func (arr) {
    if (arr.length == 1) {
      return arr;
    } else {
      let curLet = arr[arr.length-1];
      let prevArr = func (arr.slice(0, arr.length-1));
      let resArr=[];
      for (let i=0; i<prevArr.length; i++) {
        for (let j=0; j<=prevArr[i].length; j++) {
          let el = prevArr[i].slice(0, j) + curLet + prevArr[i].slice(j, prevArr[i].length);
          if (!resArr.includes(el)) resArr.push(el);
        }
      }
    return resArr;
    }
  }
  return func (result);
}
```

## Education
#### University:
- Belarusian State University of Culture and Art
   + Folk science. Diploma with honors.
- Graduate School of the National Academy of Sciences
   + Art science. Master degree.
#### Courses:
- [SEO](https://proseo.by/kursy/)
- [Performanse Optimization](https://training.epam.com/Training/Details/2957?lang=en)
- [JavaScript Front-end](https://rs.school/js/) (in process)

#### Self-education:
- [JavaScript](https://learn.javascript.ru/)
- [Software Testing]()
- [React](http://old.code.mu/books/advanced/javascript/react/)

## Experience
Site administrator of online store (3 years).

## Languages:
+ English B1 (training by test result)
+ Belarusian (native)
+ Russian
