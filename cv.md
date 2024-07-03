# Palina Pryhazhayeva

## Contact me
- Email: polina.p@gmail.com
- Mobile: +77777777
- LinkedIn: [Palina Pryhazhayeva](https://www.linkedin.com/in/polina-dev/)
- Discord server user: [Polina (@royalehoneybadger)](https://discordapp.com/users/vibing-bageta)

## Summary
>Aspiring student ready to take on new opportunities and challenges in order to launch my career as a Front-End developer. I'm on my 2nd year of Bachelor's studies having experience in areas of software development, network/administration, project management. Through self study, I lay ground work to excel in the job market. 

## Skills
- ***Languages***: C/C++, C#, Java, JS, Python
- ***Libraries/frameworks***: Cypress, Selenium, Pytest
- ***Project Tracking***: Jira, Scrum Desk
- ***DB***: SQL, CRUD, MongoDB, API, Postman
- ***OS***: Windows, Linux, iOS


## Code Snippet

**Main functionality positive test**

***Put in order for funeral***

```
describe('Main functionality test', function(){

it('Positive form test [T-01P]' , function(){

    cy.visit('https://pohrebbezobradu.testovaci-stranka.cz/');

    // Customer Form
    cy.get('#name').type('Antonina');
    cy.get('#surname').type('Sokolova');
    cy.get('#adress').type('U Křížku 992, pokoj č. 34, Križany, 463 53');
    cy.get('#relationship').type('Bratř'); 
    cy.get('#tel').type('720496543'); 
    cy.get('#email').type('animetianochka@gmail.com'); 


    // Deceased Form
    cy.get('#name2').type('Jiří'); 
    cy.get('#surname2').type('Houba'); 
    cy.get('#place2').type('Nové Město 1919/45, pokoj č. 234, Ledec Nad Sázavou, 584 01');

    cy.pause();

    // cy.get('#birtdate').type('01/01/1970');
    // cy.get('#deathdate').type('01/01/2020');  

    cy.get('#place3').type('Nemocnice 3');
    cy.get('.btn').click();

    cy.contains('p', 'Děkujeme za odeslání formuláře').should('be.visible');

});
```

## Working Experience
- **IT department trainee**
    - Project support in the department.
    - Administrative support in __Citrix__, __Active  Directory__.
    - Data processing in __SAP__, __Palstat__, __MS Office__.
    - Translation of technical documentation.
    - Preparation of presentations.
    - Support of individual users.


## Education
- College of Polytechnics Jihlava
  - Applied Informatics
  - 2022 - 2025 ***(Expected)***
### Programs & Courses
1. Blended Intensive Program:
    - Blockchain and Finance
    - 2023, Leuven, BG

2. Blended Intensive Program:
    - Finance Sumulation Game
    - 2024, Riga, LV

## Languages
- Russian:     ***native***
- English:     ***B2-C1***
- Czech:       ***B2-C1***
