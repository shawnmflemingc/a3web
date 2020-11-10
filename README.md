# Geom101 Assignment 3 Technical Guide (2020)
This repository provides some examples and documents best practices for your group to work through in Assignment 3. Each directory has a README.md file that explains the purpose of that directory and its contents. These items will be updated as clarifying questions come. 
## Repository Name
The Github repository must be named exactly `a3web` and hosted as an exact copy on each of your groups' github websites under that repository. You can't edit all 4 at the same time and you must be all editing the same repository together. 

The example website (here) can be visited by going to https://shawnmflemingc.github.io/a3web/

Because there is a default file named index.html within this repository the URL does not require the filename added on the end. It will work with or without it: https://shawnmflemingc.github.io/a3web/index.html.

## Recommended group contribution workflow
The project requires a design first, which will involve the team together making basic decisions. First chose which group member will host the website in their a3web repository and add other group members as contributors. As a team figure what your theme will be and then start mocking up the website and looking at other websites for ideas. 

Once you have a solid idea, divide up the website into components and each group member will focus on their component(s) using their own Visual Studio code on their own computer. Once they have a working prototype or approximation of what they think will meet the needs of that component, bring it to the group. If approved, merge that component into the master website. 

At first the main solution can be a "group template" of sorts. This will basically be an empty shell of a webpage (missing content) but has the overall design of what you are looking for. The entire group should concentrate on one template page together using the collaborative and version control tools built into GIT to work together at the same time. Notice this is not the content of the page--that actually is the easy part! Once you have your single page template design completed your team can divide up the ~8 pages necessary for the project and start filling in the content and "flexing" the design to meet the needs of each individual page. 

So in summary:

1. Add all group members to the one a3web master repository hosted by one group member
1. As a team, divide up the components and assign each to a group member for one "template" page. 
1. Individually design the HTML/CSS and JavaScript for your component a single page "template" that will prototype the design and be modified for all other pages in your site. The content isn't important for this template, just focus on design. 
1. Copy the template for each target page in your site and as a team fill in the "content", modifying the design slightly to adapt to the content on each page. 
1. Check your work using the validation tools. Don't forget spelling!
1. Copy the final website solution to each group members' a3web repository so that it is identical everywhere.
1. Upload the master repository .ZIP code archive to the D2L dropbox to hand it in!

## Comments
Comments are important in all your code. Your group must use an owner name for each section in comments. All code must be divided up and allocated to only one group member and cannot be shared. Contributions from other members are encouraged, but the owner of a code block is the one responsible for its function and how it works with all other sections. 
### HTML comment block example:
Comments must include the group member's name at the start and end of the block. For example:
```HTML
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<!-- -----------------
- Owner : Shawn Morgan
- Date  : Nov 5 (v1)
- From  : https://www.w3schools.com/html/html_intro.asp
------------------- -->
<h1>My First Heading</h1>
<p>My first paragraph.</p>
<!--*** End Owner: Shawn Morgan *** -->
</body>
</html>

```
### CSS comment block example:
CSS comments are similar, and all group members must contribute to the overall CSS:
```CSS
/***************** 
* Owner : Shawn Morgan
* Date  : Nov 5 (v1)
* From  : https://www.w3schools.com/html/html_intro.asp
******************/
p {
  color: red;
} 
/* End Owner: Shawn Morgan */
```
### JS comment block example:
JavaScript comments again are similar, but not everyone has to contribute to the code. 
```JavaScript
////////////////////
// Owner : Shawn Morgan
// Date  : Nov 5 (v1)
// From  : https://www.w3schools.com/html/html_intro.asp
////////////////////

document.getElementById("myH").innerHTML = "JavaScript Comments";
// End Owner: Shawn Morgan
```
## All group members to contribute to HTML and CSS
Each group member helps build the entire website. There are 2 pages per group member required, but that doesn't mean each group member creates two pages in isolation and then the group brings those together. That count of 2 per member means the solution must be that big. Each member should be contributing to sections of every page. Perhaps make one member responsible for the menuing system, another for main body layout and a third can work on the JavaScript interaction. All members would contribute content for the site as well. 

## Use consistent and purposeful HTML style
Use the style guide as a base to form your group's defined style. Neatness counts! Adaptations to this style are ok but should not violate the basics shown in the guide. If in doubt, ask. 

https://www.w3schools.com/html/html5_syntax.asp

## Quality Control
Developing a good website isn’t just about the content. Actually most of your marks comes from what you do in your HTML tags, style from CSS and how well the JavaScript functions. Checking each of these is important to maximize your marks. 

### HTML and CSS validator
Each HTML or CSS error is costly. So use the provided validators to check your HTML, CSS and revise them using the provided tips to solve the problem. 

HTML5 validator: https://validator.w3.org/

CSS3 validator: https://jigsaw.w3.org/css-validator/

### Checking JavaScript code
Use the recommended debugging methods on w3schools, and check the best practices because they align with the assignment

Debugging tips: https://www.w3schools.com/js/js_debugging.asp

Best practices for JavaScript: https://www.w3schools.com/js/js_best_practices.asp

Common mistakes: https://www.w3schools.com/js/js_mistakes.asp
