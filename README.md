# Just for Beginners - Final Fantasy 14's Beginners Guide
# Milestone Project 1
![screen-capture](readme-img/showondevices.png)

You can click this link to the living [website](https://cloki0610.github.io/CI-Portfolio-Project-1/)
## =Purpose=
FF14 is one of most well-known MMORPG in the world. And there are few different FF14 game database and many tools to fulfill their need. But there are too many information prepare to those new players. Instead of 'what I can do', 'what I should do first' are always be the first question to them. Some of them even never play any MMORPG or console game before. So this website will provide a simple guide to help those beginners.

## =Features=
### =Existing Features=
#### Landing Page
* Entrance section
  A section with four button within four rectangle to redirect user to other four pages.

  ![entrance](readme-img/entrance.png)

* Trailer section
  This section shows a embedded video from youtube include user control and hyper link to open the video on youtube in a new tab.

  ![trailer](readme-img/trailer.png)

* Footer
  This section include a e-mail link and four social media icons, if you click the icon the website will open the social media page in new tab.

  ![footer](readme-img/footer.png)

#### Guides(doh.html, dow.html, dow.html)
The content and images may be different, but these three website build by the same structure.
* Navigation bar
  The navigation bar show the title on the left side, and four hyper link on the right side to allow user discover another pages in this website. If user enter the website by mobile, the navigation bar will arranged vertically.

  ![navbar](readme-img/navbar.png)

* Sub-menu
  This section provide a sub-menu and internal links for user just want to read specific paragraph.

  ![submenu](readme-img/submenu.png)

* Main content
  This section included the complete guide for specific type of class.

  ![contents](readme-img/maincontent.png)

* Footer
  This section include a e-mail link and four social media icons, if you click the icon the website will open the social media page in a new tab.

  ![footer](readme-img/footer.png)

#### Giveaway event register form
* This section also have a nevigator bar in header
* Introduction section
  This section shows the details user should know before they enter any information.

  ![form-introdution](readme-img/form-intro.png)

* Form seciton
  This section include a form with reset and submit button. User who can complete this form and send the required information to join our giveaway event in game. 

  ![form](readme-img/form.png)

* Footer
  This section include a e-mail link and four social media icons, if you click the icon the website will open the social media page in a new tab.

  ![footer](readme-img/footer.png)

### Features Left to Implement
* Add a beginners guide in eureka, a up to 144 players instanced area release in 4.0 expansion.
* Add a complete gold saucer beginners guide.
* Add a house purchasing and furnish guide.

## =Testing=
### Functional test
* All animation in index.html(enterance section) and the nav bar in the other four pages are all functional when user hover over the link.
* Video in index.html is functional and responsive by CSS.

#### Responsive Design
I used google DevTools to check different size of screens and their responsive design.
Everythings seems right in place.

#### Links
##### index.html
There four links in enterence section, 
one link in trial section and four external link in footer.
They are all direct to right page with correct target.
#### dow.html, doh.html, dol.html
There are five internal links in nav bar, 
eight internal links in submenu and four external links in footer.
They are all direct to right page with correct target.
#### giveaway.html
There are five internal links in nav bar, 
and four external links in footer.
They are all direct to right page with correct target.
The submit button are functional, but without the action link error message will response to user.

### Validator Testing
Following test are using [HTML - W3C HTML Validator](https://validator.w3.org/) and [CSS - Jigsaw CSS Validator]().
#### HTTP test
All script have been tested without important error.

![html-test-result](readme-img/html_test.png)

#### CSS test
index.css and style.css both pass are all passed test.

![css-test-result](readme-img/css_test.png)

#### Lighthouse
I used lighthouse in Chrome Dev Tools for test the performance of the website.
And the result is in following:
* index.html

![index-test-result](readme-img/index-test.png)
* dow.html

![dow-test-result](readme-img/dox-test.png)
* doh.html

![doh-test-result](readme-img/dox-test.png)
* dol.html

![dol-test-result](readme-img/dox-test.png)
* giveaway.html

![giveaway-test-result](readme-img/giveaway-test.png)


### Unfixed Bugs
Design of index.html and the sub menu in guide pages is not good enough but I have try my best.
Maybe there are still have some responsive design problem I missed or I cannot find out.


## =Deployment=
The website use git for version control, and deploy in Github by following step:

* This website create from Code Institue [template for Gitpod](https://github.com/Code-Institute-Org/gitpod-full-template).
* Every change in this project commit by the VS Code source control function.
* git push command was used to push all committed changes to the GitHub repository.
* When the website almost complete, I login to my GitHub Repository Setting page.
* In the Page section I click the dropdown list under "Scource" and select "main".
* At last I deploy the website after press the "Save" button.


## =Credits=
### Content
  Contents and information are come from:
* [Gamer Escape](https://ffxiv.gamerescape.com/wiki/Main_Page)
* [FFXIV Wiki](https://ffxiv.consolegameswiki.com/wiki/FF14_Wiki)
* And added and modified in my personal opinion

### Images
* All images are Final Fantasy 14 in-game screenshot.

### Media
* This game trailer come from [Youtube FF14 Offical Channel](https://www.youtube.com/embed/zTTtd6bnhFs)

### Tools
* Chrome Lighthouse and Chrome Developer Tools
* HTML - W3C Validator
* CSS - Jigsaw Validator
* Gitpod
* Github

Acknowledgment
Sincerely thanks to my mentor Daisy McGirr for all support and guidance in the process.
