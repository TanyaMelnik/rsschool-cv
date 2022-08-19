# Melnik Tatiana
## About Me
I am a sociable, ambitious, creative, self-confident person. I behave in a calm way even in difficult situation. I have a strong desire to succeed in my chosen career. 

My goal is to get real work experience as a front-end developer.

## Skills
* HTML5, CSS3
* JavaScript Basics, C++
* Git, GitHub 
* Figma

## Code example
```
btnElement = document.querySelector(".btn"); 
resultElement = document.querySelector(".result"); 
radioButtons = document.querySelectorAll('[name="food"]'); 

btnElement.addEventListener("click", function(){  
    let total = 0;
    for (const radioButton of radioButtons){     
        if(radioButton.checked){
            total+=parseInt(radioButton.value,10);
        }
    }
        resultElement.textContent = total; 
});
```

