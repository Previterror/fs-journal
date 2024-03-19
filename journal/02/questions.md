# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    let, const, var

02. What is the definition of a function?

    A function is a subprogram; used to complete certain tasks that may be required repeatedly throughout your

03. What are the `SOLID` principles?

    > | ANSWER HERE |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    delete fruit[2]
    fruit.splice(2,2)
    fruit.filter(pineapple)

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    array.friends += otherarray.name

06. Give an example of a JavaScript `Conditional`:

    if(hair = false){
        friends = []
    }

07. What is the main difference between `parameters` and `arguments`?

    Parameters are the box you would insert the argument into.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | ANSWER HERE | 

09. What is the difference between a `primitive` value and a `reference` value?

    A primitive passes only the value, a reference passes the entire object.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    for (i = -100; i > 101; i++){
        console.log(i)
    }