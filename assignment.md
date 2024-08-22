## Assignment

In this assignment, you will learn to use the developer's tool to inspect the elements of [this](https://nznznh.csb.app/) webpage.

1. What is the right margin of the first element? 
```
Right margin of 50px
```

2. What is the top padding of the second element?
```
It has a top padding of 100px, 0px for the other padding sides
```

3. What is the class name of the third element and the content of the css?
```
Third element is a Div element, given the CSS class selector name of "elementThree". 


Content in the CSS class selector is:

    padding: 10px;
    background-color: aquamarine;
    text-shadow: 1px 1px white;
    border: gray solid 2px;
    border-radius: 10px;


```

4. What is the css selector of the fourth element?
```
div:nth-child(6)

because it has higher specificity than the div{} CSS selector.


This is called the ':nth-child()' Selector. It selects the html elements that are the nth child of the parent 
https://www.w3schools.com/cssref/sel_nth-child.php


```

5. What is the code you use to keep the blue box within the purple?
```

.child {
    border: mediumblue 8px solid;
    width: 100%;
    height: 100%;
    margin: 0;
    box-sizing: border-box; // added box-sizing property to be border box
}

By default, box-sizing property is = content-box. Content-box creates an issue where the border and padding thickness will affect the overall dimension of the HTML element's box (eg. heading, button etc.) 

By setting box-sizing = border-box,
The border thickness and padding will be included entirely inside of the box, which means the overall dimensions of the box do not change.

To ask:
Parent div element's width = 500px. So when child div's width = 100%, it copies the parent's width, so child div's width = 500px?


```

> hint: you should apply box-sizing property to the `.child` class. Make the changes on the developer's tool to see immediate UI change.



### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Always store your assignments in the `assignments` folder or `assignment.md` file.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 