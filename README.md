# Simon Game

This is a solution to the Simon Game.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information

### Links

- Solution URL: [https://github.com/Soaphub/Simon-game]
- Live Site URL: [https://soaphub.github.io/Simon-game/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Styled Components](https://styled-components.com/) - For styles

### What I learned
```js
    const checkPattern= (i)=>{
        if(random[i]===userPattern[i]){
            if(random.length===userPattern.length){
                setTimeout(() => {
                    randomPattern();
                }, 1500);
            }
        }
        else{
            endGame();
        }
    }
```

### Continued development

Please provide further recomendation.


### Useful resources

- [https://www.youtube.com/c/TheNetNinja] - This helped me for custome Hooks. 

## Author

- Website - [Ambadi](https://soaphub.github.io/Simon-game/)


## Acknowledgments

The udemdy coarse by Angela helped a lot in completing the project.

