# Todo-List Project

![100%](https://progress-bar.dev/100/?title=Done)

This project is written in HTML, CSS and Javascript that helps Jens finish the tasks.

## Result

![img](./images/project-1.png)



## Code
### Function
#### To add task
 `function addTask(){
    if(inputBox.value === ""){
        alert("Please Enter a Task");
    }
    else{
        let li = document.createElement("li");
        li.innerText = inputBox.value;
        listContainer.appendChild(li);
        let span = document.createElement("span");
        span.innerText = "\u00D7";
        li.appendChild(span);
    }
    inputBox.value = "";
    saveData();

}
`

## Live Demo

you can view live demo from [here](https://mahmoud128.github.io/Todo-list/)

## Accounts
### Linkedin [Account](https://www.linkedin.com/in/mahmoud-khaleel-78932a1b5/)
### LeetCode [Account](https://leetcode.com/mahmoud_khaleel/)
