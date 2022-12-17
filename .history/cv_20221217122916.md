# Paderina Olga
## Contact information:
  - Phone number +7 931 288 74 57
  - E-mail: joil.paderina@gmail.com
  - Telegram: https://t.me/jonni_red
  - [GitLab](https://gitlab.com/olga_paderina)
  - [Github](https://github.com/JonniRed?tab=repositories)


----


## About me

I have the skills formed and developed during training and work, which help me to become part of the team as quickly and efficiently as possible, join the work process and complete the assigned tasks.

I have experience teaching and working in various areas of IT, but I get the most satisfaction from web development. In order to create this magic, I study, develop and become better.


---

## Skills

- Figma
- HTML5
- CSS3 (Preprocessor SCSS, BEM-metodology, Bootstrap)
- JavaScript
- React, Redux (Redux Toolkit)
- Node (basic knowledge)
- Editors: Atom, Notepad, Sublime Text, VS Code
- Git (GitHub, GitLab)
- CMS: WordPress, Tilda

----


## Code Example


In project with user validation:
```
buttonReg.addEventListener('click', e => {
    e.preventDefault();
    let validateOk = getValidationUser();
    let user = {};
    user.email = emailData;
    user.password = passwordData;
    if(validateOk){   
        if(localStorage.getItem('users').length !== 0) {
            let newUser = JSON.parse(localStorage.getItem('users'));
            newUser.push(user);
            localStorage.setItem('users', JSON.stringify(newUser));
        }
        
        else {
            const newUser = [];
            newUser.push(user);
            localStorage.setItem('users', JSON.stringify(newUser));
        }
    }
    window.location = 'Enter_page.html'
})
```


React-project:
```
{ basket.map((item, index) => { 
    return (
        <div className="basket__item" key={index}>
            <BasketItem 
                id = { item.id }
                url = { item.img }
                name = { item.title }
                price = { item.price}
                count = { item.count }
            />
        </div>
        )
    }
```
___


## Education
* 2022, Innopolis University - junior frontend-developer (completed)
* Courses (completed): Geekbrains, IT-kama, HTML Academy;
* 2022, RS School, Stage 0 (in progress)

----


## Experience
* 2020-2022 - HTML-coding, website creation and development, creation some portfolio cases.

___


## English 
A1 (in progress)