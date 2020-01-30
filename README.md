# Harvard CS50W - Project 0

Web Programming with Python and JavaScript

# Requirements

Design a personal webpage about yourself, one of your interests, or any other topic of your choice. The subject matter, look and feel, and design of the site are entirely up to you, subject to the following requirements:

1.  Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks. //done

> :arrow_right: created page1.html, page2.html, page3.html, page4.html and put in a seperate "pages" folder

2.  Your website must include at least one list (ordered or unordered), at least one table, and at least one image. //done

> :arrow_right: Created a product table and used li, ol, ul, img tags inside it

3.  Your website must have at least one stylesheet file. //done

> :arrow_right: added a custom stylesheet. \_name:\* **style.min.css** ; \_location:\* **./dist/css/style.min.css**

4.  Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.

> :arrow_right: selector used => .class{}, #id{}, tag{}, :hover, tag > tag {},  
> :arrow_right: properties used => margin, padding, background, -webkit-background-clip, -webkit-text-fill-color, scroll-behavior, display, justify-content, width, text-transform, border, flex-direction, align-items, transition, border-radius, cursor,

5.  Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens.

6.  You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.

> :arrow_right: integrated bootstrap 4,

> :arrow_right: components used: navbar, table,

> :arrow_right: used 2 column grid bellow product table

7.  Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.

    > :arrow*right: added style.scss in the root directory. *name\* **style.scss**
    > :arrow_right: 6 variables used.
    > 1 $title-color: #ca0074;
     2 $text-color: rgb(56, 56, 56);
    > 3 $pc-title-size: 2.2rem;
     4 $pc-text-size: 1rem;
    > 5 $mobile-title-size: 1.2rem;
     6 $mobile-text-size: 0.7rem;

    > :arrow_right: used 2 SCSS nesting, inside **service** and **contact** section
    > :arrow_right: used 3 SCSS inheritance. **%gradient-bg** , **%gradient-bg-reverse**, **%gradient-text**

8)  In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

Note that not all of the above requirements are covered in Lecture 0, some will be introduced in Lecture 1.
