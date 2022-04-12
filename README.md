# media-sass-project
Incorporating media queries and SASS to NICEPAGE template





 <img src="./img/car-photo13.jpg" alt="">

<img src="./img/red-car-photo1 (2).jpg" alt="">

10% 22.5% 22.5% 22.5% 22.5%;

<img src="./img/red-car-photo1 (2).jpg" alt="">

<div class="grid-item item1">
  
  </div>


<div class="section">
 <div class="container-2">
  <div class="grid-item item1">
  </div>
  <div class="grid-item item2">
    <img src="./img/red-car-photo1 (2).jpg" alt="">
  </div>
 </div>
</div>



// Container 4 //
.grid-container-4 > h1 {
   display: inline-block;
   height: 900px;
   border: 10px white;
   text-align:left;
   margin-left: 200px;
   margin-top: 140px;
   font-family: sans-serif;
   font-size: 100px;
   color: rgb(85, 81, 81);
}

.grid-container-4 > h1 > p {
   color: black;
   font-size: 50px;
   font-family: sans-serif;
   margin-top: 70px;
}

.grid-container-4 > h1 .p {
  color: rgb(88, 86, 86);
  margin: 0px;
  font-size: 25px;
}

.button {
  background-color: #0c0f0d; /* Black */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 22px;
  margin-top: 20px;
  height: 60px;
  width: 245px;

}


<section class="border">
<div class="grid-container-4">
  <div class="grid-item grid-item8"><img src="./img/girl-in-car-photo2.jpg" alt=""><div>
  <div class="grid-item grid-item9">item9</div>
  <div class="grid-item grid-item10"><h3>SEARCH 36,000+ CAR <br> RENTAL LOCATIONS <br> WORLDWIDE</h3><p>Lorem ipsum dolor sit amet <br> consectetur adipisicing elit. Delectus veritatis <br> dolor quaerat, laboriosam quibusdam.</p><button type="button" class="button">FIND CAR DEALS</button></div>
  <div class="grid-item grid-item11"><h5>CAR RENTAL</h5><h4>Service</h4><p>A regular service schedule can help keep your car running at <br> it's best. A regular service schedule can help keep your car running at it's best.</p></div>
  <div class="grid-item grid-item12" ><img src="./img/girl-in-car-photo1.jpg" alt=""></div>
</div>
</section>


.grid-container-4 {
         display: grid;
         grid-template-columns: 1fr 1fr 1fr 1fr; 
         grid-template-rows: 1fr 1fr 1fr 1fr;
         width: 30em;
         height: 800px;
         margin-left: 100px; 
         margin-top: 150px;
         border: 10px solid rgb(13, 9, 9);
         background-color: rgb(252, 247, 247); 
      }

      .grid-item8 {
         grid-column-start: 1;
         grid-column-end: 2;
         grid-row-start: 1;
         grid-row-end: 2;
         background-color: rgb(237, 224, 224); 
         margin:10px;
      }

      .grid-item9 {
         grid-column-start: 3;
         grid-column-end: 4;
         grid-row-start: 5;
         grid-row-end: -2;
         background-color: rgb(251, 246, 246); 
         text-align: center;
      }

      .grid-item10 {
         grid-column-start: 3;
         grid-column-end: 9;
         grid-row-start: 7;
         grid-row-end: 9;
         background-color: rgb(248, 236, 236); 
         text-align: center;
      }

      .grid-item11 {
         grid-column-start: 7;
         grid-column-end: 8;
         grid-row-start: 1;
         grid-row-end: 5;
         background-color: #fdfafa; 
         text-align: center;
      }

      .grid-item12 {
         grid-column-start: 7;
         grid-column-end: 8;
         grid-row-start: 1;
         grid-row-end: 5;
         background-color: #faf6f6; 
         text-align: center;
      }
   }


// Container 4 //
.grid-container-4 {
   display: grid;
   grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr; 
   grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
   height: 800px;
   width: auto; 
   background-color: white; 
   border: 10px solid black; 
}

.grid-item8 {
   grid-column-start: 1;
   grid-column-end: 4;
   grid-row-start: 1;
   grid-row-end: 4;
   background-color: white; 
   margin-right: 670px;

}

.grid-item9 { 
   grid-column-end: 5;
   grid-row-start: 3;
   grid-row-end: 6;
   background-color: white; 
   margin-right: 670px;

}

  .grid-item10 {
   grid-column-start: 6;
   grid-column-end: 7;
   grid-row-start: 1;
   grid-row-end: 5;
   background-color: white; 
   margin-right: 670px;

}

  .grid-item11 {
   grid-column-start: 7;
   grid-column-end: 8;
   grid-row-start: 1;
   grid-row-end: 5;
   background-color: rgb(130, 30, 30); 
   margin-right: 670px;

}

By default in the CSS box model, the width and height you assign to an element is applied only to the element's content box. If the element has any border or padding, this is then added to the width and height to arrive at the size of the box that's rendered on the screen. This means that when you set width and height, you have to adjust the value you give to allow for any border or padding that may be added. For example, if you have four boxes with width: 25%;, if any has left or right padding or a left or right border, they will not by default fit on one line within the constraints of the parent container.

The box-sizing property can be used to adjust this behavior:

content-box gives you the default CSS box-sizing behavior. If you set an element's width to 100 pixels, then the element's content box will be 100 pixels wide, and the width of any border or padding will be added to the final rendered width, making the element wider than 100px.
border-box tells the browser to account for any border and padding in the values you specify for an element's width and height. If you set an element's width to 100 pixels, that 100 pixels will include any border or padding you added, and the content box will shrink to absorb that extra width. This typically makes it much easier to size elements. box-sizing: border-box is the default styling that browsers use for the <table>, <select>, and <button> elements, and for <input> elements whose type is radio, checkbox, reset, button, submit, color, or search.
Note: It is often useful to set box-sizing to border-box to layout elements. This makes dealing with the sizes of elements much easier, and generally eliminates a number of pitfalls you can stumble on while laying out your content. On the other hand, when using position: relative or position: absolute, use of box-sizing: content-box allows the positioning values to be relative to the content, and independent of changes to border and padding sizes, which is sometimes desirable.

Syntax
box-sizing: border-box;
box-sizing: content-box;

/* Global values */
box-sizing: inherit;
box-sizing: initial;
box-sizing: revert;
box-sizing: revert-layer;
box-sizing: unset;
Copy to Clipboard
The box-sizing property is specified as a single keyword chosen from the list of values below.

Values
content-box
This is the initial and default value as specified by the CSS standard. The width and height properties include the content, but does not include the padding, border, or margin. For example, .box {width: 350px; border: 10px solid black;} renders a box that is 370px wide.

Here, the dimensions of the element are calculated as: width = width of the content, and height = height of the content. (Borders and padding are not included in the calculation.)

border-box
The width and height properties include the content, padding, and border, but do not include the margin. Note that padding and border will be inside of the box. For example, .box {width: 350px; border: 10px solid black;} renders a box that is 350px wide, with the area for content being 330px wide. The content box can't be negative and is floored to 0, making it impossible to use border-box to make the element disappear.

Here the dimensions of the element are calculated as: width = border + padding + width of the content, and height = border + padding + height of the content.

Formal definition
Initial value	content-box
Applies to	all elements that accept width or height
Inherited	no
Computed value	as specified
Animation type	discrete
Formal syntax
content-box | border-box
Examples
Box sizes with content-box and border-box
This example shows how different box-sizing values alter the rendered size of two otherwise identical elements.

HTML
<div class="content-box">Content box</div>
<br>
<div class="border-box">Border box</div>
Copy to Clipboard
CSS
div {
  width: 160px;
  height: 80px;
  padding: 20px;
  border: 8px solid red;
  background: yellow;
}

.content-box {
  box-sizing: content-box;
  /* Total width: 160px + (2 * 20px) + (2 * 8px) = 216px
     Total height: 80px + (2 * 20px) + (2 * 8px) = 136px
     Content box width: 160px
     Content box height: 80px */
}

.border-box {
  box-sizing: border-box;
  /* Total width: 160px
     Total height: 80px
     Content box width: 160px - (2 * 20px) - (2 * 8px) = 104px
     Content box height: 80px - (2 * 20px) - (2 * 8px) = 24px */
}
Copy to Clipboard
Result

Specifications
Specification
CSS Box Sizing Module Level 3
# box-sizing
Browser compatibility
Report problems with this compatibility data on GitHub
desktop	mobile
Chrome
Edge
Firefox
Internet Explorer
Opera
Safari
WebView Android
Chrome Android
Firefox for Android
Opera Android
Safari on iOS
Samsung Internet
box-sizing

10
footnote
Toggle history	
12
Toggle history	
49
Toggle history	
8
footnote
Toggle history	
7
Toggle history	
5.1
Toggle history	
4
footnote
Toggle history	
18
footnote
Toggle history	
49
Toggle history	
14
footnote
Toggle history	
6
Toggle history	
1.0
footnote
Toggle history
padding-box
Deprecated
Non-standard

No
Toggle history	
No
Toggle history	
1 – 50
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history	
4 – 50
Toggle history	
No
Toggle history	
No
Toggle history	
No
Toggle history
Legend
Full support
Full support
No support
No support
Non-standard. Check cross-browser support before using.
Deprecated. Not for use in new websites.
See implementation notes.
Requires a vendor prefix or different name for use.
See also
CSS box model
Found a problem with this page?
Edit on GitHub
Source on GitHub
Report a problem with this content on GitHub
Want to fix the problem yourself? See our Contribution guide.
Last modified: Apr 5, 2022, by MDN contributors

Your blueprint for a better internet.

MDN on Twitter
MDN on Github
MDN
About
Hacks Blog
Careers
Support
Product help
Report a page issue
Report a site issue
Our communities
MDN Community
MDN Forum
MDN Chat
Developers
Web Technologies
Learn Web Development
MDN Plus
Website Privacy Notice
Cookies
Legal
Community Participation Guidelines
Visit Mozilla Corporation’s not-for-profit parent, the Mozilla Foundation.
Portions of this content are ©1998–2022 by individual mozilla.org contributors. Content available under a Creative Commons license.







