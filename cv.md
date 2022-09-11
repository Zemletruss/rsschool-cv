# Oleksii Komisarov

![Image must be here](https://i.imgur.com/uzIntn4.png)
### Beginner Frontend Developer
------
### My contact info:

* **Email:** alekseykomisarov@gmail.com
* **Mobile:** +380974792841
* **Telegram:** @alexvonreich
* **Discord:** Aleksey(@Zemletruss)
* **Instagram:** @alex.komisarov
* **GitHub:** [Zemletruss](https://github.com/zemletruss)

---

### About me:

I am starting my career as a Frontend developer, having some knowledge and practice. I've worked at social media arbitrage company and while working there I understood that I want to change my aim in favor of being Frontend developer. I've started learning basics of HTML, CSS and JavaScript. I've also learnt PHP and some SQL. While studying at Polythechnic University of Dnipro, I was convinced that this direction has become my love.

Since I'm interested in UI/UX, being a confident user of Adobe Photoshop, Adobe Illustraror, Corel Draw and Figma, I think of myself as a good one who can master the vocation of a frontend developer.

Three years ago I have passed the [Anton Nevin's](https://de.linkedin.com/in/antonnevin) course of Adobe Illustrator which gave me the whole imagination what design is, what are the basics, the techniques and theory about shapes, curves, color palette, tools, user experience etc.

It's worth to mention that I also know C++ and C# and practiced these languages in my school and university projects.

I am confident and I believe that my skills and motivation will lead me to the top of a Frontend developer path.

---

### Skills:

#### Hard:
+ HTML5
+ CSS3
+ JS Basics
+ PHP
+ SQL
+ Git, GitHub basics
+ Adobe Photoshop
+ Adobe Illustrator
+ Corel Draw
+ Figma
+ Working in VS Code, Sublime text, Visual Studio on .NET Framework
+ C#
+ C++
#### Soft:
+ English C1 Advanced

![Image must be here](https://i.imgur.com/QrfDjGB.png)

+ Logical mind
+ Communicative
+ Prone to learn quickly

---

# Code Example:  
**[Rectangle into squares KATA from Codewars](https://www.codewars.com/kata/55466989aeecab5aac00003e/javascript)**: *Given a rectangle with length `lng` and width `wdth` output an array of lengths of a minimal amount of squares that fit into this rectangle.*

```
function sqInRect(lng, wdth){
  let area = lng * wdth;
  if (lng == wdth) return null;
  let result = [];
  let square;
  while(true){
    if (lng == wdth) {result.push(lng); break;}
    if (lng > wdth){
        square = wdth;
    }
    else {
        square = lng;
        wdth = wdth - square;
    }
    result.push(square);
  }
  return result;
}
```
---
