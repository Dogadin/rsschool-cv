# Alexander Dogadin

### Contacts

**Phone:** *(+375 29) 750-75-41*\
**E-mail:** *AlexanderDogadin.7.0@gmail.com*\
**GitHub:** [*Dogadin*](https://Dogadin.github.io/rsschool-cv/cv)

### About Me

I started my career as a radio engineer.
But quickly became involved in programming. Since 2003 I have been a Lotus Domino developer.\
Now there is a desire to learn new technologies. So I decided to learn Java and JavaScript.\
It will be great if I can put my new knowledge into practice.

### Skills

+ HCL Domino, Notes
+ Lotus Script, @Formula
+ Java, Java EE, Spring Framework, JDBC, JUnit, JSP
+ SQL
+ Git, GitHub, GitLab
+ Docker
+ JavaScript (Basic), React
+ IntelliJ Idea, WebStorm, VS Code

### Code Example
**KATA from CodeWars: Pyramid Slide Down**\
*Write a function longestSlideDown that takes a pyramid representation as argument and returns its largest 'slide down'*

```
function longestSlideDown(pyramid) {
  const lengthPyr = pyramid.length
  let prev = pyramid[lengthPyr - 1]
  if (lengthPyr === 1) {
    return prev[0]
  }
  for (let level = lengthPyr - 2; level >= 0; level--) {
    const curr = pyramid[level]
    const currLength = curr.length

    for (let i = 0; i < currLength; i++) {
      const elem1 = curr[i] + prev[i]
      const elem2 = curr[i] + prev[i + 1]
      prev[i] = elem1 > elem2 ? elem1 : elem2
    }
  }
  return prev[0] > prev[1] ? prev[0] : prev[1]
}
```
### Education

+ **University:** Minsk Radio Engineering Institute, radio engineer
+ **Courses:**
    + Udemy - JavaScript, React
    + IT-Academy - Java Core, Java EE

### Languages

+ English - Intermediate
+ Russian - Native
+ Belorussian - Native