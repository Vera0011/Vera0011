# CODE:
``` js
let obj = {
  name : "Vera",
  age : "19",
  level : "Junior",
  country : "Spain",
  languages : ["JavaScript", "C", "MySQL", "SQLite", "CSS3", "HTML5"],
  frameworks : "Node.js"
};

console.log(`
\nName: ${obj.name}\nAge:${obj.age}
\nLevel in programmation: ${obj.level}
\nCountry: ${obj.country}
\nLanguages: ${obj.languages.toString().replace(/,/gm, ' ')}
\nFrameworks: ${obj.frameworks}`);

```
# RESULT:

```
Name: Vera
Age: 19
Level in programmation: Junior
Country: Spain
Languages: JavaScript C MySQL SQLite CSS3 HTML5
Frameworks: Node.js
```
