
https://github.com/mihaiserban/es6-cheetsheet/blob/master/README.md

<details>
<summary>Spread Operator</summary>

```javascript 
const app = new App()
const arr = [7,8,9]
const newarr = [1,2,...arr]

```
</details>


//How to copy an array and add an item to it
const newMenu = [...arr,'Gnocci']

//Join two arrays
const menu = [...restaurant.starterMenu,...restaurant.mainMenu]

// Join strings
const str = "Jonas"
const letters = [...str,'','S.']
console.log(letters) ['J','o','n','a','s']