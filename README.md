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

console.log(`\n\x1b[33mName:\x1b[0m ${obj.name}\n\x1b[33mAge:\x1b[0m ${obj.age}\n\x1b[33mLevel in programmation:\x1b[0m ${obj.level}\n\x1b[33mCountry:\x1b[0m ${obj.country}\n\x1b[33mLanguages:\x1b[0m ${obj.languages.toString().replace(/,/gm, ' ')}\n\x1b[33mFrameworks:\x1b[0m ${obj.frameworks}`);

```
# RESULT:

```js
\x1b[33mName: \x1b[0mVera
\x1b[33mAge: \x1b[0m19
\x1b[33mLevel in programmation: \x1b[0mJunior
\x1b[33mCountry: \x1b[0mSpain
\x1b[33mLanguages: \x1b[0mJavaScript C MySQL SQLite CSS3 HTML5
\x1b[33mFrameworks: \x1b[0mNode.js
```
