# Kalmyrza Zholchubekov 
### Junior Frontend/Web Developer  

---  

### Contact information:  
**Phone:** +996 706317022  
**E-mail:** zholchubekovk@gmail.com  
**Telegram:** @Kalmyrzazh  

---

### About me 

I am 21 years old. I study software engineering at university. There I discover front end development. And till now it is my main study subject.I've learned nesessary tools to create simple web applications and created different study projects. 

---
### Skills
- HTML5, CSS3
- JavaScript
- Git, Github
- VS Code, Intelije IDEA
- Python

---

### Code example:
Given a string s, find the first non-repeating character in it and return its index. If it does not exist, return -1.
Example 1:
Input: s = "leetcode"
Output: 0

```
function firstUniqueChar(s) {
  let obj = {};
  for (let char of s ) {
    if (obj.hasOwnProperty(char)) {
      obj[char]++
    }else {
      obj[char] = 1
    }
  }

  for (let i = 0; i < s.length; i++) {
    const letter = s[i];
    if (obj[letter] === 1)
      return i;
    }
      return -1
}

firstUniqueChar('lovvole')
```

---

### Education & Courses
- Software engineering 2019-2024 - [AlaToo university](http://alatoo.edu.kg/#gsc.tab=0)
- Responsive web design [freeCodeCamp](https://www.freecodecamp.org/learn/2022/responsive-web-design/) 
- RSShool "JavaScript/Front-end. Stage 1" (in progress)

---

### Languages
- English - Upper-intermediate 
- Russian - native 
- Kyrgyz - native



