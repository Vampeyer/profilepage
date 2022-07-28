# profilepage


Ladies, Gentleman, and bypassers alike ,


Welcome ,  to my landing page ,   
 I hope you  find yourself comfortable and enjoy my code as well as the page. 
this page is in infancy at this point but however will be continued upon until animations , etc and all will show the full diaplay in the future

the designs are quite fun to play with though , theres no telling 
what the final product will be like !  

Please enjoy , and feel free to judge and participate alike! 



------------------------- 
- - IMPORTANT  NOTES - -    

------------------------------------------

* about me > img and contact gif > img have been "ultra" customized for size , use as needed. 


- - - 7/ 24 / 2020 
this is now a main site from a older repo on git hub because of upstream repository . due to previous linking issues. - 

name change from profilesite to profilepage repo ,  

Enjoy ! 

- - 7/26 /2020 

Project should be complete so I will now follow suit with a Code Louisville 
==========================================================================================
Project Requirement Checklist 
=========================================================================================
* Visually appealing , 
project has custom photos , links and a "smooth" and "Stylish " text accordingly 

* Include a minimun of 2 media Queries , - Im not even going to reference this as my code is littered with them .   Media queries are an interesting feature for a number of uses and helped me kind of relate to jquery and learning that.  

* github repository with at least 5 commits , 
     - I have committed a lot and working with git is both a tool to have to learn , and super helpful for version control.  -  -  - -  - but great tool to use and learn. 
     
* CSS requirements ,  - nav menu and flexbox. I used 3 media queries at the least and there still may be extra uneeded media queries , will focus on that more later

columns in the media queries in the main paragraph text

columns in one other page i think4

custom phone # and email links

menu bar resizes  w media query - (min-width)

the gif on my contact page on full screen will draw you in to pass and hire me. 

* Java script requirements ,    

    - button using a btn variable in javascript

   - targeted h2 string text in HTML 

   -  targeted h4 string text in HTML tied files
   


    If you noticed i named myself a variable of  "student" as a string variable.  looking in the console you will se I have passed my name in as a variable to create a console that says I passed this requirement,   I definintly need some more javascript practices and comfortability, but its also a great way to check for errors and truthys with console.log.   


/ /  JavaScript Requirements , Revised , 
/- revised 07/27/2022   - I wasnt really sure of where else I wanted to use JavaScript at , so I gave a strong description to represent knowledge base on the subject. 


// ====Very short description of JavaScript Functionality in code . ===== // 


the button function , 
the h2 , 
and the h4 being targeted with the variables  sayhellojavascript and provideservicesjavascript respectively , 
being passed into the DOM with the document.querySelector , should meet the requirements , but here is a closer look at the .js files . . . 


//--------------------------------------------------------------------------------------------------------------------------
  // - Alert and Confirm Description - // 
// - line 2   - - - -passes a string value into the JRE using the -  alert - function , which is then opened , displays the -"string text value" 
// in a window  -,  and 
//       then prompts a click to continue.
// - line 3 ,   - - - - then passes a string value into the JRE using the - confirm - function , in which the prompt both displays the 
//'string text value ' , through the JRE , but also has an additional confirm button that then prompts the user to be sure that they will proceed, 
// (this implicitly returns a Boolean value to the user that is determining if it is the (coolest website and that is (=== true )); .
//------------------------------------------------------------------------------------------------------------
 // - Nav Menu Button - // 
// lines 6 - 15  - - - creates the JavaScript for the button action within the drop down menu, 
// -Starting on line 6 a decleration is used ,the - let - declaration , this declares a variable , a variable of btn.
//  the btn variable is then declared as a Boolean Function to be true with the one equal sign , 
// addressing the - document.querySelector - method , this then targets the (' button') element -

// - on line 7 -------the same process is repeated , however while using the - let  - declaration , the variable is now named list
// the value of this is then again DECLARED to be equal to the same, document.querySelector method , 
// however this time targeting the class , the class of .list

// Moving forward ,  on line 9 -------the -  btn  - variable as discussed above is run , with the .addEventListener method.
// this creates a listening event for the btn variable. 
// - This   .addEventListener method , then uses a click event , to listen to. 
// , giving us something like 
//
// - btn.addEventListener('click') 
//  
// Further methods can be called within this function , and is seperated, inside ,  by the seen parentheses () ,
// -giving us an option like 
//btn.addEventListener('click' ,() )       -  which is then given the condition of , 
// btn.addEventListener('click' ,   () =>    {}    )      - note the brackets to be a seperate method, in which we can imply rules. 

// in this case I choose a if / else statement which is placed into this code as such 
// if () {} else {} , written as a Boolean Expression , it is formatted at such . 

// if true do ()   , if not true do {}
// else , do {} 

// which is then closed in code with  corresponding
 //   )  and } symbols    
//---------------------------------------------------------------
// h2 selector
-------------------------------
// - Code on lines 20 and 21 , dictate the string of text ,in the h2 section of the tied HTML file. 
//
// code on line 20 uses the - const -  declaration  to declare the variable  , provideservicesjavascript , to a  document.querySelector that
// specifically is assigned to the (h2)
// element
//
//code on line 21 starts with the  variable sayhellojavascript, and applies the method .textContent. giving us 
//, sayhellojavascript.textContent 
// as the .textContent method , is obviously a method , 
// in which the targeted element , in this case the h2 element , 
// is targeted and a string of text is applied.  this seems to be a string based method. 
// all in all the h2 element is now set to display the sayhellojavascript variable , 
// and will display its string value of     'Hello worlddd!'   in the h2 element on the targeted HTML
// 
//
---------------------------------------------------------------
// h4 selector
-------------------------------
// - Code on lines 25 and 26 , dictate the string of text ,in the h4 section of the tied HTML file. 
//
// code on line 25 uses the - const -  declaration  to declare the variable  , provideservicesjavascript , to a  document.querySelector that
// specifically is assigned to the (h4) element
//
//code on line 26 starts with the  variable provideservicesjavascript, and applies the method .textContent ,  giving us , provideservicesjavascript.textContent 
//as the .textContent method , is obviously a method , 
// in which the targeted element , in this case the h4 element , 
// is targeted and a string of text is applied.  this seems to be a string based method. 
// all in all the h4 element is now set to display the sayhellojavascript variable , 
// and will display its string value of   'Quality Services'  in the h4 element on the targeted HTML. 
// 
//----------------------------------------------------------------------------------------------


--------------------------------------------------------
// - console.log  practice function
----------------------------
<<<<<<< HEAD
// - check the object in the console for details . 
=======
// - Code on lines 35 and 36 in app.js

// this code allows the variable student to be declared ,   
// then allows the string text to be valued at the student variable
// then the console.log function is called and calls the (student) value to be placed in the console.log function
//then ,as the student variable  is then passed into the function here, 
// the console.log function, works , as it is then passed through the JRE , and then displays a text in the 
// in the console , indicating a string value of "student has passed".

// - to see that the student has paassed with the proper JavaScript Requirements , 
, look in the Service page , of the Quality Services text. 
>>>>>>> 21e3ca2dd0b5e40562d48dd6ac8d6bae5289af28


//-------------------------------------------------------------------------------------------
    
     ----------------------------------------------------------------------------------------
    Requirements Complete. 
    --------------------------------------------------------------------------------------

====================================================================================================================





    
    Note - ignore project section and be on the look out for upcoming revision in the text. 
    

    - in the future - 
    
     Project #1 is going to be a code louisville web dev repo, based out of all the stuff I had too look up , normal code , manuals and a big reference page for help in coding.  
     
     Project #2 Is a enviromental project where I will utilize smart contracts for decarbonization measurements
     
     -  They will be updated in the future as my skills improve. , 
     I can fluently and easily debug now so after all this work that is a nice tool to have learned honestly. 
     ---------------------------------------------------------------------------------------
     I would like to take this section out to thank and appreciate all my Code Louisville mentors
      For help during those long bug errors and a great experience learning this all  - 
     
     Happy coding and 
     
     Enjoy my repo !  
     
     - Vampeyer - 
     
     
     
     
     
     
     p.s. please remind students to NEVER edit the 
     repo online , for the chance of gitting into a merge conflict of horribly wasted time, 
     trying to resolve the git by itself. 
     
     
     








