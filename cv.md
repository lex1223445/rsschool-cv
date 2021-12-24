# Ivan Salanovich
## Contacts:
* **E-mail**: sivann97@gmail.com
* **GitHub**: lex1223445
* **Discord**: Ivan Salanovcich
* **Tel.**: +375296976964
## About me:
I am studying at a **RSSchool** to improve my development skills!
## Skils:
* HTML
* CSS
* JavaScript
* Windows OS
* Git
## Code Example:
```js
const asyncMap = async (arr, cb) => {
    return arr.reduce( async (acc, val) => {
        acc = await acc;
        acc.push( await cb(val) );
        return acc;
    }, Promise.resolve([]) )
};

asyncMap([9,8,7,6,5,4,3,2,1], async (val) => {
    const p = new Promise((r) => {
        setTimeout(r, val * 1000);
    });
    await p;
    console.log(val);
    return val;
}).then(console.log);
```
## Work experience:
* Small own busines
## Education and courses:
1.Video courses on YouTube (HTML,CSS,JS,GIT)
2. JavaScript https://learn.javascript.ru/
## Language:
English level - A2
