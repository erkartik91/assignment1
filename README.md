# Assignment1
You are hired as a web developer for UBC bookstore to develop a website to sell their products online. As a part of your job you are going to build an online store where you can list different items that can be sold online. Students can register on the website, browse all the available products, check out availability, read product description and purchase any of the listed items.

To help you get started, you will need to structure your project into the following way for the assignments. **Submission instructions are given in the end of this document.**

* Root folder <all html files go in this folder>
  * css
    * (all stylesheets go in this folder)
  * js
    * (all JavaScript files go in this folder)
  * images
    * (all images go in this folder)
  * index.html (this should be the entry point to your website)
  
As a part of this assignment, you will need to build the homepage for the online store. In the screenshot **layout.png**, we provide you with the wireframe of how the web page should look. You are free to choose colours and fonts of your own choice.

**Marking**: There are 3 tasks for this assignment:
* Task 1: 2 Points
* Task 2: 2 Points
* Task 3
  * A - 3 Points
  * B - 3 Points

**For this assignment, you will be using HTML and CSS to define the layout of a web page and apply styles to different DOM elements. There is no JavaScript required for this assignment, so you will be penalized if you use JavaScript for this assignment.**

**Tasks**
* Create the html layout that will be required to generate the web page provided in the screenshot. Your homepage should include the following elements:
  * Header (id=header)
    * Logo (id=logo)
    * Welcome Banner (id=welcomeBanner)
  * Main Content (id=mainContent)
    * Navigation Menu (id=navigationMenu)
    * Product List (id=productList)
      * product 1 (class=product)
      * product 2 (class=product)
      * product n (class=product)
      * **You can find all the product images, with the product name and price (in the image name) that you will be displaying on the home page.**
  * Footer (id=footer)
* Create a CSS stylesheet to add relevant styles that would help you design the layout for the web page. A few things to keep in mind:
  * The width of the content within the website should be 1000px.
  * The content should be centered within the web page.

* You need to add some interactivity to the website using pure css (no javascript is required for these tasks, so please do not use JavaScript)
  * When you hover over any of the items in the navigation menu, the text and background color should be changed. As soon as you move the mouse pointer away, the color should be restored back to the original color.
  * When you hover over over any of the product, there should be a gray background visible around the product, as well as the product price becomes visible on top of the product image. As soon as you take the mouse pointer away, the price and the gray background should disappear.



**To test you code, insert the following script tags within the head tag of your page**
```
<script src="http://ece.ubc.ca/~kbajaj/cpen400a/jquery.js" type="text/javascript"></script>
<script src="http://ece.ubc.ca/~kbajaj/cpen400a/test1.js" type="text/javascript"></script>
```
You will see  a Red button on the top-right corner of your web page. Clicking on that will let you test your code.

Below you can find the list of products, along with the images and their price that you will be displaying within your website. You will need to save each of these images into the image folder for use.


**Submission instructions:**
* Create a private repository on bitbucket.
* Add your team member as a collaborator.
* Add the TA’s as collaborators
  * er.kartik91@gmail.com
  * gpli@ece.ubc.ca
* For each assignment, create a directory call assignment<number> within the same repository, for ex: assignment1, assignment2, * etc.
* Make sure you push your changes before midnight (11:59 PM) on the day when assignment is due - late submissions will not be accepted.
* We will be downloading the code on the midnight before the due date, any changes to code after that point will not be considered for marking.

 
