# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > let, const

02. What is the definition of a function?

    > a snippet of code that can be ran by calling its name

03. What are the `SOLID` principles?

    > They are a list of principles that help a developer write code that is easy to navigate, debug, and build upon.

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice(2, 1)

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

    > you.friends.push(them), them.friends.push(you)

06. Give an example of a JavaScript `Conditional`:

    > if(this || that){do this}

07. What is the main difference between `parameters` and `arguments`?

    > parameters are placeholders that name what an argument will be called

08. Instead of writing everything to the console, what is a better way to debug your code?

    > breakpoints/debuggers

09. What is the difference between a `primitive` value and a `reference` value?

    > a primitive value is stored directly while reference values point to larger spaces in memory 

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100; i <= 100; i++)console.log(i)
