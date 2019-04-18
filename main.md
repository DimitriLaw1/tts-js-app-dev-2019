# MY First Example

```
 /*console.log(`hello im a string

and this is an example`);

const instructor = {
    name: "dimitri",
    lesson:"ES6",
    greet: function(){
        return `Hello ${this.name} blah blah blah ${this.lesson}`
    }
}

console.log(`Hello ${instructor.name} blah blah blah ${instructor.lesson}`);

console.log(instructor.greet());
 ```
*/

/*

# MY Second Example

```
const teacher = {
    name: "dimitri",
    greet: function(){
        let boundFunction = function(){
            console.log("later my name is" + this.name);
        }
        setTimeout(boundFunction, 7000);
    }
};
console.log(teacher.greet());
*/
```

/*

# MY Third Example

```
let students = [
    {name: 'Hugo'},
    {name: 'Candace'},
    {name: 'Taylor'},
    {name: 'Dimitri'},
];

let names = students.map((student) => student.name);
console.log(names);
 */

/*
```
# MY Forth Example
```
let students = ["bull", "woow", "jobb"];
let [x,y,z] = students;
let [x, ...rest] = students;

console.log([x, ...rest]);
*/ 

/*
var students = [
    {name: 'bobby '}
    
    
];

function apples(peanuts){
peanuts = "pine";
return students.name + peanuts; 
}

console.log(apples());

*/

class SuperHero{
    constructor (name, heroName, superPower){
        super(name);
        this.heroName = heroName;
        this.superPower = superPower;
    }
    secretIdentity(){
        return `${this.heroName} is ${this.name}!!`
    }
} console.log(secretIdentity());

```