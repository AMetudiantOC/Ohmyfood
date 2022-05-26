# __Ohmyfood__

Third project of the "Web Developer" course at OpenClassroom. The objective is to integrate and dynamize a web page with CSS animations using the Sass preprocessor

You can find the [complete brief here](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Brief%20cre%CC%81atif%20-%20Ohmyfood!.pdf)

![image](https://github.com/AMetudiantOC/ohmyfood/blob/main/src/images/logo/screenshot.png?raw=true)  

## Goals
---------- 
   
1. Develop a website proposing the menu of 4 great Parisian restaurants.
2. Allow online booking and menu composition.  

## Delivery
---------- 
   
### __Pages to be integrated according to the models__
* __Home page__
* __Menu pages (x4)__  

## Animation
----------  
  
__Buttons__  
* On hover, the background color of the main buttons should lighten slightly. The drop shadow should also be more visible.  
* Eventually, visitors will be able to save their favorite menus. For that, a heart-shaped "Like" button is present on the model. When clicked, it should fill up progressively. For this first version, the effect can be shown on hover instead of click.  

__Home page__  
* When the application will have more menus, a loading spinner will be necessary. On this mockup, we want to have a preview of it. It will have to appear for 1 to 3 seconds when we arrive on the home page, cover the whole screen, and use CSS animations (no library). The design of this loader is not defined, so any proposal is welcome as long as it is consistent with the graphic charter of the site.  

__Menu pages__  
* When you arrive on the page, the dishes should appear progressively with a slight time lag. They can either appear one by one, or in groups "Starter", "Main course" and "Dessert". An example of the expected effect is provided.  
* The visitor can add the dishes he wants to his order by clicking on them. A small check mark will appear to the right of the dish. This tick will have to slide from the right to the left. For this first version, the effect can appear on the hover instead of the click. If the title of the dish is too long, it should be trimmed with ellipses. An example of the expected effect is provided.  

## Technologies
----------  
  
__Approved :__ HTML / CSS / Sass  
__Recommended :__ HTML / Sass  
__Prohibited :__ Javascript / Frameworks CSS / Inline CSS  

## Notes
----------
__Fonts :__  
* Logo & titles : Shrikhand
* Text : Roboto

__Colors :__
* Primary : #9356DC
* Secondary : #FF79DA
* Tertiary : #99E2D0

__Constraints :__
* Mobile-first approach: yes
* Mobile model : yes
* Desktop model : to improvise
* W3C HTML validation: to be passed, warning allowed
* W3C CSS validation: to be passed, warning allowed
* Compatibility: Latest versions of Chrome, Firefox & Safari

## Naming convention commit
----------  
  
* [BEM](https://css-tricks.com/bem-101/)
* [Gitmoji](https://gitmoji.carloscuesta.me/)  

## Test the project
---------- 
  
To test simply & quickly, please visit the online demo: [ohmyfood.alexandremagre.com]()  
  
Otherwise, clone the project  
`git clone https://github.com/MathisBarre/MathisBarre_3_04112020.git`  
  
Install dependencies  
`yarn install`  
  
And run the server!  
`yarn dev`  
  
You can also build the project for production:  
`yarn build`  
  
## License
----------  
  
[OPENCLASSROOMS](https://openclassrooms.com/fr/)
