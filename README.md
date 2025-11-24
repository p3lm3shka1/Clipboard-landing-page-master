# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

# Links

[Repository URL](https://github.com/p3lm3shka1/Clipboard-landing-page-master)

[Live site URL](https://p3lm3shka1.github.io/Clipboard-landing-page-master)


## Project Setup & SCSS Compilation Process

This project was built using HTML, SCSS.

## SCSS Workflow

All styling in this project is written in SCSS and compiled into a single ```style.css``` file.

### Process of creating the SCSS files:

Split the styling into several SCSS partials such as:

```_variables.scss``` — color palette and global variables

```_mixins.scss``` — reusable functions and mixins

```style.scss``` — main file that imports all partials

Compiled SCSS into CSS using a npm script and Live Sass Complier:

```
sass styles/style.scss styles/style.css --watch
```

The compiled CSS file (style.css) is then linked in index.html.

## Responsive design with **@media**

<details>
  <summary>Mobile version</summary>
  
  ```
@media (max-width:480px)
```
<img width="100" height="550" alt="image" src="https://github.com/user-attachments/assets/2630131f-6ba4-40ee-8358-4d7489038d81" />
</details>  

<details>
<summary>Desktop version</summary>
<img width="1200" height="500" alt="image" src="https://github.com/user-attachments/assets/8d451260-51cd-4c1c-8625-6f30c930a7f5" />
</details>

## Author

- Website - https://github.com/p3lm3shka1
- Frontend Mentor - https://www.frontendmentor.io/profile/p3lm3shka1
