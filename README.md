# xp stands for Xtra Power Tools
The aim of this respository is to provide 'tools' with xtra-power. 
1. xp.css:
A front-end developer needs to make every thing responsive as per different device sizes. Just imagine , they get a css library that takes care of every thing to go responsive in any device size - small phones to TVs. For Instance,
The size of text , buttons, images, cards, menu etc.

Why xp was created:
(a) Linking one CSS library ensures the responsiveness of all users. 
(b) Unlike bootstrap or other libraries, you can modify code of xp.css as per your project. You dont need to scratch your head.

2. xp-backened
Just imagine you only need to define lables and you get a code in PHP, RUST , JS, C++ , Phython etc in a click. ( Coming Soon).

3. xp-Websitecreator
Drag and Drop beautiful site maker. Its Scalable... Share your snippet with others or use their in your website. (Coming Soon).


# xp.css [xtra power css]
This CSS Library makes everything super responsive. It calculate device size and outputing topography , images, div size, cards, buttons etc as responsive. You don't need to write media queries for different devices. This Library is modified version of w3.css. However, lot of addition is done in w3.css to make give it xtra-power.

1. Fast 
2. One Css Library for drawing mobile, tablet, desktop and TV apps.
3. Similar syntax like Bootstrap css. Therefore, easy to implement.
4. Production Ready.
5. Responsive Topography is replaced with fluid topography.
6. Size of button changes with device size. 

## How to use xp.css:
Just download and link it or 
link it by github link: https://raw.githubusercontent.com/Manishfoodtechs/xp/main/xp.css

Here is demo on codepen:
<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>CodePen - super css</title>
  <link rel="stylesheet" href="https://raw.githubusercontent.com/Manishfoodtechs/xp/main/xp.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  <script src="xp.js"></script>

</head>
<body>
<!-- partial:index.partial.html -->
 <div><button class=" primary-btn-RT ">Submit</button></div>
 
 <p>I’ve covered the very useful vw and vh CSS units in a previous article, but the related vmin and vmax units are far less known and generally poorly understood. This is unfortunate, as the units have some truly novel use-cases in web development.

As I discussed earlier, 1vh is equal to 1% of the current viewport height (i.e. the open browser window), while 1vw is 1% of the current viewport width. vmin and vmax use those same units, but in response to particular rules:</p>
 
 
 
 
 <hr>
 
 <h2>Display Warnings</h2>
<p>The xp-panel class can be used to display warnings:</p>

<div class="xp-panel xp-pale-yellow xp-border">
  <h3>Warning!</h3>
  <p>Yellow often indicates a warning that might need attention.</p>
</div>

<div class="xp-panel xp-yellow xp-border">
  <h3>Warning!</h3>
  <p>Yellow often indicates a warning that might need attention.</p>
</div>
<hr>
 <div class="xp-container">
  <h2>Photo Card</h2>

  <div class="xp-card-4" style="width:50%">
    <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" alt="Alps" style="width:100%">
    <div class="xp-container xp-center">
      <p>The Italian / Austrian Alps</p>
    </div>
  </div>
</div>
<hr>
<div class="xp-container">
  <h2>List Header</h2>
  <p>An example of how to add a heading element inside the list item.</p>

  <ul class="xp-ul xp-border">
    <li><h2>Names</h2></li>
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
<hr>
<div class="xp-container">
  <h1>Background Colors</h1>
  <p>The xp-color classes defines background colors for HTML elements:</p>
</div>

<div class="xp-container xp-red">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

<div class="xp-container xp-teal">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

<div class="xp-container xp-yellow">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

<div class="xp-container xp-gray">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

<div class="xp-container xp-grey">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>
<hr>
<div class="xp-container">
<h1>Text Colors</h1>
<p>The xp-text-color classes defines text colors for HTML elements:</p>

  <div class="xp-text-red">
    <h2>London</h2>
    <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-text-blue">
    <h2>London</h2>
    <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

<hr>
<div class="xp-container">
<h1>Hover Colors</h1>

<p>Change the background color when hovering over an element:</p>
<div class="xp-container xp-orange xp-hover-red">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

</div>

 <hr>
 <div class="xp-container">
<h1>Hover Colors</h1>

<p>Change the text color when hovering over an element:</p>
<div class="xp-container xp-orange xp-hover-text-white">
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom, with a metropolitan area of over 9 million inhabitants.</p>
</div>

</div>
 <hr>
 <div> 
  <h2>Without a Container</h2>
  <p>The xp-container class is one of the most important xp.CSS classes.</p>
  <p>It provides correct margins, padding, alignments, and more, to most HTML elements.</p>
</div>

<div class="xp-container"> 
  <h2>With a Container</h2>
  <p>The xp-container class is one of the most important xp.CSS classes.</p>
  <p>It provides correct margins, padding, alignments, and more, to most HTML elements.</p>
</div>
 
 <hr>
 <div class="xp-container">
  <h2>Displaying Colors</h2>
  <p>The xp-color classes can be used to add colors to any HTML element.</p>
</div>

<div class="xp-container xp-red">
  <p>London is the capital city of England.</p>
</div>

 <hr>
 <div class="xp-container xp-teal">
  <h1>Header</h1>
</div>

<div class="xp-container">
  <p>The xp-container class can be used to display headers.</p>
</div>

 <hr>
 <header class="xp-container xp-teal">
  <h1>Header</h1>
</header>

<div class="xp-container">
  <p>The xp-container class can be used to display headers.</p>
</div>

 <hr>
 <div class="xp-container">
  <p>The xp-container class can be used to display footers.</p>
</div>

<div class="xp-container xp-teal">
  <h5>Footer</h5>
  <p>Footer information goes here</p>
</div>
 <hr>
 <div class="xp-container">
  <p>The xp-container class can be used to display footers.</p>
</div>

<footer class="xp-container xp-teal">
  <h5>Footer</h5>
  <p>Footer information goes here</p>
</footer>
 <hr>
 <div class="xp-container"> 
  <h2>London</h2>
  <p>London is the most populous city in the United Kingdom,
  with a metropolitan area of over 9 million inhabitants.</p>
  <hr>
</div>

<article class="xp-container"> 
  <h2>Paris</h2>
  <p>The Paris area is one of the largest population centers in Europe,
  with more than 2 million inhabitants.</p>
  <hr>
</article>

<section class="xp-container"> 
  <h2>Tokyo</h2>
  <p>Tokyo is the center of the Greater Tokyo Area,
  and the most populous metropolitan area in the world.</p>
  <hr>
</section>
<hr>

<img src="https://www.w3schools.com/w3css/img_car.jpg" alt="Car" style="width:100%">

<div class="xp-container">
  <p>A car is a wheeled, self-powered motor vehicle used for transportation. Most definitions of the term specify that cars are designed to run primarily on roads. (Wikipedia)</p>
</div>

<div class="xp-container xp-red">
  <h5>Footer</h5>
</div>
 <hr>
 <header class="xp-container xp-teal">
  <h1>Header</h1>
</header>

<img src="https://www.w3schools.com/w3css/img_car.jpg" alt="Car" style="width:100%">

<article class="xp-container">
  <p>A car is a wheeled, self-powered motor vehicle used for transportation. Most definitions of the term specify that cars are designed to run primarily on roads. (Wikipedia)</p>
</article>

<footer class="xp-container xp-teal">
  <h5>Footer</h5>
</footer>
 <hr>
 <div class="xp-container xp-blue">
  The xp-container class has a default 16px left and right padding, and no top or bottom padding.
</div>
 <hr>
 <div class="xp-container xp-blue">
  <h1>I am a Heading</h1>
  <p>I am a paragraph.</p>
  <p>Normally you will not have to change the default padding of a container, because paragraphs and heading provide margins that will simulate padding.</p>
</div>

 <hr>
 <div class="xp-container">
  <h2>Displaying Panels</h2>
  <p>Panels are the same as containers except for an added top and bottom margin.</p>

  <div class="xp-panel xp-red">
    <p>I am a panel.</p>
  </div>
  <div class="xp-panel xp-green">
    <p>I am a panel.</p>
  </div>

  <div class="xp-container xp-red">
    <p>I am a container.</p>
  </div>
  <div class="xp-container xp-green">
    <p>I am a container.</p>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Panels for Notes</h2>
  <p>The xp-panel class can be used to display notes:</p>

  <div class="xp-panel xp-pale-green">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

</div>
 <hr>
 <div class="xp-container">
  <h2>Panels for Quotes</h2>
  <p>The xp-panel class can be used to display quotes.</p>

  <div class="xp-panel xp-leftbar xp-sand xp-xxlarge xp-serif">
    <p><i>"Make it as simple as possible, but not simpler."</i></p>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Panels for Alerts</h2>
  <p>The xp-panel class can be used to display alerts:</p>

  <div class="xp-panel xp-red">
    <h3>Danger!</h3>
    <p>Red often indicates a dangerous or negative situation.</p>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Panels as Cards</h2>
  <p>The xp-panel class can be used to display cards:</p>
  
  <div class="xp-panel xp-blue xp-card-4">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Rounded Panels</h2>
  <div class="xp-panel xp-blue xp-round-xlarge">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

 <hr>
 <div class="xp-container">
  <h2>Hiding Panels</h2>
  <p>Hiding a panel can be done using an onclick event on a xp-button:</p>
</div>

<div class="xp-panel xp-red xp-display-container">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-red xp-large xp-display-topright">x</span>
  <p>Click on the X to close this panel.</p>
  <p>Click on the X to close this panel.</p>
</div>

 <hr>
 <button class="xp-button xp-red" onclick="document.getElementById('id01').style.display='block'">Show Panel</button> 

<div id="id01" class="xp-panel xp-green xp-display-container" style="display:none">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-red xp-display-topright">x</span>
  <p>Click on the X to close this panel.</p>
  <p>Click on the X to close this panel.</p>
</div>
 <hr>
 <div class="xp-container">
  <h2>Borders</h2>

  <div class="xp-panel xp-border">
    <p>I have borders.</p>
  </div>
  
  <div class="xp-panel xp-border-left">
    <p>I have only a left border.</p>
  </div>
  
  <div class="xp-panel xp-border-right">
    <p>I have only a right border.</p>
  </div>
  
  <div class="xp-panel xp-border-top xp-border-bottom">
    <p>I have top and bottom borders.</p>
  </div>

</div>

<hr>
<div class="xp-container">
  <h2>Border Colors</h2>

  <div class="xp-panel xp-border xp-border-red">
    <p>I have red borders.</p>
  </div>

  <div class="xp-panel xp-border-left xp-border-blue">
    <p>I have a blue left border.</p>
  </div>

  <div class="xp-panel xp-border-top xp-border-bottom xp-border-green">
    <p>I have a green top and bottom border.</p>
  </div>

  <div class="xp-panel xp-border-left xp-pale-red xp-border-red">
    <p>I have a red left border and a pale-red background color.</p>
  </div>

</div>
 <hr>
 <div class="xp-container">

  <h2>Borders</h2>
  <div class="xp-panel xp-border">
    <p>My borders are normal.</p>
  </div>
  
  <div class="xp-panel xp-border xp-round-small">
   <p>My borders are rounded (small).</p>
  </div>
  
  <div class="xp-panel xp-border xp-round">
    <p>My borders are rounded.</p>
  </div>

  <div class="xp-panel xp-border xp-round-large">
    <p>I have large rounded borders.</p>
  </div>

  <div class="xp-panel xp-border xp-round-xlarge">
    <p>I have xlarge rounded borders.</p>
  </div>

  <div class="xp-panel xp-border xp-round-xxlarge">
    <p>I have xxlarge rounded borders.</p>
  </div>

</div>
 <hr>
 <div class="xp-container">
  <h2>Thick Border Bars</h2>

  <div class="xp-panel xp-light-grey xp-leftbar">
    <p>I have a thick left border.</p>
  </div>
  
  <div class="xp-panel xp-light-grey xp-leftbar xp-border-grey">
    <p>I have a thick left border.</p>
  </div>
 
 <div class="xp-panel xp-leftbar xp-border-blue">
    <p>I have a thick blue left border.</p>
  </div>
 
  <div class="xp-panel xp-leftbar xp-border-blue xp-text-blue">
    <p>I have a thick blue left border.</p>
  </div>

  <div class="xp-panel xp-leftbar xp-border-red">
    <p>I have a thick red left border.</p>
  </div>
 
  <div class="xp-panel xp-leftbar xp-border-red xp-text-red">
    <p>I have a thick red left border.</p>
  </div>

  <div class="xp-panel xp-leftbar xp-border-blue xp-pale-blue">
    <p>I have a thick blue left border and a pale-blue background color.</p>
  </div>
 
  <div class="xp-panel xp-topbar xp-bottombar xp-border-red xp-pale-red">
    <p>I have a thick red top and bottom border and a pale-red background color.</p>
  </div>

  <div class="xp-panel xp-leftbar xp-border-green">
    <p>I have a thick green left border.</p>
  </div>
 
  <div class="xp-panel xp-leftbar xp-border-green xp-text-green">
    <p>I have a thick green left border.</p>
  </div>

  <div class="xp-panel xp-leftbar xp-border-yellow">
    <p>I have a thick yellow left border.</p>
  </div>
 
  <div class="xp-panel xp-leftbar xp-border-yellow xp-text-yellow">
    <p>I have a thick yellow left border.</p>
  </div>

</div>
 <hr>
 <div class="xp-container">
  <h2>Hoverable Borders</h2>

  <div class="xp-panel xp-border xp-hover-border-red">
    <p>Border that turns red on hover.</p>
  </div>
  
  <div class="xp-panel xp-border xp-border-red xp-hover-border-green">
    <p>Red border that turns green on hover.</p>
  </div>
</div>

 <hr>
 <div class="xp-container">
  <h2>Hoverable Borders</h2>

  <div class="xp-panel xp-leftbar xp-border-white xp-hover-border-green">
    <p>Thick white (invisible) left border that turns green on hover.</p>
  </div>

  <div class="xp-panel xp-light-grey xp-bottombar xp-border-white xp-hover-border-green">
    <p>Thick white (invisible) bottom border that turns green on hover.</p>
  </div>

</div>

 <hr>
 <div class="xp-container">
  <h2>Hoverable Borders</h2>

  <div style="border:16px solid white" class="xp-panel xp-hover-border-green">
    <p>Thick white (invisible) border that turns green on hover.</p>
  </div>

  <div style="border:16px solid white" class="xp-panel xp-hover-border-black">
    <p>Thick white (invisible) border that turns black on hover.</p>
  </div>

</div>

 <hr>
 <div class="xp-container">
  <h2>Cards</h2>
  <p>Create paper-like cards with the xp-card classes:</p>

  <div class="xp-panel xp-card"><p>xp-card</p></div>
  <div class="xp-panel xp-card-2"><p>xp-card-2</p></div>
  <div class="xp-panel xp-card-4"><p>xp-card-4</p></div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Yellow Cards</h2>
  <p>Create paper-like cards with the xp-card classes, and use a xp-color class to add a color:</p>

  <div class="xp-panel xp-card xp-yellow"><p>xp-card</p></div>
  <div class="xp-panel xp-card-2 xp-yellow"><p>xp-card-2</p></div>
  <div class="xp-panel xp-card-4 xp-yellow"><p>xp-card-4</p></div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Card Content</h2>
  <p>Add containers inside the card to create different sections:</p>

  <div class="xp-card-4" style="width:50%;">
    <header class="xp-container xp-blue">
      <h1>Header</h1>
    </header>

    <div class="xp-container">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </div>

    <footer class="xp-container xp-blue">
      <h5>Footer</h5>
    </footer>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Shadow on Hover</h2>
  <p>The xp-hover-shadow class adds a shadow effect on hover - this will make any element look like a "xp-card-4".</p>

  <div class="xp-green xp-hover-shadow xp-padding-64 xp-center" style="width:70%">
    <p>Hover over me to display me as a card!</p>
  </div>
</div>

 <hr>
 <div class="xp-container">
  <h2>Card Example</h2>

  <div class="xp-card-4 xp-dark-grey" style="width:50%">

    <div class="xp-container xp-center">
      <h3>Friend Request</h3>
      <img src="https://www.w3schools.com/w3css/img_avatar3.png" alt="Avatar" style="width:80%">
      <h5>John Doe</h5>

      <div class="xp-section">
        <button class="xp-button xp-green">Accept</button>
        <button class="xp-button xp-red">Decline</button>
      </div>
    </div>

  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Card Example</h2>

  <div class="xp-card-4" style="width:70%">
    <header class="xp-container xp-light-grey">
      <h3>John Doe</h3>
    </header>
    <div class="xp-container">
      <p>1 new friend request</p>
      <hr>
      <img src="https://www.w3schools.com/w3css/img_avatar3.png" alt="Avatar" class="xp-left xp-circle xp-margin-right" style="width:60px">
      <p>CEO at Mighty Schools. Marketing and Advertising. Seeking a new job and new opportunities.</p><br>
    </div>
    <button class="xp-button xp-block xp-dark-grey">+ Connect</button>
  </div>
</div>
 <hr>
 <div class="xp-card-4 xp-margin" style="width:50%">
  <div class="xp-display-container xp-text-white">
    <img src="https://www.w3schools.com/w3css/img_london.jpg" alt="Lights" style="width:100%">
    <div class="xp-xlarge xp-display-bottomleft xp-padding">LONDON 60&deg; F</div>
  </div>
  <div class="xp-row">
    <div class="xp-third xp-center">
      <h3>MON</h3>
      <img src="https://www.w3schools.com/w3css/img_weather_sun.jpg" alt="sun" style="width:80px">
    </div>
    <div class="xp-third xp-center">
      <h3>TUE</h3>
      <img src="https://www.w3schools.com/w3css/img_weather_cloud.jpg" alt="cloud" style="width:80px">
    </div>
    <div class="xp-third xp-center xp-margin-bottom">
      <h3>WED</h3>
      <img src="https://www.w3schools.com/w3css/img_weather_clouds.jpg" alt="clouds" style="width:80px">
    </div>
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>Round Classes</h2>

  <div class="xp-panel xp-round-small xp-teal">
    <p>xp-round-small</p>
  </div>

  <div class="xp-panel xp-round xp-teal">
    <p>xp-round</p>
  </div>

  <div class="xp-panel xp-round-large xp-teal">
    <p>xp-round-large</p>
  </div>

  <div class="xp-panel xp-round-xlarge xp-teal">
    <p>xp-round-xlarge</p>
  </div>

  <div class="xp-panel xp-round-xxlarge xp-teal">
    <p>xp-round-xxlarge</p>
  </div>
</div>

 <hr>
 <div class="xp-container">
  <h2>The xp-circle Class</h2>
  <img src="https://www.w3schools.com/w3css/img_car.jpg" class="xp-circle" alt="Car" style="width:400px">
</div>

 <hr>
 <div class="xp-padding-32 xp-red xp-circle xp-center">
  <h1>The xp-circle Class</h1>
</div>
 <hr>
 <div class="xp-container">
  <h2>A Circle in a Circle</h2>
  <div class="xp-padding-32 xp-green xp-circle">
    <img src="https://www.w3schools.com/w3css/img_car.jpg" class="xp-circle" style="width:75%">
  </div>
</div>
 <hr>
 <div class="xp-container">
  <h2>A Circle in a Circle</h2>
  <div class="xp-padding-32 xp-green xp-circle">
    <div class="xp-padding-32 xp-red xp-circle xp-center" style="width:55%">
      <p class="xp-xlarge">Hello<br>xp.CSS!</p>
    </div>
  </div>
</div>
 <hr>
 <div class="xp-container">

<div class="xp-panel xp-padding-16 xp-orange">
  <h4>xp-padding-16</h4>
  <p>I have 16px top and bottom padding</p>
</div>

<div class="xp-panel xp-padding-24 xp-orange">
  <h4>xp-padding-24</h4>
  <p>I have 24px top and bottom padding</p>
</div>

<div class="xp-panel xp-padding-32 xp-orange">
  <h4>xp-padding-32</h4>
  <p>I have 32px top and bottom padding</p>
</div>

<div class="xp-panel xp-padding-48 xp-orange">
  <h4>xp-padding-48</h4>
  <p>I have 48px top and bottom padding</p>
</div>

<div class="xp-panel xp-padding-64 xp-orange">
  <h4>xp-padding-64</h4>
  <p>I have 64px top and bottom padding</p>
</div>

</div>

  <hr>
  <div class="xp-container">

<div class="xp-panel xp-padding-small xp-blue">
<h4>xp-padding-small</h4>
<p>I have 4px top and bottom padding and 8px left and right padding.</p>
</div>

<div class="xp-panel xp-padding xp-blue">
<h4>xp-padding</h4>
<p>I have 8px top and bottom padding and 16px left and right padding.</p>
</div>

<div class="xp-panel xp-padding-large xp-blue">
<h4>xp-padding-large</h4>
<p>I have 12px top and bottom padding and 24px left and right padding.</p>
</div>

  <hr>
  <div class="xp-container">
  <h1>Using xp-margin</h1>

  <div class="xp-border">
    <div class="xp-container xp-margin xp-green">
      <p>The xp-margin class adds 16px margin to all sides of an element.</p>
    </div>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h1>Using xp-margin-top</h1>

  <div class="xp-border">
    <div class="xp-container xp-margin-top xp-green">
      <p>The xp-margin-top class adds a 16px top margin to an element.</p>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Using xp-margin-bottom</h1>

  <div class="xp-border">
    <div class="xp-container xp-margin-bottom xp-green">
      <p>The xp-margin-bottom class adds a 16px bottom margin to an element.</p>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Using xp-margin-left</h1>

  <div class="xp-border">
    <div class="xp-container xp-margin-left xp-green">
      <p>The xp-margin-left class adds a 16px left margin to an element.</p>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Using xp-margin-right</h1>

  <div class="xp-border">
    <div class="xp-container xp-margin-right xp-green">
      <p>The xp-margin-right class adds a 16px right margin to an element.</p>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Sections</h2>
  <p>The xp-section class adds a 16px top and bottom margin to any HTML element, and can be used to separate sections of HTML content:</p>
</div>
<div class="xp-container xp-blue">
  <h1>I am Blue</h1>
</div>
<div class="xp-container xp-green">
  <h1>I am Green</h1>
</div>

<div class="xp-container xp-section xp-blue">
  <h1>I am Blue</h1>
</div>
<div class="xp-container xp-section xp-green">
  <h1>I am Green</h1>
</div>

  <hr>
  <div class="xp-container">
  <h1>Using xp-display-container</h1>

  <div class="xp-display-container xp-green" style="height:300px;">
    <div class="xp-display-topleft">Top Left</div>
    <div class="xp-display-topright">Top Right</div>
    <div class="xp-display-bottomleft">Bottom Left</div>
    <div class="xp-display-bottomright">Bottom Right</div>
    <div class="xp-display-left">Left</div>
    <div class="xp-display-right">Right</div>
    <div class="xp-display-middle">Middle</div>
    <div class="xp-display-topmiddle xp-hide-small">Top Middle</div>
    <div class="xp-display-bottommiddle xp-hide-small">Bottom Middle</div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Using xp-display-container</h1>

  <div class="xp-display-container xp-green" style="height:300px;">
    <div class="xp-display-topleft xp-padding">Top Left</div>
    <div class="xp-display-topright xp-padding">Top Right</div>
    <div class="xp-display-bottomleft xp-padding">Bottom Left</div>
    <div class="xp-display-bottomright xp-padding">Bottom Right</div>
    <div class="xp-display-left xp-padding">Left</div>
    <div class="xp-display-right xp-padding">Right</div>
    <div class="xp-display-middle xp-padding">Middle</div>
    <div class="xp-display-topmiddle xp-padding xp-hide-small">Top Middle</div>
    <div class="xp-display-bottommiddle xp-padding xp-hide-small">Bottom Middle</div>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h1>The <strong>xp-display-container</strong> Class</h1>
  <p>Position of text inside an image</p>
  
  <div class="xp-display-container xp-text-white">
    <img src="https://www.w3schools.com/w3css/img_lights.jpg" alt="Lights" style="width:100%">
    <div class="xp-padding xp-display-topleft">Top Left</div>
    <div class="xp-padding xp-display-topright">Top Right</div>
    <div class="xp-padding xp-display-bottomleft">Bottom Left</div>
    <div class="xp-padding xp-display-bottomright">Bottom Right</div>
    <div class="xp-padding xp-display-topmiddle">Top Mid</div>
    <div class="xp-padding xp-display-left">Left</div>
    <div class="xp-padding xp-display-right">Right</div>
    <div class="xp-padding xp-display-middle xp-xxlarge">Middle</div>
    <div class="xp-padding xp-display-bottommiddle">Bottom Mid</div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>The <strong>xp-display-hover</strong> Class</h1>
  <p>The xp-display-hover class displays content on hover inside a xp-display-container (goes from hidden to shown).</p>
  
  <div class="xp-display-container xp-light-grey" style="height:300px;">
    <div class="xp-display-topleft xp-display-hover">Top Left</div>
    <div class="xp-display-topright xp-display-hover">Top Right</div>
    <div class="xp-display-bottomleft xp-display-hover">Bottom Left</div>
    <div class="xp-display-bottomright xp-display-hover">Bottom Right</div>
    <div class="xp-display-left xp-display-hover">Left</div>
    <div class="xp-display-right xp-display-hover">Right</div>
    <div class="xp-display-middle">Mouse over this box!</div>
    <div class="xp-display-topmiddle xp-display-hover">Top Mid</div>
    <div class="xp-display-bottommiddle xp-display-hover">Bottom Mid</div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>The <strong>xp-display-hover</strong> Class</h1>  
  <div class="xp-display-container xp-hover-opacity" style="width:50%">
    <img src="https://www.w3schools.com/w3css/img_avatar3.png" alt="Avatar" style="width:100%">
    <div class="xp-display-middle xp-display-hover xp-xlarge">
      <button class="xp-button xp-black">John Doe</button>
    </div>
  </div>
</div>

  <hr>
  <div class="xp-display-container xp-margin xp-card-4" style="height:200px;width:350px">
  <div class="xp-red xp-display-topleft" style="width:25%;height:40%"></div>
  <div class="xp-red xp-display-topright" style="width:60%;height:40%"></div>
  <div class="xp-red xp-display-bottomleft" style="width:25%;height:40%"></div>
  <div class="xp-red xp-display-bottomright" style="width:60%;height:40%"></div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Floating Classes</h2>
  <p>The xp-left class floats an element to the left, and the xp-right class floats an element to the right:</p>
  
  <div class="xp-bar xp-light-grey">
    <div class="xp-left xp-red xp-padding">xp-left</div>
    <div class="xp-right xp-blue xp-padding">xp-right</div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Show and Hide</h2>
  <p>The xp-hide class hides an element (display: none).</p>
  <p>The xp-show class shows an element (display: block).</p>
  <p class="xp-show">I am shown.</p>
  <p class="xp-hide">I am hidden.</p>
</div>
  <hr>
  <div class="xp-container">
  <h2>The xp-mobile Class</h2>
  <p>The <strong>xp-mobile</strong> class adds mobile-first responsivenss to any element.</p>
  <p>It adds display:block and width:100% to an element on screens that are less than 600px wide.</p>

  <p>Resize the browser window to see the effect:</p>
  <button class="xp-button xp-black xp-mobile">Home</button>
  <button class="xp-button xp-black xp-mobile">Link 1</button>
  <button class="xp-button xp-black xp-mobile">Link 2</button>
  <button class="xp-button xp-black xp-mobile">Link 3</button>
</div>
  <hr>
  <div class="xp-container">
  <h2>Buttons (xp-button)</h2>
  <input type="button" class="xp-button xp-black" value="Input Button">
  <button class="xp-button xp-black">Button Button</button>
  <a href="#" class="xp-button xp-black">Link Button</a>
</div>

<div class="xp-container">
  <h2>Buttons (xp-btn)</h2>
  <input type="button" class="xp-btn xp-black" value="Input Button">
  <button class="xp-btn xp-black">Button Button</button>
  <a href="#" class="xp-btn xp-black">Link Button</a>
</div>
  <hr>
  <div class="xp-container">
  <h2>Button Colors</h2>
  <p><button class="xp-button xp-red">Red</button></p>
  <p><button class="xp-button xp-pink">Pink</button></p>
  <p><button class="xp-button xp-purple">Purple</button></p>
  <p><button class="xp-button xp-deep-purple">Deep Purple</button></p>
  <p><button class="xp-button xp-indigo">Indigo</button></p>
  <p><button class="xp-button xp-blue">Blue</button></p>
  <p><button class="xp-button xp-light-blue">Light Blue</button></p>
  <p><button class="xp-button xp-cyan">Cyan</button></p>
  <p><button class="xp-button xp-aqua">Aqua</button></p>
  <p><button class="xp-button xp-teal">Teal</button></p>
  <p><button class="xp-button xp-green">Green</button></p>
  <p><button class="xp-button xp-light-green">Light Green</button></p>
  <p><button class="xp-button xp-lime">Lime</button></p>
  <p><button class="xp-button xp-sand">Sand</button></p>
  <p><button class="xp-button xp-khaki">Khaki</button></p>
  <p><button class="xp-button xp-yellow">Yellow</button></p>
  <p><button class="xp-button xp-amber">Amber</button></p>
  <p><button class="xp-button xp-orange">Orange</button></p>
  <p><button class="xp-button xp-deep-orange">Deep Orange</button></p>
  <p><button class="xp-button xp-brown">Brown</button></p>
  <p><button class="xp-button xp-blue-grey">Blue Grey</button></p>
  <p><button class="xp-button xp-light-grey">Light Grey</button></p>
  <p><button class="xp-button xp-grey">Grey</button></p>
  <p><button class="xp-button xp-dark-grey">Dark Grey</button></p>
  <p><button class="xp-button xp-black">Black</button></p>
  <p><button class="xp-button xp-pale-red">Pale-red</button></p>
  <p><button class="xp-button xp-pale-yellow">Pale-yellow</button></p>
  <p><button class="xp-button xp-pale-green">Pale-green</button></p>
  <p><button class="xp-button xp-pale-blue">Pale-blue</button></p>        
</div>

  <hr>
  <div class="xp-container">
  <h2>Hover Colors</h2>
  <p>Hover over the buttons to see the effect:</p>

  <p><button class="xp-button xp-border xp-hover-red">Red</button></p>
  <p><button class="xp-button xp-border xp-hover-pink">Pink</button></p>
  <p><button class="xp-button xp-border xp-hover-purple">Purple</button></p>
  <p><button class="xp-button xp-border xp-hover-deep-purple">Deep Purple</button></p>
  <p><button class="xp-button xp-border xp-hover-indigo">Indigo</button></p>
  <p><button class="xp-button xp-border xp-hover-blue">Blue</button></p>
  <p><button class="xp-button xp-border xp-hover-light-blue">Light Blue</button></p>
  <p><button class="xp-button xp-border xp-hover-cyan">Cyan</button></p>
  <p><button class="xp-button xp-border xp-hover-aqua">Aqua</button></p>
  <p><button class="xp-button xp-border xp-hover-teal">Teal</button></p>
  <p><button class="xp-button xp-border xp-hover-green">Green</button></p>
  <p><button class="xp-button xp-border xp-hover-light-green">Light Green</button></p>
  <p><button class="xp-button xp-border xp-hover-lime">Lime</button></p>
  <p><button class="xp-button xp-border xp-hover-sand">Sand</button></p>
  <p><button class="xp-button xp-border xp-hover-khaki">Khaki</button></p>
  <p><button class="xp-button xp-border xp-hover-yellow">Yellow</button></p>
  <p><button class="xp-button xp-border xp-hover-amber">Amber</button></p>
  <p><button class="xp-button xp-border xp-hover-orange">Orange</button></p>
  <p><button class="xp-button xp-border xp-hover-deep-orange">Deep Orange</button></p>
  <p><button class="xp-button xp-border xp-hover-brown">Brown</button></p>
  <p><button class="xp-button xp-border xp-hover-blue-grey">Blue Grey</button></p>
  <p><button class="xp-button xp-border xp-hover-light-grey">Light Grey</button></p>
  <p><button class="xp-button xp-border xp-hover-grey">Grey</button></p>
  <p><button class="xp-button xp-border xp-hover-dark-grey">Dark Grey</button></p>
  <p><button class="xp-button xp-border xp-hover-black">Black</button></p>
  <p><button class="xp-button xp-border xp-hover-pale-red">Pale-red</button></p>
  <p><button class="xp-button xp-border xp-hover-pale-yellow">Pale-yellow</button></p>
  <p><button class="xp-button xp-border xp-hover-pale-green">Pale-green</button></p>
  <p><button class="xp-button xp-border xp-hover-pale-blue">Pale-blue</button></p>        

</div>

  <hr>
  <div class="xp-container">
  <h2>Button Shapes</h2>
  <p><button class="xp-button xp-black xp-round-small">Round Small</button></p>
  <p><button class="xp-button xp-black xp-round">Round Normal</button></p>
  <p><button class="xp-button xp-black xp-round-large">Round Large</button></p>
  <p><button class="xp-button xp-black xp-round-xlarge">Round XLarge</button></p>
  <p><button class="xp-button xp-black xp-round-xxlarge">Round XXLarge</button></p>
</div>

  <hr>
  <div class="xp-container">
  <h2>Button Sizes</h2>

  <p><button class="xp-button xp-border xp-tiny">Tiny</button></p>
  <p><button class="xp-button xp-border xp-small">Small</button></p>
  <p><button class="xp-button xp-border xp-medium">Medium</button></p>
  <p><button class="xp-button xp-border xp-large">Large</button></p>
  <p><button class="xp-button xp-border xp-xlarge">XLarge</button></p>
  <p><button class="xp-button xp-border xp-xxlarge">XXLarge</button></p>
  <p><button class="xp-button xp-border xp-xxxlarge">XXXLarge</button></p>
  <p><button class="xp-button xp-border xp-jumbo">Jumbo</button></p>

  <p><button class="xp-btn xp-border xp-tiny">Tiny</button></p>
  <p><button class="xp-btn xp-border xp-small">Small</button></p>
  <p><button class="xp-btn xp-border xp-medium">Medium</button></p>
  <p><button class="xp-btn xp-border xp-large">Large</button></p>
  <p><button class="xp-btn xp-border xp-xlarge">XLarge</button></p>
  <p><button class="xp-btn xp-border xp-xxlarge">XXLarge</button></p>
  <p><button class="xp-btn xp-border xp-xxxlarge">XXXLarge</button></p>
  <p><button class="xp-btn xp-border xp-jumbo">Jumbo</button></p>

</div>

  <hr>
  <div class="xp-container">
<h2>Button Borders</h2>
<p>
  <button class="xp-button xp-white xp-border">Button</button>
  <button class="xp-button xp-yellow xp-border">Button</button>
  <button class="xp-button xp-white xp-border xp-round-large">Button</button>
  <button class="xp-button xp-white xp-border xp-border-red xp-round-large">Button</button>
</p>
<p>
  <button class="xp-btn xp-white xp-border">Button</button>
  <button class="xp-btn xp-yellow xp-border">Button</button>
  <button class="xp-btn xp-white xp-border xp-round-large">Button</button>
  <button class="xp-btn xp-white xp-border xp-border-red xp-round-large">Button</button>
</p>
</div>

  <hr>
  <div class="xp-container">
<h2>Buttons with wider text</h2>
<p>
  <button class="xp-button xp-black">Normal</button>
  <button class="xp-button xp-black xp-wide">Wide</button>
</p>
<p>
  <button class="xp-btn xp-black">Normal</button>
  <button class="xp-btn xp-black xp-wide">Wide</button>
</p>
</div>
  <hr>
  <div class="xp-container">
<h2>Buttons with Text Effects</h2>
<p>
  <button class="xp-button xp-black">Normal</button>
  <button class="xp-button xp-black"><i>Italic</i></button>
  <button class="xp-button xp-black"><b>Bold</b></button>
</p>
<p>
  <button class="xp-btn xp-black">Normal</button>
  <button class="xp-btn xp-black"><i>Italic</i></button>
  <button class="xp-btn xp-black"><b>Bold</b></button>
</p>
</div>
  <hr>
  <div class="xp-container">
<h2>Buttons With Extra Padding</h2>
<p>
  <button class="xp-button xp-black xp-padding-small">Button</button>
  <button class="xp-button xp-black">Button</button>
  <button class="xp-button xp-black xp-padding-large">Button</button>
</p>
<p>
  <button class="xp-btn xp-black xp-padding-small">Button</button>
  <button class="xp-btn xp-black">Button</button>
  <button class="xp-btn xp-black xp-padding-large">Button</button>
</p>
</div>
  <hr>
  <div class="xp-panel">
  <h2>Buttons as Blocks (xp-button)</h2>
  <button class="xp-button xp-block xp-black">Button</button>
  <p>The size of the block can be defined using <strong>style="width:"</strong>.</p>
</div>

<div class="xp-panel" style="width:30%">
  <button class="xp-button xp-block xp-black">Button</button>
</div>

<div class="xp-panel" style="width:50%">
  <button class="xp-button xp-block xp-teal">Button</button>
</div>

<div class="xp-panel" style="width:80%">
  <button class="xp-button xp-block xp-red xp-right-align">Button</button>
</div>

<div class="xp-panel">
  <h2>Buttons as Blocks (xp-button)</h2>
  <button class="xp-btn xp-block">Button</button>
</div>

<div class="xp-panel" style="width:30%">
  <button class="xp-btn xp-block">Button</button>
</div>

<div class="xp-panel" style="width:50%">
  <button class="xp-btn xp-block xp-teal">Button</button>
</div>

<div class="xp-panel" style="width:80%">
  <button class="xp-btn xp-block xp-red xp-right-align">Button</button>
</div>
  <hr>
  <div class="xp-container">
  <h2>Disabled Buttons (xp-button)</h2>
  
  <p>Link buttons:</p>
  <a class="xp-button xp-black" href="#">Link Button</a>  
  <a class="xp-button xp-black xp-disabled" href="#">Link Button</a>
  
  <p>Button buttons:</p>  
  <button class="xp-button xp-teal">Button</button>
  <button class="xp-button xp-teal" disabled>Button</button>
  
  <p>Input buttons:</p>    
  <input type="button" class="xp-button xp-red" value="Input Button">
  <input type="button" class="xp-button xp-red" value="Input Button" disabled>

  <h2>Disabled Buttons (xp-btn)</h2>
  
  <p>Link buttons:</p>
  <a class="xp-btn xp-black" href="#">Link Button</a>  
  <a class="xp-btn xp-black xp-disabled" href="#">Link Button</a>
  
  <p>Button buttons:</p>  
  <button class="xp-btn xp-teal">Button</button>
  <button class="xp-btn xp-teal" disabled>Button</button>
  
  <p>Input buttons:</p>    
  <input type="button" class="xp-btn xp-red" value="Input Button">
  <input type="button" class="xp-btn xp-red" value="Input Button" disabled>
</div>

  <hr>
  <div class="xp-container">
<h2>Button Bars</h2>
<p>Buttons can be grouped together in a horizontal bar using the <strong>xp-bar</strong> class:</p>
<div class="xp-bar">
  <button class="xp-button xp-black">Button</button>
  <button class="xp-button xp-teal">Button</button>
  <button class="xp-button xp-red">Button</button>
</div>
</div>
  <hr>
  <div class="xp-container">
<h2>Button Bars</h2>
<p>Buttons can be grouped together without a space between them by using <strong>xp-bar-item</strong> class:</p>
<div class="xp-bar">
  <button class="xp-bar-item xp-button xp-black">Button</button>
  <button class="xp-bar-item xp-button xp-teal">Button</button>
  <button class="xp-bar-item xp-button xp-red">Button</button>
</div>

</div>
  <hr>
  <div class="xp-container xp-center">
<h2>Button Bars</h2>
<p>Buttons bars can be centered using the <strong>xp-center</strong> class:</p>
<div class="xp-bar">
  <button class="xp-button xp-black">Button</button>
  <button class="xp-button xp-teal">Button</button>
  <button class="xp-button xp-red">Button</button>
</div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Button Bars</h2>

  <p>Two button groups on the same line (if enough space):</p>
  <div class="xp-show-inline-block">
  <div class="xp-bar">
    <button class="xp-button xp-black">Button</button>
    <button class="xp-button xp-teal">Button</button>
    <button class="xp-button xp-red">Button</button>
  </div>
  </div>
  <div class="xp-show-inline-block">
  <div class="xp-bar">
    <button class="xp-button xp-black">Button</button>
    <button class="xp-button xp-teal">Button</button>
    <button class="xp-button xp-red">Button</button>
  </div>
  </div>

  <p>Two button groups on the same line (if enough space):</p>
  <div class="xp-show-inline-block">
  <div class="xp-bar">
    <button class="xp-bar-item xp-button xp-black">Button</button>
    <button class="xp-bar-item xp-button xp-teal">Button</button>
    <button class="xp-bar-item xp-button xp-red">Button</button>
  </div>
  </div>
  <div class="xp-show-inline-block">
  <div class="xp-bar">
    <button class="xp-bar-item xp-button xp-black">Button</button>
    <button class="xp-bar-item xp-button xp-teal">Button</button>
    <button class="xp-bar-item xp-button xp-red">Button</button>
  </div>
  </div>
</div>

  <hr>
  <div class="xp-container">
<h2>Button Bars</h2>
<p>Buttons bars can easily be used as navigation bars:</p>

<div class="xp-bar xp-black">
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
</div>
<br>
<div class="xp-bar xp-border">
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
</div>
<br>
<div class="xp-bar xp-green">
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
</div>
<br>
<div class="xp-bar xp-red">
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
</div>
<br>
<div class="xp-bar xp-teal">
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
<button class="xp-bar-item xp-button">Button</button>
</div>

</div>

  <hr>
  <div class="xp-container">
<h2>Button Bars</h2>
<p>The size of each items can be defined by using <strong>style="width:"</strong>:</p>
<div class="xp-bar">
  <button class="xp-bar-item xp-button xp-black" style="width:33.3%">Button</button>
  <button class="xp-bar-item xp-button xp-teal" style="width:33.3%">Button</button>
  <button class="xp-bar-item xp-button xp-red" style="width:33.3%">Button</button>
</div>

  <hr>
  <div class="xp-container">
<h2>Left and Right Buttons</h2>
<div class="xp-bar xp-black">
  <button class="xp-button xp-left">Left</button>
  <button class="xp-button xp-right">Right</button>
</div>

<p>Used to create "previous/next" buttons:</p>
<div class="xp-bar">
  <button class="xp-button xp-left xp-light-grey">&laquo; Previous</button>
  <button class="xp-button xp-right xp-green">Next &raquo;</button>
</div>
</div>
  <hr>
  <div class="xp-container">

<h2>Buttons with Ripple Effect</h2>
<p>Click on the buttons to see the effect:</p>
<p>
  <button class="xp-button xp-ripple xp-black">Button</button>
  <button class="xp-button xp-ripple xp-red">Button</button>
  <button class="xp-button xp-ripple xp-yellow">Button</button>
</p>
<p>
  <button class="xp-btn xp-ripple xp-black">Button</button>
  <button class="xp-btn xp-ripple xp-red">Button</button>
  <button class="xp-btn xp-ripple xp-yellow">Button</button>
</p>
</div>
  <hr>
  <div class="xp-container">
  <h2>Circular Buttons</h2>
  <button class="xp-button xp-xlarge xp-circle xp-black">+</button>
  <button class="xp-button xp-xlarge xp-circle xp-teal">+</button>
  <button class="xp-button xp-xlarge xp-circle xp-red xp-card-4">+</button>
</div>

  <hr>
  <div class="xp-container">
  <h2>Square Buttons</h2>
  <button class="xp-button xp-xlarge xp-black">+</button>
  <button class="xp-button xp-xlarge xp-teal">+</button>
  <button class="xp-button xp-xlarge xp-red xp-card-4">+</button>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Notes</h2>
  <p>The xp-panel class can be used to display all sorts of notes:</p>

  <div class="xp-panel xp-yellow">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-border">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-light-grey xp-border xp-round">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-pale-blue xp-leftbar xp-border-blue">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-pale-red xp-leftbar xp-rightbar xp-border-red">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-pale-yellow xp-topbar xp-bottombar xp-border-yellow">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-pale-green xp-bottombar xp-border-green xp-border">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>

  <div class="xp-panel xp-yellow xp-bottombar xp-border-amber">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-border xp-light-grey xp-round-large">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-pale-blue xp-leftbar xp-rightbar xp-border-blue">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-pale-red xp-leftbar xp-border-red">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-pale-yellow xp-border xp-border-yellow">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-pale-green xp-bottombar xp-border-green xp-border">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <div class="xp-panel xp-yellow xp-topbar xp-bottombar xp-border-amber">
    <p>London is the most populous city in the United Kingdom,
    with a metropolitan area of over 9 million inhabitants.</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Quotes</h2>
  <p>The xp-panel class can be used to display quotes:</p>

  <div class="xp-panel xp-leftbar xp-light-grey">
    <p class="xp-xlarge xp-serif"><i>"Make it as simple as possible, but not simpler."</i></p>
    <p>Albert Einstein</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Large Quotes</h2>
  <p>The xp-panel class can be used to display quotes:</p>

  <div class="xp-panel xp-leftbar xp-sand">
    <p class="xp-xxlarge xp-serif"><i>"Make it as simple as possible, but not simpler."</i></p>
    <p>Albert Einstein</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Displaying Blockquotes</h2>
  <p>The xp-panel class can be used to display blockquotes:</p>

  <blockquote class="xp-panel xp-leftbar xp-light-grey">
    <p class="xp-large"><i>"Make it as simple as possible, but not simpler."</i></p>
    <p>Albert Einstein</p>
  </blockquote> 
</div>
  <hr>
  <div class="xp-container">
  <h1>Quotes with HTML Symbols</h1>

  <div class="xp-panel xp-light-grey">
    <span style="font-size:150px;line-height:0.6em;opacity:0.2">❝</span>
    <p class="xp-xlarge" style="margin-top:-40px"><i>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper.
    Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</i></p>
  </div>

  <div class="xp-panel xp-light-grey">
    <span style="font-size:100px;line-height:0.6em">✂</span>
    <p class="xp-xlarge"><i>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper.
    Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</i></p>
</div>

</div>

  <hr>
  <div class="xp-panel xp-center xp-leftbar xp-sand">
<p><i class="xp-serif xp-xlarge">
<span style="font-size:150px;line-height:0.6em;opacity:0.2">✔</span>
Programming in C will slowly decline.<br>
Programming in JavaScript will be more important.</i></p>
</div>
  <hr>
  <div class="xp-container">
  <h1>Quotes with Font Awesome Symbols</h1>

  <div class="xp-panel xp-leftbar">
    <p><i class="fa fa-quote-right xp-xxlarge"></i><br>
    <i class="xp-serif xp-xlarge">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper. Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</i></p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Quotes with Font Awesome Symbols</h1>

  <div class="xp-panel xp-sand xp-leftbar">
    <p><i class="fa fa-quote-right xp-xxlarge xp-opacity"></i><br>
    <i class="xp-serif xp-xlarge">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper. Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</i></p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Quotes Example</h1>

  <div class="xp-panel xp-black">
    <p class="xp-large xp-serif">
    <i class="fa fa-quote-right xp-xxlarge xxp-margin-right"></i>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa
    vitae risus fermentum ullamcorper. Phasellus risus urna, ornare in aliquam
    id, porttitor sit amet sapien. Nulla facilisi.</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Quote as Card</h1>

  <div class="xp-panel xp-card-4 xp-light-grey" style="width:50%">
    <p class=" xp-large xp-serif">
    <i class="fa fa-quote-right xp-xxlarge xp-text-red"></i><br>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper. Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h1>Quote as Card</h1>

  <div class="xp-panel xp-card-4 xp-center" style="width:50%">
    <span style="font-size:100px">❝</span><br>
    <p style="margin-top:-60px"><i><b>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut non massa vitae risus fermentum ullamcorper. Phasellus risus urna, ornare in aliquam id, porttitor sit amet sapien. Nulla facilisi.</b></i></p>
  </div>
</div>
  <hr>
  <h2>Display Alerts</h2>
<p>The w3-panel class can be used to display alerts:</p>

<div class="w3-panel w3-pale-red w3-border">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-red">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>
  <hr>
  <h2>Display Warnings</h2>
<p>The xp-panel class can be used to display warnings:</p>

<div class="xp-panel xp-pale-yellow xp-border">
  <h3>Warning!</h3>
  <p>Yellow often indicates a warning that might need attention.</p>
</div>

<div class="xp-panel xp-yellow xp-border">
  <h3>Warning!</h3>
  <p>Yellow often indicates a warning that might need attention.</p>
</div>
  <hr>
  <h2>Display Success</h2>
<p>The xp-panel class can be used to display success:</p>

<div class="xp-panel xp-pale-green xp-border">
  <h3>Success!</h3>
  <p>Green often indicates something successful or positive.</p>
</div>

<div class="xp-panel xp-green">
  <h3>Success!</h3>
  <p>Green often indicates something successful or positive.</p>
</div>

  <hr>
  <h2>Display Information</h2>
<p>The xp-panel class can be used to display information:</p>

<div class="xp-panel xp-pale-blue xp-border">
  <h3>Information!</h3>
  <p>Blue often indicates a neutral informative change or action.</p>
</div>

<div class="xp-panel xp-blue">
  <h3>Information!</h3>
  <p>Blue often indicates a neutral informative change or action.</p>
</div>
  <hr>
  <h2>Displaying Alerts</h2>
<p>The xp-container class can also be used to display alerts:</p>

<div class="xp-container xp-red">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or potentially negative action.</p>
</div>

<div class="xp-container xp-yellow">
  <h3>Warning!</h3>
  <p>Yellow or orange often indicates a warning that might need attention.</p>
</div>

<div class="xp-container xp-green">
  <h3>Success!</h3>
  <p>Green often indicates something successful or positive.</p>
</div>

<div class="xp-container xp-blue">
  <h3>Info!</h3>
  <p>Blue often indicates a neutral informative change or action.</p>
</div>

  <hr>
  <h2>Display Alerts</h2>
<p>The xp-panel class can be used to display alerts:</p>

<div class="xp-panel xp-pink">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-orange">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-blue-grey">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-deep-orange">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-black">
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>
  <hr>
  <h2>Closing Alerts</h2>
<p>To close the alerts, click on the X in the upper right corner:</p>

<div class="xp-panel xp-red xp-display-container">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-large xp-display-topright">&times;</span>
  <h3>Danger!</h3>
  <p>Red often indicates a dangerous or negative situation.</p>
</div>

<div class="xp-panel xp-yellow xp-display-container">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-large xp-display-topright">&times;</span>
  <h3>Warning!</h3>
  <p>Yellow often indicates a warning that might need attention.</p>
</div>

<div class="xp-panel xp-green xp-display-container">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-large xp-display-topright">&times;</span>
  <h3>Success!</h3>
  <p>Green often indicates something successful or positive.</p>
</div>

<div class="xp-panel xp-blue xp-display-container">
  <span onclick="this.parentElement.style.display='none'"
  class="xp-button xp-large xp-display-topright">&times;</span>
  <h3>Info!</h3>
  <p>Blue often indicates a neutral informative change or action.</p>
</div>
  <hr>
  <h2>Rounded Alerts</h2>
<p>Use the xp-round classes if you want rounded alerts:</p>

<div class="xp-panel xp-green xp-round">
  <h3>Success!</h3>
  <p>Here xp-round is used.</p>
</div>

<div class="xp-panel xp-green xp-round-large">
  <h3>Success!</h3>
  <p>Here xp-round-large is used.</p>
</div>

<div class="xp-panel xp-green xp-round-xxlarge">
  <h3>Success!</h3>
  <p>Here xp-round-xxlarge is used.</p>
</div>

<div class="xp-panel xp-pale-green xp-round xp-border">
  <h3>Success!</h3>
  <p>Here xp-round is used.</p>
</div>

<div class="xp-panel xp-pale-green xp-round-large xp-border">
  <h3>Success!</h3>
  <p>Here xp-round-large is used.</p>
</div>

<div class="xp-panel xp-pale-green xp-round-xxlarge xp-border">
  <h3>Success!</h3>
  <p>Here xp-round-xxlarge is used.</p>
</div>
  <hr>
  <h2>Alert as a Card</h2>
<p>Use the xp-card classes to display an alert as a card:</p>

<div class="xp-panel xp-pale-yellow xp-card">
  <p>xp-card</p>
</div>

<div class="xp-panel xp-pale-yellow xp-card-4">
  <p>xp-card-4</p>
</div>
<div class="xp-panel xp-yellow xp-card">
  <p>xp-card</p>
</div>

<div class="xp-panel xp-yellow xp-card-4">
  <p>xp-card-4</p>
</div>
  <hr>
  <div class="xp-container">
  <h2>Basic Table</h2>
  <p>The xp-table class defines a basic table:</p>

  <table class="xp-table">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Striped Table</h2>
  <p>The xp-striped class adds zebra-stripes to a table:</p>

  <table class="xp-table xp-striped">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Bordered Table</h2>
  <p>The xp-bordered class adds a bottom border to each table row:</p>

  <table class="xp-table xp-bordered">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Striped Bordered Table</h2>

  <table class="xp-table xp-striped xp-bordered">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Border Around Table</h2>
  <p>The xp-border class adds a border around the table.</p>

  <table class="xp-table xp-striped xp-border">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Table All</h2>
  <p>The xp-table-all class combines the xp-table, xp-bordered, xp-striped, and 
  xp-border classes:</p>

  <table class="xp-table-all">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
    <tr>
      <td>Bo</td>
      <td>Nilson</td>
      <td>35</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Flipped Stripes</h2>
  <p>To flip the zebra-stripes, add thead around the table header:</p>

  <table class="xp-table-all">
    <thead>
      <tr class="xp-light-grey">
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
      </tr>
    </thead>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
    <tr>
      <td>Bo</td>
      <td>Nilson</td>
      <td>35</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Centering Content in Table</h2>

  <table class="xp-table-all xp-centered">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
    <tr>
      <td>Bo</td>
      <td>Nilson</td>
      <td>35</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Centering a Column</h2>

  <table class="xp-table-all">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th class="xp-center">Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td class="xp-center">50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td class="xp-center">94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td class="xp-center">67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Right Align a Column</h2>

  <table class="xp-table-all">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th class="xp-right-align">Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td class="xp-right-align">50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td class="xp-right-align">94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td class="xp-right-align">67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Hoverable Table</h2>

  <table class="xp-table-all xp-hoverable">
    <thead>
      <tr class="xp-light-grey">
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
      </tr>
    </thead>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Table With Different Hover Colors</h2>
  <p>If you different hover colors, add xp-hover-<em>color</em> classes to each tr element:</p>

  <table class="xp-table-all">
    <thead>
      <tr class="xp-light-grey xp-hover-red">
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
      </tr>
    </thead>
    <tr class="xp-hover-green">
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr class="xp-hover-blue">
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr class="xp-hover-black">
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
    <tr class="xp-hover-text-green">
      <td>Bo</td>
      <td>Nilson</td>
      <td>35</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Colored Table Heading</h2>
  <p>Use any of the xp-<em>color</em> classes to display a colored row:</p>

  <table class="xp-table-all">
    <thead>
      <tr class="xp-red">
        <th>First Name</th>
        <th>Last Name</th>
        <th>Points</th>
      </tr>
    </thead>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Colored Table</h2>
  <p>Use any of the <em>xp-color</em> classes to display a colored table:</p>

  <table class="xp-table xp-blue">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">

<h2>Responsive Table</h2>
<div class="xp-responsive">
<table class="xp-table-all">
<tr>
  <th>First Name</th>
  <th>Last Name</th>
  <th>Points</th>
  <th>Points</th>
  <th>Points</th>
  <th>Points</th>
  <th>Points</th>
  <th>Points</th>
  <th>Points</th>
</tr>
<tr>
  <td>Jill</td>
  <td>Smith</td>
  <td>50</td>
  <td>50</td>
  <td>50</td>
  <td>50</td>
  <td>50</td>
  <td>50</td>
  <td>50</td>
</tr>
<tr>
  <td>Eve</td>
  <td>Jackson</td>
  <td>94</td>
  <td>94</td>
  <td>94</td>
  <td>94</td>
  <td>94</td>
  <td>94</td>
  <td>94</td>
</tr>
<tr>
  <td>Adam</td>
  <td>Johnson</td>
  <td>67</td>
  <td>67</td>
  <td>67</td>
  <td>67</td>
  <td>67</td>
  <td>67</td>
  <td>67</td>
</tr>
</table>
</div>

<div class="xp-panel xp-red">
  <p>A responsive table will display a horizontal scroll bar if the screen is too small to display the full content.</p>
  <p>Resize the screen to see the effect.</p>
</div>

</div>

<hr>
<div class="xp-container">
  <h2>Table as a Card</h2>
  <p>The xp-card-* classes makes the table look like a card (adds shadows):</p>

  <table class="xp-table-all xp-card-4">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Tiny Table</h2>
  <p>The xp-tiny class creates a tiny table:</p>

  <table class="xp-table-all xp-tiny">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Small Table</h2>
  <p>The xp-small class creates a small table:</p>

  <table class="xp-table-all xp-small">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Large Table</h2>
  <p>The xp-large class creates a large table:</p>

  <table class="xp-table-all xp-large">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>XLarge Table</h2>
  <p>The xp-xlarge class creates an extra large table:</p>

  <table class="xp-table-all xp-xlarge">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>XXLarge Table</h2>
  <p>The xp-xxlarge class creates an extra extra large table:</p>

  <table class="xp-table-all xp-xxlarge">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>XXXLarge Table</h2>
  <p>The xp-xxxlarge class creates an XXXlarge table:</p>

  <table class="xp-table-all xp-xxxlarge">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
      <th>Points</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>94</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
      <td>67</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Jumbo Table</h2>
  <p>The xp-jumbo class creates an enormous "jumbo" table:</p>

  <table class="xp-table-all xp-jumbo">
    <tr>
      <th>First Name</th>
      <th>Last Name</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
    </tr>
    <tr>
      <td>Adam</td>
      <td>Johnson</td>
    </tr>
  </table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Basic List</h2>
  <p>The xp-ul class creates a basic list:</p>
  <ul class="xp-ul">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Bordered List</h2>
  <p>The xp-border class adds a border around the list:</p>
  <ul class="xp-ul xp-border">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>List Header</h2>
  <p>An example of how to add a heading element inside the list item.</p>

  <ul class="xp-ul xp-border">
    <li><h2>Names</h2></li>
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>

  <hr>
  <div class="xp-container">
  <h2>List as a Card</h2>
  <p>The xp-card class makes the list look like a card:</p>
  <ul class="xp-ul xp-card" style="width:50%">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
  <br>

  <p>More shadows:</p>
  <ul class="xp-ul xp-card-4" style="width:50%">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>

  <hr>
  <div class="xp-container">
  <h2>Centered List</h2>
  <p>The xp-center class centers the list items:</p>
  <ul class="xp-ul xp-center">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Colored List</h2>
  <p>Use any xp-color class to add a color to the list:</p>
  <ul class="xp-ul xp-red">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Colored List Item</h2>
  <p>Use any xp-color class to add a color to the list or list items:</p>
  <ul class="xp-ul">
    <li class="xp-blue">Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Hoverable List</h2>
  <p>The xp-hoverable class adds a grey background color to all list items when you mouse over them:</p>
  <ul class="xp-ul xp-hoverable">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Hoverable List</h2>
  <p>If you want a specific hover color, add any of the xp-hover-classes to each li element:</p>
  <ul class="xp-ul">
    <li class="xp-hover-red">Jill</li>
    <li class="xp-hover-green">Eve</li>
    <li class="xp-hover-blue">Adam</li>
    <li class="xp-hover-black">Bo</li>
    <li class="xp-hover-orange">Anja</li>
  </ul>
</div>

  <hr>
  <div class="xp-container">
  <h2>Closable List Items</h2>
  <p>To close/hide the list items, click on the "x":</p>
  <ul class="xp-ul xp-card-4">
    <li class="xp-display-container">Jill <span onclick="this.parentElement.style.display='none'" class="xp-button xp-transparent xp-display-right">&times;</span></li>
    <li class="xp-display-container">Adam <span onclick="this.parentElement.style.display='none'" class="xp-button xp-transparent xp-display-right">&times;</span></li>
    <li class="xp-display-container">Eve <span onclick="this.parentElement.style.display='none'" class="xp-button xp-transparent xp-display-right">&times;</span></li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Padded List</h2>
  <p>Use any of the xp-padding classes to increase or decrease the padding of each list item:</p>

  <p>Padding Small:
  <ul class="xp-ul xp-border" style="width:50%">
    <li class="xp-padding-small">Jill</li>
    <li class="xp-padding-small">Eve</li>
    <li class="xp-padding-small">Adam</li>
  </ul>

  <p>Default:</p>
  <ul class="xp-ul xp-border" style="width:50%">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>

  <p>Padding Large:</p>
  <ul class="xp-ul xp-border" style="width:50%">
    <li class="xp-padding-large">Jill</li>
    <li class="xp-padding-large">Eve</li>
    <li class="xp-padding-large">Adam</li>
  </ul> 
</div>

  <hr>
  <div class="xp-container">
  <h2>Avatar List</h2>
  <p>You can combine xp-ul and the xp-bar classes to create an avatar list:</p>
  <ul class="xp-ul xp-card-4">
    <li class="xp-bar">
      <span onclick="this.parentElement.style.display='none'" class="xp-bar-item xp-button xp-white xp-xlarge xp-right">×</span>
      <img src="https://www.w3schools.com/w3css/img_avatar2.png" class="xp-bar-item xp-circle xp-hide-small" style="width:85px">
      <div class="xp-bar-item">
        <span class="xp-large">Mike</span><br>
        <span>Web Designer</span>
      </div>
    </li>

    <li class="xp-bar">
      <span onclick="this.parentElement.style.display='none'" class="xp-bar-item xp-button xp-white xp-xlarge xp-right">×</span>
      <img src="https://www.w3schools.com/w3css/img_avatar5.png" class="xp-bar-item xp-circle xp-hide-small" style="width:85px">
      <div class="xp-bar-item">
        <span class="xp-large">Jill</span><br>
        <span>Support</span>
      </div>
    </li>

    <li class="xp-bar">
      <span onclick="this.parentElement.style.display='none'" class="xp-bar-item xp-button xp-white xp-xlarge xp-right">×</span>
      <img src="https://www.w3schools.com/w3css/img_avatar6.png" class="xp-bar-item xp-circle xp-hide-small" style="width:85px">
      <div class="xp-bar-item">
        <span class="xp-large">Jane</span><br>
        <span>Accountant</span>
      </div>
    </li>
  </ul>
</div>

  <hr>
  <h2>xp.CSS Lists</h2>
<p>Lists have a 100% width by default. Use the width property to change this:</p>

<p>Default:</p>
<ul class="xp-ul xp-border">
  <li>Jill</li>
  <li>Adam</li>
</ul>

<p>30% width:</p>
<ul class="xp-ul xp-border" style="width:30%">
  <li>Jill</li>
  <li>Adam</li>
</ul>

<p>50% width:</p>
<ul class="xp-ul xp-border" style="width:50%">
  <li>Jill</li>
  <li>Adam</li>
</ul>

<p>80% width:</p>
<ul class="xp-ul xp-border" style="width:80%">
  <li>Jill</li>
  <li>Adam</li>
</ul>

  <hr>
  <div class="xp-container">
  <h2>Tiny List</h2>
  <p>The xp-tiny class creates a tiny list.</p>

  <ul class="xp-ul xp-tiny">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Small List</h2>
  <p>The xp-small class creates a small list.</p>

  <ul class="xp-ul xp-small">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Large List</h2>
  <p>The xp-large class creates a large list.</p>

  <ul class="xp-ul xp-large">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>XLarge List</h2>
  <p>The xp-xlarge class creates an extra large list.</p>

  <ul class="xp-ul xp-xlarge">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>XLarge List</h2>
  <p>The xp-xlarge class creates an extra large list.</p>

  <ul class="xp-ul xp-xlarge">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>XXXLarge List</h2>
  <p>The xp-xxxlarge class creates an XXXlarge list.</p>

  <ul class="xp-ul xp-xxxlarge">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>Jumbo List</h2>
  <p>The xp-jumbo class creates an enormous "jumbo" list.</p>

  <ul class="xp-ul xp-jumbo">
    <li>Jill</li>
    <li>Eve</li>
    <li>Adam</li>
  </ul>
</div>

  <hr>
  <div class="xp-container">
  <h2>Rounded Images</h2>
  <p>The xp-round classes add rounded corners to an image:</p>

  <p>xp-round-small:</p>
  <img src="https://www.w3schools.com/w3css/img_lights.jpg" class="xp-round-small" alt="Norway" style="width:30%">

  <p>xp-round:</p>
  <img src="https://www.w3schools.com/w3css/img_lights.jpg" class="xp-round" alt="Norway" style="width:30%">

  <p>xp-round-large:</p>
  <img src="https://www.w3schools.com/w3css/img_lights.jpg" class="xp-round-large" alt="Norway" style="width:30%">

  <p>xp-round-xlarge:</p>
  <img src="https://www.w3schools.com/w3css/img_lights.jpg" class="xp-round-xlarge" alt="Norway" style="width:30%">

  <p>xp-round-xxlarge:</p>
  <img src="https://www.w3schools.com/w3css/img_lights.jpg" class="xp-round-xxlarge" alt="Norway" style="width:30%">
</div>

  <hr>
  <div class="xp-container">
  <h2>Image in a Circle</h2>
  <p>The xp-circle class shapes an image to a circle:</p>
  <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" class="xp-circle" alt="Norway" style="width:50%">
</div>
  <hr>
  <div class="xp-container">
  <h2>Bordered Image</h2>
  <p>The xp-border class adds borders around the image.</p>
  <p>Padding added wil be inside the borders:</p>
  <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" class="xp-border" alt="Norway" style="padding:4px;width:50%">

  <p>More padding:</p>
  <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" class="xp-border" alt="Norway" style="padding:16px;width:50%">
</div>
  <hr>
  <div class="xp-container">
  <h2>Image as a Card</h2>
  <p>Wrap any of the xp-card classes around the image to display it as a card:</p>
  <div class="xp-card" style="width:50%">
    <img src="https://www.w3schools.com/w3css/img_avatar3.png" alt="Person" style="width:100%">
    <div class="xp-container">
      <h4><b>Simon</b></h4>
      <p>The boss of all bosses</p>
    </div>
  </div>
  <br>

  <p>More shadows:</p>
  <div class="xp-card-4" style="width:50%">
    <img src="https://www.w3schools.com/w3css/img_avatar5.png" alt="Person" style="width:100%">
    <div class="xp-container">
      <h4><b>Jane</b></h4>
      <p>The other boss</p>
    </div>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Opacity/Transparency</h2>
  <p>The xp-opacity classes adds transparency to an element.</p>

  <p>Normal (100% opacity):</p>
  <img src="https://www.w3schools.com/w3css/img_forest.jpg" alt="Forest" style="width:150px">
  <p>xp-opacity-min (75% opacity):</p>
  <img src="https://www.w3schools.com/w3css/img_forest.jpg" alt="Forest" class="xp-opacity-min" style="width:150px">
  <p>xp-opacity (60% opacity):</p>
  <img src="https://www.w3schools.com/w3css/img_forest.jpg" alt="Forest" class="xp-opacity" style="width:150px">
  <p>xp-opacity-max (25% opacity):</p>
  <img src="https://www.w3schools.com/w3css/img_forest.jpg" alt="Forest" class="xp-opacity-max" style="width:150px">
</div>
  <hr>
  <div class="xp-container">
  <h2>Grayscale Effect</h2>
  <p>The xp-grayscale classes add a grayscale effect to an element.</p>
  <p><strong>Note:</strong> The xp-grayscale classes are not supported in IE 11 and earlier versions.</p>

  <p>Normal:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" style="width:150px">
  <p>xp-grayscale-min:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-grayscale-min" style="width:150px">
  <p>xp-grayscale:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-grayscale" style="width:150px">
  <p>xp-grayscale-max (black and white):</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-grayscale-max" style="width:150px">
</div>

  <hr>
  <div class="xp-container">
  <h2>Sepia Effect</h2>
  <p>The xp-sepia classes add a sepia effect to an element.</p>
  <p><strong>Note:</strong> The xp-sepia classes are not supported in IE 11 and earlier versions.</p>

  <p>Normal:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" style="width:150px">
  <p>xp-sepia-min:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-sepia-min" style="width:150px">
  <p>xp-sepia:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-sepia" style="width:150px">
  <p>xp-sepia-max:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" alt="Snow" class="xp-sepia-max" style="width:150px">
</div>

  <hr>
  <div class="xp-container">
  <h2>Hover Effect</h2>
  <p>You can also add special effects on hover/mouse-over.</p>
  <p><strong>Note:</strong> The xp-hover-sepia and xp-hover-grayscale classes are not supported in IE 11 and earlier versions.</p>

  <p>xp-hover-opacity:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" class="xp-hover-opacity" style="width:150px">
  <p>xp-hover-grayscale:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" class="xp-hover-grayscale" style="width:150px">
  <p>xp-hover-sepia:</p>
  <img src="https://www.w3schools.com/w3css/img_workshop.jpg" class="xp-hover-sepia" style="width:150px">
</div>

  <hr>
  <div class="xp-container">
  <h2>Hoverable Image</h2>

  <p>The xp-hover-opacity class adds transparency to the image when you move the mouse over it:</p>
  <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" class="xp-hover-opacity" alt="Norway" style="width:50%">

  <p>The xp-hover-opacity-off class rempves transparency from an image when you move the mouse over it:</p>
  <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" class="xp-opacity xp-hover-opacity-off" alt="Norway" style="width:50%">
</div>

  <hr>
  <div class="xp-container xp-teal">
  <h1>Summer 2015</h1>
</div>

<div class="xp-row-padding xp-margin-top">
  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_5terre.jpg" style="width:100%">
      <div class="xp-container">
        <h5>5 Terre</h5>
      </div>
    </div>
  </div>

  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_monterosso.jpg" style="width:100%">
      <div class="xp-container">
        <h5>Monterosso</h5>
      </div>
    </div>
  </div>

  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_vernazza.jpg" style="width:100%">
      <div class="xp-container">
        <h5>Vernazza</h5>
      </div>
    </div>
  </div>
</div>

<div class="xp-row-padding xp-margin-top">
  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_manarola.jpg" style="width:100%">
      <div class="xp-container">
        <h5>Manarola</h5>
      </div>
    </div>
  </div>

  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_corniglia.jpg" style="width:100%">
      <div class="xp-container">
        <h5>Corniglia</h5>
      </div>
    </div>
  </div>

  <div class="xp-third">
    <div class="xp-card">
      <img src="https://www.w3schools.com/w3css/img_riomaggiore.jpg" style="width:100%">
      <div class="xp-container">
        <h5>Riomaggiore</h5>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container xp-blue">
  <h2>Input Form</h2>
</div>

<form class="xp-container">
  <p>
  <label>First Name</label>
  <input class="xp-input" type="text"></p>
  <p>
  <label>Last Name</label>
  <input class="xp-input" type="text"></p>
  <p>
  <label>Email</label>
  <input class="xp-input" type="text"></p>
</form>
  <hr>
  <div class="xp-container xp-orange">
  <h2>Input Form</h2>
</div>

<form class="xp-container">
  <p>
  <input class="xp-input" type="text">
  <label>First Name</label></p>

  <p>
  <input class="xp-input" type="text">
  <label>Last Name</label></p>

  <p>
  <input class="xp-input" type="text">
  <label>Email</label></p>
</form>
  <hr>
  <div class="xp-container">
  <h2>Input Card</h2>
  
  <div class="xp-card-4">
    <div class="xp-container xp-green">
      <h2>Input Form</h2>
    </div>

    <form class="xp-container">
      <p>
      <input class="xp-input" type="text">
      <label>First Name</label></p>
      <p>     
      <input class="xp-input" type="text">
      <label>Last Name</label></p>
    </form>
  </div>
</div>
  <hr>
  <form class="xp-container xp-card-4" action="/action_page.php">
  <h2 class="xp-text-blue">Input Form</h2>
  <p>Use any of the xp-text-color classes to color your labels.</p>
  <p>      
  <label class="xp-text-blue"><b>First Name</b></label>
  <input class="xp-input xp-border" name="first" type="text"></p>
  <p>      
  <label class="xp-text-blue"><b>Last Name</b></label>
  <input class="xp-input xp-border" name="last" type="text"></p>
  <p>      
  <button class="xp-btn xp-blue">Register</button></p>
</form>

  <hr>
  <form class="xp-container xp-card-4 xp-light-grey">
  <h2>Bordered Input</h2>
  <p>Add the xp-border class to create bordered inputs.</p>

  <p><label>First Name</label>
  <input class="xp-input xp-border" name="first" type="text"></p>

  <p><label>Last Name</label>
  <input class="xp-input xp-border" name="last" type="text"></p>
</form>
  <hr>
  <form class="xp-container xp-card-4 xp-light-grey">
  <h2>Rounded Input</h2>
  <p>Use any of the xp-round classes to create rounded borders.</p>

  <p>
  <label>First Name</label>
  <input class="xp-input xp-border xp-round" name="first" type="text"></p>
  <p>
  <label>Last Name</label>
  <input class="xp-input xp-border xp-round-large" name="last" type="text"></p>
  <p>
  <label>Last Name</label>
  <input class="xp-input xp-border xp-round-xxlarge" name="last" type="text"></p>
</form>
  <hr>
  <div class="xp-container">
  <h2>Borderless Input</h2>
  <p>The xp-input class has a bottom border by default. If you want a borderless input, add the xp-border-0 class.</p>
</div>

<form class="xp-container xp-card-4 xp-light-grey">
  <h3>Default:</h3>
  <p>      
  <label>First Name</label>
  <input class="xp-input" type="text"></p>
</form>
<br>

<form class="xp-container xp-card-4 xp-light-grey">
  <h3>Bordered:</h3>
  <p>      
  <label>First Name</label>
  <input class="xp-input xp-border" type="text"></p>
</form>
<br>

<form class="xp-container xp-card-4 xp-light-grey">
  <h3>Borderless:</h3>
  <p>      
  <label>First Name</label>
  <input class="xp-input xp-border-0" type="text"></p>
</form>

  <hr>
  <div class="xp-card-4">
  <div class="xp-container xp-brown">
    <h2>Input Colors</h2>
  </div>
  <form class="xp-container" action="/action_page.php">
    <p>      
    <label class="xp-text-brown"><b>First Name</b></label>
    <input class="xp-input xp-border xp-sand" name="first" type="text"></p>
    <p>      
    <label class="xp-text-brown"><b>Last Name</b></label>
    <input class="xp-input xp-border xp-sand" name="last" type="text"></p>
    <p>
    <button class="xp-btn xp-brown">Register</button></p>
  </form>
</div>

  <hr>
  <form class="xp-container">
  <h2>Hoverable Inputs</h2>
  <p>Move the mouse over the input fields:</p>

  <p><input class="xp-input xp-hover-green" type="text"></p>
  <p><input class="xp-input xp-border xp-hover-red" type="text"></p>
  <p><input class="xp-input xp-border xp-hover-blue" type="text"></p>
</form>
  <hr>
  <form class="xp-container">
  <h2>Animated Inputs</h2>
  <p>The xp-animate-input class animates the width of an input to 100%. Click on the inputs below to see the effect:</p>
  <input class="xp-input xp-animate-input" type="text" style="width:135px"><br>
  <input class="xp-input xp-border xp-animate-input" type="text" style="width:30%">
</form>
  <hr>
  <form class="xp-container xp-card-4">
  <h2>Checkboxes</h2>
  <p>
  <input class="xp-check" type="checkbox" checked="checked">
  <label>Milk</label></p>
  <p>
  <input class="xp-check" type="checkbox">
  <label> Sugar</label></p>
  <p>
  <input class="xp-check" type="checkbox" disabled>
  <label>Lemon (Disabled)</label></p>
</form>
  <hr>
  <form class="xp-container xp-card-4">
  <h2>Radio Buttons</h2>
  <p>
  <input class="xp-radio" type="radio" name="gender" value="male" checked>
  <label>Male</label></p>
  <p>
  <input class="xp-radio" type="radio" name="gender" value="female">
  <label>Female</label></p>
  <p>
  <input class="xp-radio" type="radio" name="gender" value="" disabled>
  <label>Don't know (Disabled)</label></p>
</form>

  <hr>
  <form class="xp-container xp-card-4" action="/action_page.php">
  <h1>Select Your Free Option</h1>

  <select class="xp-select" name="option">
    <option value="" disabled selected>Choose your option</option>
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
    <option value="3">Option 3</option>
  </select>

  <p><button class="xp-btn xp-teal">Register</button></p>
</form>
  <hr>
  <form class="xp-container xp-card-4" action="/action_page.php">
  <h1>Select Your Free Option</h1>

  <select class="xp-select xp-border" name="option">
    <option value="" disabled selected>Choose your option</option>
    <option value="1">Option 1</option>
    <option value="2">Option 2</option>
    <option value="3">Option 3</option>
  </select>
  <p><button class="xp-btn xp-teal">Register</button></p>
</form>
  <hr>
  <div class="xp-container">
  <h2>Form Elements in a Grid</h2>
  <p>In this example, we use xp.CSS' Responsive Grid System to make the inputs appear on the same line (on smaller screens, they will stack horizontally with 100% width). You will learn more about this later.</p>
</div>

<div class="xp-row-padding">
  <div class="xp-third">
    <input class="xp-input xp-border" type="text" placeholder="One">
  </div>
  <div class="xp-third">
    <input class="xp-input xp-border" type="text" placeholder="Two">
  </div>
  <div class="xp-third">
    <input class="xp-input xp-border" type="text" placeholder="Three">
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Form Elements in a Grid</h2>
  <p>Two column layout with labels:</p>
</div>

<div class="xp-row-padding">
  <div class="xp-half">
    <label>First Name</label>
    <input class="xp-input xp-border" type="text" placeholder="One">
  </div>
  <div class="xp-half">
    <label>Last Name</label>
    <input class="xp-input xp-border" type="text" placeholder="Two">
  </div>
</div>

  <hr>
  <form action="/action_page.php" class="xp-container xp-card-4 xp-light-grey xp-text-blue xp-margin">
<h2 class="xp-center">Contact Us</h2>
 
<div class="xp-row xp-section">
  <div class="xp-col" style="width:50px"><i class="xp-xxlarge fa fa-user"></i></div>
    <div class="xp-rest">
      <input class="xp-input xp-border" name="first" type="text" placeholder="First Name">
    </div>
</div>

<div class="xp-row xp-section">
  <div class="xp-col" style="width:50px"><i class="xp-xxlarge fa fa-user"></i></div>
    <div class="xp-rest">
      <input class="xp-input xp-border" name="last" type="text" placeholder="Last Name">
    </div>
</div>

<div class="xp-row xp-section">
  <div class="xp-col" style="width:50px"><i class="xp-xxlarge fa fa-envelope-o"></i></div>
    <div class="xp-rest">
      <input class="xp-input xp-border" name="email" type="text" placeholder="Email">
    </div>
</div>

<div class="xp-row xp-section">
  <div class="xp-col" style="width:50px"><i class="xp-xxlarge fa fa-phone"></i></div>
    <div class="xp-rest">
      <input class="xp-input xp-border" name="phone" type="text" placeholder="Phone">
    </div>
</div>

<div class="xp-row xp-section">
  <div class="xp-col" style="width:50px"><i class="xp-xxlarge fa fa-pencil"></i></div>
    <div class="xp-rest">
      <input class="xp-input xp-border" name="message" type="text" placeholder="Message">
    </div>
</div>

<button class="xp-button xp-block xp-section xp-blue xp-ripple xp-padding">Send</button>

</form>

  <hr>
  <div class="xp-container">
  <h2>Badges</h2>
  <p>The xp-badge class creates a circular badge. Badges are black by default.</p>
  <p>Updates <span class="xp-badge">9</span></p>
</div>
  <hr>
  <div class="xp-container">
  <h2>Badges</h2>
  <p>You can use color classes to change the color of a badge:</p>
  <p>News <span class="xp-badge xp-green">6</span></p>
  <p>Comments <span class="xp-badge xp-red">8</span></p>
</div>
  <hr>
  <h2>Badges in Buttons</h2>

<p>The xp-badge class can be used inside buttons:</p>

<p><button class="xp-btn xp-black">Button
<span class="xp-badge xp-margin-left xp-white">1</span>
</button></p>

<p><button class="xp-btn xp-red">Button
<span class="xp-badge xp-margin-left">2</span>
</button></p>

</div>
  <hr>
  <div class="xp-container">
<h2>Badges in a List</h2>
<ul class="xp-ul">
  <li><span class="xp-badge">1</span> Jill</li>
  <li><span class="xp-badge">2</span> Eve</li>
  <li><span class="xp-badge">3</span> Adam</li>
</ul>
</div>
  <hr>
  <div class="xp-container">
  <h2>List with Badges</h2>
  <p>The xp-right class floats an element to the right</p>
  <p>This is perfect for lists with badges:</p>

  <ul class="xp-ul xp-border">
    <li>Jill <span class="xp-badge xp-right xp-margin-right">5</span></li>
    <li>Eve <span class="xp-badge xp-right xp-margin-right">3</span></li>
    <li>Adam <span class="xp-badge xp-right xp-margin-right">8</span></li>
  </ul>
</div>
  <hr>
  <div class="xp-container">
<h2>Badges in a Table</h2>
<table class="xp-table xp-bordered xp-striped xp-border">
<thead>
<tr class="xp-green">
  <th>First Name</th>
  <th>Last Name</th>
  <th>Points</th>
</tr>
</thead>
<tr>
  <td>Jill</td>
  <td>Smith</td>
  <td>50</td>
</tr>
<tr>
  <td>Eve</td>
  <td>Jackson <span class="xp-badge">1</span></td>
  <td>94</td>
</tr>
<tr>
  <td>Adam</td>
  <td>Johnson <span class="xp-badge">2</span></td>
  <td>67</td>
</tr>
<tr>
  <td>Bo</td>
  <td>Nilsson</td>
  <td>50</td>
</tr>
<tr>
  <td>Mike</td>
  <td>Ross</td>
  <td>34</td>
</tr>
</table>
</div>

  <hr>
  <div class="xp-container">
  <h2>Small and Large Badges</h2>
  <p>
    <span class="xp-badge xp-tiny xp-red">6</span>
    <span class="xp-badge xp-small xp-red">6</span>
    <span class="xp-badge xp-red">6</span>
  </p>
  <p>
    <span class="xp-badge xp-large xp-padding xp-red">66</span>
    <span class="xp-badge xp-xlarge xp-padding xp-red">66</span>
    <span class="xp-badge xp-xxlarge xp-padding xp-red">66</span>
  </p>
  <p>
    <span class="xp-badge xp-xxxlarge xp-padding xp-red">66</span>
    <span class="xp-badge xp-jumbo xp-padding xp-red">66</span></p>
  <p>
</div>

  <hr>
  <div class="xp-container">
  <h2>xp.CSS Badges</h2>
  <p>You can display single digit badges using UTF-8 Dingbats:</p>

  <div class="xp-xxlarge">
  &#x2776; &#x2777; &#x2778; &#x2779; &#x277A;
  &#x2785; &#x2786; &#x2787; &#x2788; &#x2789;
  </div>

  <div class="xp-xxlarge xp-text-red">
  &#x2776; &#x2777; &#x2778; &#x2779; &#x277A;
  &#x2785; &#x2786; &#x2787; &#x2788; &#x2789;
  </div>

</div>

  <hr>
  <div class="xp-container">
  <h2>xp.CSS Tags</h2>
  <p>The xp-tag class creates a rectangular tag (label or sign).</p>
  <p>The default color is black.</p>
  <p>Status: <span class="xp-tag">Done</span></p>
</div>
  <hr>
  <div class="xp-container">
  <h2>xp.CSS Tags</h2>
  <p>You can use a color class to change the color of a tag.</p>
  <p><span class="xp-tag xp-blue">New!</span></p>
  <p><span class="xp-tag xp-teal">More Later!</span></p>
</div>

  <hr>
  <div class="xp-container">

<h2>Large Tags (Labels or Signs)</h2>

<p>
<span class="xp-tag xp-xlarge xp-blue">66</span>
<span class="xp-tag xp-xxlarge xp-blue">66</span>
<span class="xp-tag xp-xxxlarge xp-blue">66</span>
</p>

<p>
<span class="xp-tag xp-jumbo xp-blue">66</span>
<span class="xp-tag xp-jumbo xp-blue xp-padding-large">66</span>
</p>

</div>

  <hr>
  <div class="xp-container">
  <h2>Displaying Letters as Tags</h2>
  <span class="xp-tag xp-xlarge">A</span>
  <span class="xp-tag xp-xlarge">U</span>
  <span class="xp-tag xp-xlarge">G</span>
  <span class="xp-tag xp-xlarge">U</span>
  <span class="xp-tag xp-xlarge">S</span>
  <span class="xp-tag xp-xlarge">T</span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Tags in a Row</h2>
  <span class="xp-tag xp-jumbo xp-red">S</span>
  <span class="xp-tag xp-jumbo">A</span>
  <span class="xp-tag xp-jumbo xp-yellow">L</span>
  <span class="xp-tag xp-jumbo">E</span>
</div>

  <hr>
  <div class="xp-container">
  <h2>Displaying a Tag as a Sign</h2>
  <div class="xp-tag xp-xxlarge xp-orange">London Zoo</div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Displaying Road Signs</h2>

  <div class="xp-tag xp-round xp-green" style="padding:3px">
    <div class="xp-tag xp-round xp-green xp-border xp-border-white">
      Falcon Ridge Parkway
    </div>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Displaying Large Signs</h2>
  <span class="xp-tag xp-xxlarge xp-padding xp-orange xp-center">
    <strong>
    IN CASE OF<br>
    EMERGENCY<br>
    RUN LIKE HELL !
    </strong>
  </span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Large Signs</h2>
  <span class="xp-tag xp-jumbo xp-green">
  49<span class="xp-xlarge">,99</span>
  </span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying Rounded Signs</h2>
  <span class="xp-tag xp-padding xp-round-large xp-red xp-center">
  DO NOT<br>
  BREATHE<br>
  UNDER WATER
  </span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying a Rotated Sign</h2>
  <span class="xp-tag xp-xlarge xp-padding xp-red" style="transform:rotate(-10deg)">
  STOP
  </span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Displaying a Spinning Sign</h2>
  <span class="xp-tag xp-spin xp-large">
  STOP
  </span>
</div>

  <hr>
  <div class="xp-container">
  <h1>Using Font Awesome Icons</h1>

  <div class="xp-padding xp-xlarge xp-teal">
    <i class="fa fa-home"></i>
    <i class="fa fa-search"></i>
    <i class="fa fa-cloud"></i>
    <i class="fa fa-trash"></i>
    Welcome!
  </div>

  <div class="xp-padding xp-xlarge xp-text-orange">
    <i class="fa fa-home"></i>
    <i class="fa fa-search"></i>
    <i class="fa fa-cloud"></i>
    <i class="fa fa-trash"></i>
    Welcome!
  </div>

  <ul class="xp-ul">
    <li><i class="fa fa-home"></i> Home</li>
    <li class="xp-large"><i class="fa fa-home"></i> Home</li>
    <li class="xp-xlarge"><i class="fa fa-home"></i> Home</li>
    <li class="xp-xxlarge"><i class="fa fa-home"></i> Home</li>
    <li class="xp-xxxlarge"><i class="fa fa-home"></i> Home</li>
    <li class="xp-jumbo xp-teal"><i class="fa fa-home"></i> Home</li>
  </ul>

  <p><button class="xp-btn xp-orange xp-xlarge">Button<i class="xp-margin-left fa fa-home"></i></button></p>

  <p><i class="xp-jumbo xp-spin fa fa-home"></i></p>
</div>
  <hr>
  <div class="xp-container">
  <h1>Using Google Icons</h1>

  <div class="xp-padding xp-xlarge xp-teal">
    <i class="material-icons">home</i>
    <i class="material-icons">search</i>
    <i class="material-icons">cloud</i>
    <i class="material-icons">delete</i>
    Welcome!
  </div>

 <div class="xp-padding xp-xlarge xp-text-orange">
    <i class="material-icons">home</i>
    <i class="material-icons">search</i>
    <i class="material-icons">cloud</i>
    <i class="material-icons">delete</i>
    Welcome!
  </div>

  <ul class="xp-ul">
    <li><i class="material-icons">home</i> Home</li>
    <li class="xp-large"><i class="material-icons xp-large">home</i> Home</li>
    <li class="xp-xlarge"><i class="material-icons xp-xlarge">home</i> Home</li>
    <li class="xp-xxlarge"><i class="material-icons xp-xxlarge">home</i> Home</li>
    <li class="xp-xxxlarge"><i class="material-icons xp-xxxlarge">home</i> Home</li>
    <li class="xp-jumbo xp-teal"><i class="material-icons xp-jumbo">home</i> Home</li>
  </ul>

  <p><button class="xp-btn xp-orange xp-xlarge">Button<i class="xp-margin-left material-icons">home</i></button></p>

  <p><i class="material-icons xp-spin xp-jumbo">home</i></p>
</div>

  <hr>
  <div class="xp-row xp-border">
  <div class="xp-container xp-half xp-red">
    <h2>xp-half</h2>  
    <p>The xp-half class uses 50% of the parent container.</p>
    <p>On screens smaller than 601 pixels it resizes to 100%.</p>
  </div>
  <div class="xp-container xp-half">
    <h2>xp-half</h2>  
  </div>
</div>
  <hr>
  <div class="xp-container">
<h2>Mobile First Responsiveness</h2>
<p class="xp-large">Try to resize the window!</p>
</div>

<div class="xp-row xp-border">
<div class="xp-third xp-container xp-red">
  <h2>xp-third</h2>  
  <p>The xp-third class uses 33% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="xp-third xp-container">
  <h2>xp-third</h2>
</div>
<div class="xp-third xp-container">
  <h2>xp-third</h2>
</div>
</div>
  <hr>
  <div class="xp-container">
<h2>Mobile First Responsiveness</h2>
<p class="xp-large">Try to resize the window!</p>
</div>

<div class="xp-row xp-border">
<div class="xp-twothird xp-container xp-red">
  <h2>xp-twothird</h2>  
  <p>The xp-twothird class uses 66% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="xp-third xp-container">
  <h2>xp-third</h2>
  <p>The xp-twothird class uses 33% of parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
</div>
<br>

<div class="xp-row xp-border">
<div class="xp-third xp-container">
  <h2>xp-third</h2>
  <p>The xp-twothird class uses 33% of parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="xp-twothird xp-container xp-red">
  <h2>xp-twothird</h2>  
  <p>The xp-twothird class uses 66% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
</div>

  <hr>
  <div class="xp-container">
<h2>Mobile First Responsiveness</h2>
<p class="xp-large">Try to resize the window!</p>
</div>

<div class="xp-row xp-border">
<div class="xp-quarter xp-container xp-red">
  <h2>xp-quarter</h2>  
  <p>The xp-quarter class uses 25% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="xp-quarter xp-container">
  <h2>xp-quarter</h2>
</div>
<div class="xp-quarter xp-container">
  <h2>xp-quarter</h2>
</div>
<div class="xp-quarter xp-container">
  <h2>xp-quarter</h2>
</div>
</div>

  <hr>
  <div class="xp-container">
<h2>Mobile First Responsiveness</h2>
<p class="xp-large">Try to resize the window!</p>
</div>

<div class="xp-row xp-border">
<div class="xp-threequarter xp-container xp-red">
  <h2>xp-threequarter</h2>  
  <p>The xp-threequarter class uses 75% of the parent container.</p>
  <p>On screens smaller than 601 pixels it resizes to full screen.</p>
</div>
<div class="xp-quarter xp-container">
  <h2>xp-quarter</h2>
</div>
</div>
  <hr>
  <div class="xp-container">
<h2>Mobile First Responsiveness</h2>
<h3>Nested Rows (xp-half inside xp-half)</h3>
<p class="xp-large">Try to resize the window!</p>
</div>

<div class="xp-row">
  <div class="xp-half xp-container xp-green">
    <h2>xp-half</h2>
    <div class="xp-row">
      <div class="xp-half xp-container xp-red">
        <h2>xp-half</h2>  
        <p>This is a paragraph.</p>
      </div>
      <div class="xp-half xp-container xp-yellow">
        <h2>xp-half</h2>  
        <p>This is a paragraph.</p>
      </div>
    </div>
  </div>
  <div class="xp-half xp-container xp-blue">
    <h2>xp-half</h2>
    <div class="xp-row">
      <div class="xp-half xp-container xp-red">
        <h2>xp-half</h2>  
        <p>This is a paragraph.</p>
      </div>
      <div class="xp-half xp-container xp-yellow">
        <h2>xp-half</h2>  
        <p>This is a paragraph.</p>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Using xp-rest</h2>
  <p>The xp-rest class will use what's left of the grid column.</p>
</div>

<div class="xp-row">
  <div class="xp-col xp-container xp-blue" style="width:150px"><p>150px</p></div>
  <div class="xp-rest xp-container xp-green"><p>xp-rest</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-col xp-right xp-container xp-blue" style="width:75px"><p>75px</p></div>
  <div class="xp-rest xp-container xp-green"><p>xp-rest</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-col xp-left xp-container xp-blue" style="width:100px"><p>100px</p></div>
  <div class="xp-col xp-right xp-container xp-blue" style="width:100px"><p>100px</p></div>
  <div class="xp-rest xp-container xp-green"><p>xp-rest</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-quarter xp-container xp-red"><p>quarter</p></div>
  <div class="xp-half">
    <div class="xp-row">
      <div class="xp-col xp-container xp-blue" style="width:80px"><p>80px</p></div>
      <div class="xp-rest xp-container xp-green"><p>xp-rest</p></div>
    </div>
  </div>
  <div class="xp-quarter xp-container xp-purple"><p>quarter</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-quarter xp-container xp-red"><p>quarter</p></div>
  <div class="xp-quarter xp-container xp-purple"><p>quarter</p></div>
  <div class="xp-half">
    <div class="xp-row">
      <div class="xp-col xp-container xp-blue" style="width:35%"><p>35%</p></div>
      <div class="xp-rest xp-container xp-green"><p>xp-rest</p></div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
<h2>Using Percent</h2>
<p>Use the CSS width property to determine a specific width of the columns.</p>
</div>

<div class="xp-row">
  <div class="xp-col xp-green xp-container" style="width:20%"><p>20%</p></div>
  <div class="xp-col xp-blue xp-container" style="width:60%"><p>60%</p></div>
  <div class="xp-col xp-red xp-container" style="width:20%"><p>20%</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-col xp-green xp-container" style="width:45%"><p>45%</p></div>
  <div class="xp-col xp-dark-grey xp-container" style="width:55%"><p>55%</p></div>
</div>
<br>

<div class="xp-row">
  <div class="xp-col xp-green xp-container" style="width:15%"><p>15%</p></div>
  <div class="xp-col xp-dark-grey xp-container" style="width:35%"><p>35%</p></div>
  <div class="xp-col xp-red xp-container" style="width:10%"><p>10%</p></div>
  <div class="xp-col xp-blue xp-container" style="width:30%"><p>30%</p></div>
  <div class="xp-col xp-purple xp-container" style="width:10%"><p>10%</p></div>
</div>
  <hr>
  <div class="xp-container xp-card xp-indigo">
  <h1>Movies 2014</h1>
</div>

<ul class="xp-ul">
  <li>
    <h3>xp-content</h3>
    <p>The xp-content class defines a container for fixed size centered content. Use the CSS max-width property to override the default width (980px).</p>
  </li>
  <li>
    <h3>The Fault in Our Stars</h3>
    <p>Touching, gripping and genuinely well made.</p>
  </li>
  <li>
    <h3>The Avengers</h3>
    <p>A huge success for Marvel and Disney.</p>
  </li>
</ul>

<div class="xp-container xp-indigo xp-xlarge">
  <h5>Movies 2014</h5>
</div>

  <hr>
  <div class="xp-container">
  <h3>Difference between xp-row and xp-row-padding</h3>
  <p>The xp-row class defines a padded-less container:</p>
</div>

  <div class="xp-row">
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_lights.jpg" style="width:100%">
    </div>
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_nature.jpg" style="width:100%">
    </div>
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" style="width:100%">
    </div>
  </div>

<div class="xp-container">
  <p>The xp-row-padding class adds a 8px left and right padding to each column:</p>
</div>

  <div class="xp-row-padding">
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_lights.jpg" style="width:100%">
    </div>
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_nature.jpg" style="width:100%">
    </div>
    <div class="xp-third">
      <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" style="width:100%">
    </div>
  </div>

  <hr>
  <h2>Stretch</h2>

<p>The xp-stretch class removes the right and left margins from an element. This class is often used to stretch a padded row:</p>

<p>An example with xp-stretch:</p>
<div class="xp-row-padding xp-section xp-stretch">
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_nature_wide.jpg" style="width:100%">
  </div>
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" style="width:100%">
  </div>
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_mountains_wide.jpg" style="width:100%">
  </div>
</div>

<p>An example without xp-stretch:</p>
<div class="xp-row-padding xp-section">
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_nature_wide.jpg" style="width:100%">
  </div>
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" style="width:100%">
  </div>
  <div class="xp-col s4">
    <img src="https://www.w3schools.com/w3css/img_mountains_wide.jpg" style="width:100%">
  </div>
</div>

  <hr>
  <div class="xp-container">
<h2>Responsive Show/Hide</h2>
<p><strong>Note:</strong> Resize the browser window to understand how it works:</p>

<div class="xp-container xp-hide-small xp-red">
<p>xp-hide-small will be hidden on small screens (phones)</p>
</div>

<div class="xp-container xp-hide-medium xp-green">
<p>xp-hide-medium will be hidden on medium screens (tablets)</p>
</div>

<div class="xp-container xp-hide-large xp-blue">
<p>xp-hide-large will be hidden on large screens (laptops/desktop)</p>
</div>
</div>

  <hr>
  <div class="xp-container">
  <h2>The xp-mobile Class</h2>
  <p>The <strong>xp-mobile</strong> class adds mobile-first responsivenss to any element.</p>
  <p>It adds display:block and width:100% to an element on screens that are less than 600px wide.</p>

  <p>Resize the browser window to see the effect:</p>
  <button class="xp-button xp-black xp-mobile">Home</button>
  <button class="xp-button xp-black xp-mobile">Link 1</button>
  <button class="xp-button xp-black xp-mobile">Link 2</button>
  <button class="xp-button xp-black xp-mobile">Link 3</button>
</div>

  <hr>
  <div class="xp-container xp-red">
  <p>Hello xp.CSS Layout.</p>
</div>

<div class="xp-container xp-green">
  <p>Hello xp.CSS Layout.</p>
</div>

  <hr>
  <div class="xp-container xp-red xp-cell">
  <p>Hello xp.CSS Layout.</p>
</div>

<div class="xp-container xp-green xp-cell">
  <p>Hello xp.CSS Layout.</p>
</div>
  <hr>
  <div class="xp-cell-row">
  <div class="xp-container xp-red xp-cell">
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-green xp-cell">
    <p>Hello xp.CSS Layout.</p>
  </div>
</div>
  <hr>
  <div class="xp-cell-row" style="width:75%">
  <div class="xp-container xp-red xp-cell">
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-green xp-cell">
    <p>Hello xp.CSS Layout.</p>
  </div>
</div>
  <hr>
  <div class="xp-container xp-red xp-cell">
  <p>Hello xp.CSS Layout.</p>
</div>

<div class="xp-container xp-green xp-cell">
  <p>Hello xp.CSS Layout. Hello xp.CSS Layout. Hello xp.CSS Layout.</p>
</div>
  <hr>
  <div class="xp-container xp-red xp-cell">
  <p>Hello xp.CSS Layout.</p>
</div>

<div class="xp-container xp-green xp-cell">
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
</div>
  <hr>
  <div class="xp-container">
  <h2>Responsive Layout</h2>
  <p>The xp-mobile class displays HTML elements vertically on small screens and horizontally on medium/large screens. Resize the browser window to see the effect.</p>
</div>

<div class="xp-cell-row">
  <div class="xp-container xp-red xp-cell xp-mobile">
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-green xp-cell xp-mobile">
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-blue xp-cell xp-mobile">
    <p>Hello xp.CSS Layout. Hello xp.CSS Layout.</p>
  </div>
</div>
  <hr>
  <div class="xp-container xp-red xp-cell xp-cell-top">
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
  <p>Hello xp.CSS Layout.</p>
</div>
<div class="xp-container xp-green xp-cell xp-cell-middle">
  <p>Hello xp.CSS Layout.</p>
</div>
<div class="xp-container xp-blue xp-cell xp-cell-bottom">
  <p>Hello xp.CSS Layout.</p>
</div>

  <hr>
  <div class="xp-container">
  <h2>Layout Container</h2>
  <p>The xp-cell-row class stretches the elements to fit the page width.</p>
  <p>Resize the browser window to see the effect.</p>
</div>

<div class="xp-cell-row">
  <div class="xp-container xp-red xp-cell xp-cell-top">
    <p>Hello xp.CSS Layout.</p>
    <p>Hello xp.CSS Layout.</p>
    <p>Hello xp.CSS Layout.</p>
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-green xp-cell xp-cell-middle">
    <p>Hello xp.CSS Layout.</p>
  </div>
  <div class="xp-container xp-blue xp-cell xp-cell-bottom">
    <p>Hello xp.CSS Layout.</p>
  </div>
</div>
  <hr>
 <div class="xp-container">
  <h2>Opacity Effect</h2>
  <p>The xp-opacity classes add a transparency effect to an element.</p>

  <p>Normal:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" style="width:300px">
  <p>xp-opacity-min:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-opacity-min" style="width:300px">
  <p>xp-opacity:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-opacity" style="width:300px">
  <p>xp-opacity-max:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-opacity-max" style="width:300px">

  <div class="xp-panel xp-red xp-opacity">
    <p>Red with opacity</p>
  </div>
  <div class="xp-panel xp-blue xp-opacity">
    <p>Blue with opacity</p>
  </div>
  <div class="xp-panel xp-green xp-opacity">
    <p>Green with opacity</p>
  </div>
</div>
<hr>
<div class="xp-container">
  <h2>Grayscale Effect</h2>
  <p>The xp-grayscale classes add a grayscale effect to an element.</p>
  <p><strong>Note:</strong> The xp-grayscale classes are not supported in IE 11 and earlier versions.</p>

  <p>Normal:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" style="width:300px">
  <p>xp-grayscale-min:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" class="xp-grayscale-min" style="width:300px">
  <p>xp-grayscale:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" class="xp-grayscale" style="width:300px">
  <p>xp-grayscale-max (black and white):</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Fjords" class="xp-grayscale-max" style="width:300px">

  <div class="xp-panel xp-red xp-grayscale">
    <p>Red with grayscale</p>
  </div>
  <div class="xp-panel xp-blue xp-grayscale">
    <p>Blue with grayscale</p>
  </div>
  <div class="xp-panel xp-green xp-grayscale">
    <p>Green with grayscale</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Sepia Effect</h2>
  <p>The xp-sepia classes add a sepia effect to an element.</p>
  <p><strong>Note:</strong> The xp-sepia classes are not supported in IE 11 and earlier versions.</p>

  <p>Normal:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" style="width:300px">
  <p>xp-sepia-min:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" class="xp-sepia-min" style="width:300px">
  <p>xp-sepia:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" class="xp-sepia" style="width:300px">
  <p>xp-sepia-max:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" alt="Snow" class="xp-sepia-max" style="width:300px">

  <div class="xp-panel xp-red xp-sepia">
    <p>Red with sepia</p>
  </div>
  <div class="xp-panel xp-blue xp-sepia">
    <p>Blue with sepia</p>
  </div>
  <div class="xp-panel xp-green xp-sepia">
    <p>Green with sepia</p>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Hover Effect</h2>
  <p>You can also add special effects on hover/mouse-over.</p>
  <p><strong>Note:</strong> The xp-hover-sepia and xp-hover-grayscale classes are not supported in IE 11 and earlier versions.</p>

  <p>xp-hover-opacity:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-hover-opacity" style="width:300px">
  <p>xp-hover-grayscale:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-hover-grayscale" style="width:300px">
  <p>xp-hover-sepia:</p>
  <img src="https://www.w3schools.com/w3css/img_snow_wide.jpg" class="xp-hover-sepia" style="width:300px">

  <div class="xp-panel xp-red xp-hover-opacity">
    <p>xp-hover-opacity</p>
  </div>
  <div class="xp-panel xp-red xp-hover-grayscale">
    <p>xp-hover-grayscale</p>
  </div>
  <div class="xp-panel xp-red xp-hover-sepia">
    <p>xp-hover-sepia</p>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Hover Effects</h2>
  <p>You can also combine xp-hover-color classes with xp-hover-opacity to create a slightly "lighter" background-color.</p>

  <div class="xp-panel xp-border xp-hover-red xp-padding">
    <p>xp-hover-red</p>
  </div>
  
  <div class="xp-panel xp-border xp-hover-opacity xp-hover-red xp-padding">
    <p>xp-hover-red with xp-hover-opacity</p>
  </div>
</div>
  <hr>
  <h2>Horizontal Bar</h2>

<p>An horizontal bar is a common web design element:</p>

<div class="xp-bar xp-border xp-light-grey">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>
  <hr>
  <div class="xp-container">

<h2>Vertical Bar</h2>

<p>An vertical bar is a common web design element:</p>

<div class="xp-bar-block xp-border xp-light-grey" style="width:100px">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Bar Colors</h2>

<p>You can use any color to style a bar:</p>

<div class="xp-bar xp-black">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>
<br>
<div class="xp-bar xp-red">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>
<br>
<div class="xp-bar-block xp-black" style="width:120px">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>
<br>
<div class="xp-bar-block xp-red" style="width:120px">
  <div class="xp-bar-item">London</div>
  <div class="xp-bar-item">Paris</div>
  <div class="xp-bar-item">Tokyo</div>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Hover Colors</h2>

<p>You can use any hover color to style a bar:</p>
<p>Mouse over the bar items to see the effect:</p>

<div class="xp-bar xp-black">
  <div class="xp-bar-item xp-hover-red">London</div>
  <div class="xp-bar-item xp-hover-green ">Paris</div>
  <div class="xp-bar-item xp-hover-blue">Tokyo</div>
</div>
<br>
<div class="xp-bar-block xp-black" style="width:120px">
  <div class="xp-bar-item xp-hover-red">London</div>
  <div class="xp-bar-item xp-hover-green ">Paris</div>
  <div class="xp-bar-item xp-hover-blue">Tokyo</div>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Bar Links</h2>
<p>Providing navigation is a typical use for bars:</p>
<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-hover-green">London</a>
  <a href="#" class="xp-bar-item xp-hover-green">Paris</a>
  <a href="#" class="xp-bar-item xp-hover-green">Tokyo</a>
</div>
<br>
<div class="xp-bar-block xp-black" style="width:120px">
  <a href="#" class="xp-bar-item xp-hover-green">London</a>
  <a href="#" class="xp-bar-item xp-hover-green">Paris</a>
  <a href="#" class="xp-bar-item xp-hover-green">Tokyo</a>
</div>
  <hr>
  <div class="xp-container">

<h2>Bar Links</h2>
<p>Providing navigation is a typical use for bars:</p>
<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button">London</a>
  <a href="#" class="xp-bar-item xp-button">Paris</a>
  <a href="#" class="xp-bar-item xp-button">Tokyo</a>
</div>
<br>
<div class="xp-bar-block xp-black" style="width:120px">
  <a href="#" class="xp-bar-item xp-button">London</a>
  <a href="#" class="xp-bar-item xp-button">Paris</a>
  <a href="#" class="xp-bar-item xp-button">Tokyo</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Responsive Bar</h2>
<p>The <strong>xp-mobile</strong> class is perfect for smaking bar items responsive.</p>
<p>Resize the window to see the effect:</p>

<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button xp-mobile">London</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Paris</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Tokyo</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Responsive Bar</h2>
<p>The <strong>xp-right</strong> class right-aligns bar items:</p>

<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button">London</a>
  <a href="#" class="xp-bar-item xp-button">Paris</a>
  <a href="#" class="xp-bar-item xp-button xp-right">Tokyo</a>
</div>

</div>
  <hr>
  <div class="xp-container">
  <h2>Dropdown Button</h2>
  <p>Move the mouse over the button to open the dropdown content.</p>
  <div class="xp-dropdown-hover">
    <button class="xp-button xp-black">Hover Over Me!</button>
    <div class="xp-dropdown-content xp-bar-block xp-border">
      <a href="#" class="xp-bar-item xp-button">Link 1</a>
      <a href="#" class="xp-bar-item xp-button">Link 2</a>
      <a href="#" class="xp-bar-item xp-button">Link 3</a>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Dropdown Paragraph</h2>
  <p>Move the mouse over the paragraph to open the dropdown content.</p>

  <p class="xp-dropdown-hover">Hover over me!
    <span class="xp-dropdown-content xp-green xp-padding">Hello World!</span>
  </p>
</div>
  <hr>
  <div class="xp-container">
  <h2>Navigation Bar with Dropdown</h2>
  <p>Add a dropdown menu inside the navigation bar:</p>

  <div class="xp-bar xp-light-grey">
    <a href="#" class="xp-bar-item xp-button">Home</a>
    <a href="#" class="xp-bar-item xp-button">Link 1</a>
    <div class="xp-dropdown-hover">
      <button class="xp-button">Dropdown</button>
      <div class="xp-dropdown-content xp-bar-block xp-card-4">
        <a href="#" class="xp-bar-item xp-button">Link 1</a>
        <a href="#" class="xp-bar-item xp-button">Link 2</a>
        <a href="#" class="xp-bar-item xp-button">Link 3</a>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Image Dropdown</h2>
  <p>Move the mouse over the image:</p>

  <div class="xp-dropdown-hover"><img src="img_snowtops.jpg" alt="Monterosso" style="width:20%">
    <div class="xp-dropdown-content" style="width:300px"><br>
      <img src="https://www.w3schools.com/w3css/img_snowtops.jpg" alt="Norway" style="width:100%">
      <a href="#" class="xp-border">Visit Norway »</a>
    </div>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Card Dropdowns</h2>
  <p>Move the mouse over "London" or "Tokyo":</p>

  <div class="xp-dropdown-hover">London
    <div class="xp-dropdown-content xp-card-4" style="width:250px">
      <img src="https://www.w3schools.com/w3css/img_london.jpg" alt="London" style="width:100%">
      <div class="xp-container">
        <p>London is the capital city of England.</p>
        <p>It is the most populous city in the UK.</p>
      </div>
    </div>
  </div>
  
  <div class="xp-dropdown-hover">Tokyo
    <div class="xp-dropdown-content xp-card-4" style="width:250px">
      <img src="https://www.w3schools.com/w3css/img_tokyo.jpg" alt="Tokyo" style="width:100%">
      <div class="xp-container">
        <p>Tokyo is the capital city of Japan.</p>
        <p>13 million inhabitants.</p>
      </div>
    </div>
  </div>

</div>

  <hr>
  <div class="xp-container">
  <h2>Right-aligned Dropdown</h2>
  <p>Use the xp-right class to float the dropdown to the right, and use CSS to position the dropdown content (right:0 will make the dropdown menu go from right to left).</p>

  <div class="xp-dropdown-hover xp-right">
    <button class="xp-button xp-black">Dropdown</button>
    <div class="xp-dropdown-content xp-bar-block xp-border" style="right:0">
      <a href="#" class="xp-bar-item xp-button">Link 1</a>
      <a href="#" class="xp-bar-item xp-button">Link 2</a>
      <a href="#" class="xp-bar-item xp-button">Link 3</a>
    </div>
  </div>

  <div class="xp-clear"></div>
  
  <p>Note: Remember to clear floats if you use xp-right or xp-left. Remove the div class="xp-clear" to understand why.</p>
</div>
  <hr>
 <div class="xp-container">

<h2>Accordions</h2>
<p>An accordion is used to show (and hide) HTML content:</p>
  
<button onclick="myFunction('Demo1')" class="xp-btn xp-block xp-black xp-left-align">Open Section 1</button>
<div id="Demo1" class="xp-container xp-hide">
  <h4>Section 1</h4>
  <p>Some text..</p>
</div>

</div>
  <hr>
  <h2>Accordion Buttons</h2>
<p>You can use any HTML element to open the accordion content. We prefer a button with a xp-block class, because it spans the entire width of its parent element, just like the accordion content (100% width). Remember that buttons in xp.CSS are centered by default. Use the xp-left-align class if you want them left aligned instead. However, you do not have to follow our approach.</p>

<button onclick="myFunction('Demo1')" class="xp-button xp-light-grey">
Normal button</button>

<div id="Demo1" class="xp-hide xp-container xp-light-grey">
  <p>Lorem ipsum...</p>
</div>
<button onclick="myFunction('Demo2')" class="xp-button xp-block xp-left-align xp-green">
Left aligned and full-width</button>

<div id="Demo2" class="xp-hide xp-container">
  <p>Lorem ipsum...</p>
</div>

<button onclick="myFunction('Demo3')" class="xp-btn xp-block xp-red">
Centered and full-width</button>

<div id="Demo3" class="xp-hide xp-container xp-center xp-pale-red">
  <p>Centered content as well!</p>
</div>

</div>
<div class="xp-container">
  <h2>Navigation Bars</h2>
  <p>The <strong>xp-bar</strong> class is a container for displaying HTML elements horizontally.</p>
  <p>The <strong>xp-bar-item</strong> class defines the container elements.</p>
  <p>It it a perfect tool for creating navigation bars:</p>
</div>

<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
  
  <hr>
  <div class="xp-container">
<h2>Responsive Navigation Bars</h2>

<p>The <strong>xp-mobile</strong> class defines responsive elements.</p>
<p>On medium and large screens (tablets and desktops), the bar items will appear side by side horizontally. On smalls screens (smartphones), the items are vertically and centered:</p>
<p><strong>Resize the browser window to see the effect.</strong></p>

<p>Default navigation bar:</p>
<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>Responsive navigation bar:</p>
<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button xp-mobile">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Link 3</a>
</div>
</div>

  <hr>
  <div class="xp-container">

<h2>Colored Navigation Bars</h2>
<p>Use the xp-color class to add a background color to the navigation bar:</p>

<div class="xp-bar xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
<br>
<div class="xp-bar xp-green">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
<br>
<div class="xp-bar xp-blue">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
<br>
<div class="xp-bar xp-red">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
<br>
<div class="xp-bar xp-blue-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Bordered Navigation Bars</h2>
<p>Use the xp-border class to add borders around the navigation bar:</p>

<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>Use the xp-round classes to add rounded borders:</p>

<div class="xp-bar xp-border xp-round xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>Use the xp-card classes to display the navigation bar as a card:</p>

<div class="xp-bar xp-border xp-card-4 xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>You can also add a border to each link:</p>

<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button xp-border-right">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-border-right">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-border-right">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-border-right">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Active/Current Link</h2>
<p>Add a xp-color class, or the xp-text-color class to the current link to let the user know which page he/she is on:</p>

<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button xp-green">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>
<br>
<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button xp-text-teal">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Hoverable Links</h2>
<p>When you mouse a button, the background color will change to grey.</p>
<p>If you want a different hover color, use any of the <strong>xp-hover-color</strong> classes:</p>

<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Default</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-green">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-blue">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-teal">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Hoverable Links</h2>
<p>When you mouse over a button, the background color will change to grey.</p>
<p>If you want to change the text color instead, turn off the default hover effect with the <strong>xp-hover-none</strong> class, and add a <strong>xp-hover-text</strong> class:</p>

<div class="xp-bar xp-border xp-black">
  <a href="#" class="xp-bar-item xp-button">Default</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-text-grey xp-hover-text-white">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-text-grey xp-hover-text-white">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-text-grey xp-hover-text-white">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Hoverable Links</h2>
<p>Play around with different hover effects:</p>

<div class="xp-bar">
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-black">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-black">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-black">Link 3</a>
</div>
<br>
<div class="xp-bar">
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-green">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-green">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-green">Link 3</a>
</div>
<br>
<div class="xp-bar">
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-blue xp-hover-text-blue">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-blue xp-hover-text-blue">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hover-none xp-border-white xp-bottombar xp-hover-border-blue xp-hover-text-blue">Link 3</a>
</div>
<br>
<div class="xp-bar">
  <a href="#" style="border:5px solid white" class="xp-bar-item xp-button xp-hover-none xp-hover-border-green">Link 1</a>
  <a href="#" style="border:5px solid white" class="xp-bar-item xp-button xp-hover-none xp-hover-border-red">Link 2</a>
  <a href="#" style="border:5px solid white" class="xp-bar-item xp-button xp-hover-none xp-hover-border-blue">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Right-Align Links</h2>
<p>To right-align elements in the navigation bar, add the xp-right class:</p>

<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-green xp-right">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">
<h2>Navigation Bar Sizes</h2>
<p>Add the xp-small, xp-large, xp-xlarge or xp-xxlarge to change the size of the navigation (will change the font-size of each link).</p>

<p>Default:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>xp-large:</p>
<div class="xp-bar xp-border xp-green xp-large">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>xp-xlarge:</p>
<div class="xp-bar xp-border xp-green xp-xlarge">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>xp-xxlarge:</p>
<div class="xp-bar xp-border xp-green xp-xxlarge">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<p>If you want more space between each link, instead of increasing the font-size, you could add a xp-padding-classes to each link:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-container">

<h2>Navigation Bar Sizes</h2>
<p>Add the xp-padding-classes to change the padding of each element inside the navigation bar.</p>

<p>xp-padding-small:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Link 2</a>
</div>

<p>Default:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>

<p>xp-padding-large:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Link 2</a>
</div>

<p>xp-padding-16:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 2</a>
</div>

<p>xp-padding-24:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Link 2</a>
</div>

<p>xp-padding-32:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Link 2</a>
</div>

<p><strong>Note:</strong> You can also add padding to the navigation bar, instead of each link. However, if you do this, note that the links do not get full padding on hover:</p>
<p>xp-padding-small:</p>
<div class="xp-bar xp-border xp-green xp-padding-small">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>
<p>xp-padding:</p>
<div class="xp-bar xp-border xp-green xp-padding">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>
<p>xp-padding-large:</p>
<div class="xp-bar xp-border xp-green xp-padding-large">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>

</div>
  <hr>
  <h2>Navigation Bar Sizes</h2>
<p>Add the xp-padding-classes to change the padding of each element inside the navigation bar.</p>

<p>xp-padding-small:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-small">Link 2</a>
</div>

<p>Default:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>

<p>xp-padding-large:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-large">Link 2</a>
</div>

<p>xp-padding-16:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-16">Link 2</a>
</div>

<p>xp-padding-24:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-24">Link 2</a>
</div>

<p>xp-padding-32:</p>
<div class="xp-bar xp-border xp-green">
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-padding-32">Link 2</a>
</div>

<p><strong>Note:</strong> You can also add padding to the navigation bar, instead of each link. However, if you do this, note that the links do not get full padding on hover:</p>
<p>xp-padding-small:</p>
<div class="xp-bar xp-border xp-green xp-padding-small">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>
<p>xp-padding:</p>
<div class="xp-bar xp-border xp-green xp-padding">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>
<p>xp-padding-large:</p>
<div class="xp-bar xp-border xp-green xp-padding-large">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
</div>

</div>
  <hr>
  <div class="xp-container">
<h2>Navigation Bar Sizes</h2>
<p>Customize the width of the list items with the width property (Note: on smaller screens, they will transform to 100%):</p>

<p>Default with two items:</p>
<div class="xp-bar xp-border xp-light-grey">
  <a href="#" class="xp-bar-item xp-button xp-mobile xp-green">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
</div>

<p>Two items, customized:</p>
<div class="xp-bar xp-border xp-light-grey">
  <a href="#" style="width:50%" class="xp-bar-item xp-button xp-mobile xp-green">Link 1</a>
  <a href="#" style="width:50%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
</div>

<p>Two items <strong>centered:</strong></p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:50%" class="xp-bar-item xp-button xp-mobile xp-green">Link 1</a>
  <a href="#" style="width:50%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
</div>

<p>Three items:</p>
<div class="xp-bar xp-border xp-light-grey">
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile xp-green">Link 1</a>
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile">Link 3</a>
</div>

<p>Three items <strong>centered:</strong></p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile">Link 1</a>
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" style="width:33.33%" class="xp-bar-item xp-button xp-mobile">Link 3</a>
</div>

<p>Four items:</p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:25%" class="xp-bar-item xp-button xp-mobile">Link 1</a>
  <a href="#" style="width:25%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" style="width:25%" class="xp-bar-item xp-button xp-mobile">Link 3</a>
  <a href="#" style="width:25%" class="xp-bar-item xp-button xp-mobile">Link 4</a>
</div>

<p>Five items:</p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:20%" class="xp-bar-item xp-button xp-mobile">Link 1</a>
  <a href="#" style="width:20%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" style="width:20%" class="xp-bar-item xp-button xp-mobile">Link 3</a>
  <a href="#" style="width:20%" class="xp-bar-item xp-button xp-mobile">Link 4</a>
  <a href="#" style="width:20%" class="xp-bar-item xp-button xp-mobile">Link 5</a>
</div>

<p>Six items:</p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 1</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 2</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 3</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 4</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 5</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link 6</a>
</div>

<p>Other examples:</p>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:50%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:12.5%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:12.5%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:12.5%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:12.5%" class="xp-bar-item xp-button xp-mobile">Link</a>
</div>
<br>

<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:66.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
</div>

<br>
<div class="xp-bar xp-border xp-light-grey xp-center">
  <a href="#" style="width:16.66%" class="xp-hide-small">
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:16.66%" class="xp-bar-item xp-button xp-mobile">Link</a>
  <a href="#" style="width:16.66%" class="xp-hide-small">
</div>
</div>
  <hr>
  <div class="xp-container">

<h2>Navigation Bar with Icons</h2>

<p>xp-small:</p>
<div class="xp-bar xp-light-grey xp-border xp-small">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

<p>Default:</p>
<div class="xp-bar xp-light-grey xp-border">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

<p>xp-large:</p>
<div class="xp-bar xp-light-grey xp-border xp-large">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

<p>xp-xlarge:</p>
<div class="xp-bar xp-light-grey xp-border xp-xlarge">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

<p>xp-xxlarge:</p>
<div class="xp-bar xp-light-grey xp-border xp-xxlarge">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

<p>xp-xxxlarge:</p>
<div class="xp-bar xp-light-grey xp-border xp-xxxlarge">
  <a href="#" class="xp-bar-item xp-button xp-green"><i class="fa fa-home"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-search"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-envelope"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-globe"></i></a>
  <a href="#" class="xp-bar-item xp-button"><i class="fa fa-sign-in"></i></a>
</div>

</div>
  <hr>
  <div class="xp-container">
  <h2>xp-bar-item</h2>
  <p>If you want text instead of buttons inside the navigation bar, use the xp-bar-item class to get the same padding as the buttons:</p>
</div>

<div class="xp-bar xp-black">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
  <span class="xp-bar-item">More Text</span>
</div>
  <hr>
  <div class="xp-container">
  <h2>Navigation Bar with Input and Buttons</h2>

  <p>Input and button inside navbar:</p>
  <div class="xp-bar xp-light-grey xp-border">
    <a href="#" class="xp-bar-item xp-button xp-mobile">Home</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 1</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
    <input type="text" class="xp-bar-item xp-input xp-white xp-mobile" placeholder="Search..">
    <button class="xp-bar-item xp-button xp-green xp-mobile">Go</button>
  </div>
  
  <p>Padded navbar:</p>
  <div class="xp-bar xp-light-grey xp-border xp-padding">
    <a href="#" class="xp-bar-item xp-button xp-mobile">Home</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 1</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
    <input type="text" class="xp-bar-item xp-input xp-white xp-mobile" placeholder="Search..">
    <button class="xp-bar-item xp-button xp-green xp-mobile">Go</button>
  </div>
</div>

  <hr>
  <div class="xp-container">
  <h2>Navigation Bar with Dropdown</h2>
  <p>Add a dropdown menu inside the navigation bar:</p>

  <div class="xp-bar xp-light-grey">
    <a href="#" class="xp-bar-item xp-button">Home</a>
    <a href="#" class="xp-bar-item xp-button">Link 1</a>
    <div class="xp-dropdown-hover">
      <button class="xp-button">Dropdown</button>
      <div class="xp-dropdown-content xp-bar-block xp-card-4">
        <a href="#" class="xp-bar-item xp-button">Link 1</a>
        <a href="#" class="xp-bar-item xp-button">Link 2</a>
        <a href="#" class="xp-bar-item xp-button">Link 3</a>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Navigation Bar with Dropdown</h2>
  <p>In this example, we remove the xp-bar-block class from xp-dropdown-content, to horizontally align the dropdown links (instead of vertically).</p>

  <div class="xp-bar xp-light-grey">
    <a href="#" class="xp-bar-item xp-button">Home</a>
    <a href="#" class="xp-bar-item xp-button">Link 1</a>
    <div class="xp-dropdown-hover">
      <button class="xp-button">Dropdown</button>
      <div class="xp-dropdown-content xp-card-4">
        <a href="#" class="xp-bar-item xp-button">Link 1</a>
        <a href="#" class="xp-bar-item xp-button">Link 2</a>
        <a href="#" class="xp-bar-item xp-button">Link 3</a>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-container">
  <h2>Responsive navbar with responsive dropdown</h2>
  <p>Resize the browser window to see the result:</p>

  <div class="xp-bar xp-black">
    <a href="#" class="xp-bar-item xp-button xp-mobile xp-green">Home</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 1</a>
    <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
    <div class="xp-dropdown-hover xp-mobile">
      <button class="xp-button">Dropdown <i class="fa fa-caret-down"></i></button>
      <div class="xp-dropdown-content xp-bar-block xp-dark-grey">
        <a href="#" class="xp-bar-item xp-button xp-mobile">Link 1</a>
        <a href="#" class="xp-bar-item xp-button xp-mobile">Link 2</a>
        <a href="#" class="xp-bar-item xp-button xp-mobile">Link 3</a>
      </div>
    </div>
  </div>
</div>
  <hr>
  <div class="xp-top">
  <div class="xp-bar xp-red">
    <a href="#" class="xp-bar-item xp-button">Home</a>
    <a href="#" class="xp-bar-item xp-button">Link 1</a>
    <a href="#" class="xp-bar-item xp-button">Link 2</a>
    <a href="#" class="xp-bar-item xp-button">Link 3</a>
  </div>
</div>

<br><br>

<div class="xp-container">
  <h2>Fixed Top Navigation</h2>
  <h3>The xp-top class forces the navigation bar to stay at the top of the page, even when the user scrolls the page.</h3>
  <h3>Scroll this page to see the effect.</h3>
  <p>Some text to enable scrolling..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
</div>
  <hr>
  <div class="xp-bottom">
  <div class="xp-bar xp-red">
    <a href="#" class="xp-bar-item xp-button">Home</a>
    <a href="#" class="xp-bar-item xp-button">Link 1</a>
    <a href="#" class="xp-bar-item xp-button">Link 2</a>
    <a href="#" class="xp-bar-item xp-button">Link 3</a>
  </div>
</div>

<div class="xp-container">
  <h2>Fixed Bottom Navigation</h2>
  <h3>The xp-bottom class forces the navigation bar to stay at the bottom of the page, even when the user scrolls the page.</h3>
  <h3>Scroll this page to see the effect.</h3>
  <p>Some text to enable scrolling..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
  <p>Some text some text some text some text..</p>
</div>

  <hr>
  <div class="xp-container">

<h2>Navigation Bars</h2>
<p>The <strong>xp-bar-block</strong> class is a container for displaying HTML elements vertically.</p>
<p>The <strong>xp-bar-item</strong> class defines the container elements.</p>

<div class="xp-bar-block xp-light-grey">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

</div>
  <hr>
  <div class="xp-bar xp-red">
  <a href="#" class="xp-bar-item xp-button">Home</a>
  <a href="#" class="xp-bar-item xp-button xp-hide-small">Link 1</a>
  <a href="#" class="xp-bar-item xp-button xp-hide-small">Link 2</a>
  <a href="#" class="xp-bar-item xp-button xp-hide-small">Link 3</a>
  <a href="javascript:void(0)" class="xp-bar-item xp-button xp-right xp-hide-large xp-hide-medium" onclick="myFunction()">&#9776;</a>
</div>

<div id="demo" class="xp-bar-block xp-red xp-hide xp-hide-large xp-hide-medium">
  <a href="#" class="xp-bar-item xp-button">Link 1</a>
  <a href="#" class="xp-bar-item xp-button">Link 2</a>
  <a href="#" class="xp-bar-item xp-button">Link 3</a>
</div>

<div class="xp-container">
  <p>In the example, the navigation bar is replaced with a button (☰) in the top right corner when shown on tablets and mobile devices. When the button is clicked, the links in the bar will vertically stack.</p>
  <p>Resize the screen to see the effect.</p>
</div>
  <hr>
    

  <hr>
 <!------------>
<div class="column">
  
<h1 class=" overunderline-txt" style="color:#eb7700;"> EXAMPLES</h1>
<span-caps class="overunderline-txt" >BUTTONS</span-caps><br>
  <p><i> Rectangular written with class btn-RT:</i> </p>
 <div class="container">
  <div class="column">
      <div><button class=" primary-btn-RT ">Primary</button></div></div>
	  <div class="column">
<div><button class="success-btn-RT ">Success</button></div></div>
<div class="column">
<div><button class="info-btn-RT ">info</button></div></div>
<div class="column">
<div><button class="warning-btn-RT ">warning</button></div></div>
<div class="column">
<div><button class="danger-btn-RT ">danger</button></div></div>
<div class="column">
<div><button class="default-btn-RT ">default</button></div></div>
<div class="column">
<div><button class="inverse-btn-RT ">inverse</button></div></div>
    </div>

 <p><i> Rectangular written with class btn-RT btn-corners:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-RT btn-corners">Primary</button></div>
<div><button class="success-btn-RT btn-corners ">Success</button></div>
<div><button class="info-btn-RT btn-corners ">info</button></div>
<div><button class="warning-btn-RT btn-corners ">warning</button></div>
<div><button class="danger-btn-RT btn-corners ">danger</button></div>
<div><button class="default-btn-RT btn-corners ">default</button></div>
<div><button class="inverse-btn-RT btn-corners ">inverse</button></div>
    </div></div></div>

  <p><i> Rectangular written with class btn-RT btn-oval:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-RT btn-oval">Primary</button></div>
<div><button class="success-btn-RT btn-oval ">Success</button></div>
<div><button class="info-btn-RT btn-oval ">info</button></div>
<div><button class="warning-btn-RT btn-oval ">warning</button></div>
<div><button class="danger-btn-RT btn-oval ">danger</button></div>
<div><button class="default-btn-RT btn-oval ">default</button></div>
<div><button class="inverse-btn-RT btn-oval ">inverse</button></div>
    </div></div></div>
<br>
  <p><i> ANIMATED BUTTON -1 written with class btn-1 btn-1a:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-1 btn-1a">Primary1</button></div>
<div><button class="success-btn-1 btn-1a ">Success1</button></div>
<div><button class="info-btn-1 btn-1a ">info1</button></div>
<div><button class="warning-btn-1 btn-1a ">warning1</button></div>
<div><button class="danger-btn-1 btn-1a ">danger1</button></div>
<div><button class="default-btn-1 btn-1a ">default1</button></div>
<div><button class="inverse-btn-1 btn-1a ">inverse1</button></div>
    </div></div></div>
   <p><i> ANIMATED BUTTON -1 making it oval with class btn-1 btn-corners:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-1 btn-1a btn-corners">Primary1</button></div>
<div><button class="success-btn-1 btn-1a btn-corners">Success1</button></div>
<div><button class="info-btn-1 btn-1a btn-corners">info1</button></div>
<div><button class="warning-btn-1 btn-1a btn-corners">warning1</button></div>
<div><button class="danger-btn-1 btn-1a btn-corners">danger1</button></div>
<div><button class="default-btn-1 btn-1a btn-corners">default1</button></div>
<div><button class="inverse-btn-1 btn-1a btn-corners">inverse1</button></div>
    </div></div></div>

  <p><i> ANIMATED BUTTON -1 making it oval with class btn-1  btn-oval:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-1 btn-1a btn-oval">Primary1</button></div>
<div><button class="success-btn-1 btn-1a btn-oval">Success1</button></div>
<div><button class="info-btn-1 btn-1a btn-oval">info1</button></div>
<div><button class="warning-btn-1 btn-1a btn-oval">warning1</button></div>
<div><button class="danger-btn-1 btn-1a btn-oval">danger1</button></div>
<div><button class="default-btn-1 btn-1a btn-oval">default1</button></div>
<div><button class="inverse-btn-1 btn-1a btn-oval">inverse1</button></div>
    </div></div></div>
<br>
 <!------>
  <p><i> ANIMATED BUTTON -2 making it oval with class btn-2 and you can also add classes btn-oval or btn-corners with it:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-2">Primary2</button></div>
<div><button class="success-btn-2">Success2</button></div>
<div><button class="info-btn-2">info2</button></div>
<div><button class="warning-btn-2">warning2</button></div>
<div><button class="danger-btn-2">danger2</button></div>
<div><button class="default-btn-2">default2</button></div>
<div><button class="inverse-btn-2">inverse2</button></div>
    </div></div></div>
<br>
  <!------>
  <p><i> ANIMATED BUTTON -2 making it oval with class btn-2 btn-corners with it:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-2 btn-corners">Primary2</button></div>
<div><button class="success-btn-2 btn-corners">Success2</button></div>
<div><button class="info-btn-2 btn-corners">info2</button></div>
<div><button class="warning-btn-2 btn-corners">warning2</button></div>
<div><button class="danger-btn-2 btn-corners">danger2</button></div>
<div><button class="default-btn-2 btn-corners">default2</button></div>
<div><button class="inverse-btn-2 btn-corners">inverse1</button></div>
    </div></div></div>
<br>
  <!------>
  <p><i> ANIMATED BUTTON -2 making it oval with class btn-2 btn-oval with it:</i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class=" primary-btn-2 btn-oval">Primary2</button></div>
<div><button class="success-btn-2 btn-oval">Success2</button></div>
<div><button class="info-btn-2 btn-oval">info2</button></div>
<div><button class="warning-btn-2 btn-oval">warning2</button></div>
<div><button class="danger-btn-2  btn-oval ">danger2</button></div>
<div><button class="default-btn-2 btn-oval">default2</button></div>
<div><button class="inverse-btn-2 btn-oval">inverse1</button></div>
    </div></div></div>
<br>
  <!------>
  <p><i>btn-3 are stylish buttons. Just add class btn-3 first/second/third/fourth/fifth/sixth </i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button class="btn-3 first">first</button></div>
<div><button class="btn-3 second">second</button></div>
<div><button class="btn-3 third">third</button></div>
<div><button class="btn-3 fourth">fourth</button></div>
<div><button class="btn-3 fifth  btn-oval ">fifth</button></div>
<div><button class="btn-3 sixth btn-oval">sixth</button></div>
<div><button class="btn-3 first btn-corners">first btn-corners</button></div>
    </div></div></div>
<br>
   <!------>
  <p><i>create your own stylish buttons. Just add classes and sub classes first/second/third/fourth/fifth/sixth </i> </p> 
  <div class="container">
  <div class="column">
    <div class="panel element">
      <div><button style="background-color:black;" class="overunderline-txt  xp-txt fourth btn-corners"><p >Submit form </p></button></div>

      
    <div><button><p class="overunderline-txt xp-txt">Print here</p></button></div>
<div><button><p class=" border-mix">Reports</p></button></div>
    
    </div></div></div>
<br>
 <span-caps class="overunderline-txt" >Unstructured List</span-caps><br>
  <ul class="ul-square underline-txt" style="color:#eb7700;"><li>Circle</li></ul>
  <p><i> (written with class ul-circle)</i> </p>
  <ul class="ul-circle" >
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
  </ul>
  <ul class="ul-square underline-txt" style="color:#eb7700;"><li>Square</li></ul>
  <p><i> (written with class ul-square)</i> </p>
  <ul class="ul-square" >
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
  </ul>
  <ul class="ul-square underline-txt" style="color:#eb7700;"><li>Upper Roman</li></ul>
  <p><i> (written with class ol-uromman)</i> </p>
  <ul class="ol-uromman" >
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
  </ul>
  <ul class="ul-square underline-txt" style="color:#eb7700;"><li>ordered Alphabetical</li></ul>
  <p><i> (written with class ol-lalpha)</i> </p>
  <ul class="ol-lalpha" >
  <li>Coffee</li>
  <li>Tea</li>
  <li>Coca Cola</li>
  </ul>
</div>
<span-caps class="overunderline-txt" >TEXT DECORATIONS</span-caps><br>
<p><i>written with class overline-txt:</i> </p>
  <h4 class= "overline-txt"> This is overline text written with class overline-txt</h4>
<p><i>written with class strike-txt:</i> </p>
<h4 class= "strike-txt"> This is overline text written with class strike-txt </h4>
<p><i>written with class underline-txt:</i> </p>
<h4 class= "underline-txt"> This is overline text written with class underline-txt </h4>
<p><i> written with class overunderline-txt:</i> </p>
<h4 class= "overunderline-txt"> This is overline text written with class overunderline-txt</h4>
<hr>
<h5 class="border-dotted">A dotted border written with class <span-bold>border-dotted</span-bold><span-caps>. This is written inside span-caps tags </sapn-caps></h5>
<h5 class="border-dashed">A dashed border written with class <span-caps> border-dashed</span-caps> <span-bold>. This is wiritten inside span-bold tags </sapn-bold></h5>
<h5 class="border-solid">A solid border written with class border-solid</h5>
<h5 class="border-double">A double border written with class border-double</h5>
<h5 class="border-groove">A groove border written with class border-groove</h5>
<h5 class="border-ridge">A ridge border written with class border-ridge</h5>
<h5 class="border-inset">An inset border written with class border-inset</h5>
<h5 class="border-outset">An outset border written with class border-outset</h5>
<h5 class="border-none">No border written with class border-none</h5>
<h5 class="border-hidden">A hidden border written with class border-hidden</h5>
<h5 class="border-mix">A mixed border written with class border-mix</h5>

<div class="column">
  <h1>This is Written in Tag h1</h1>
  <h2>This is written in tag h2</h2>
  <h3>This is written in tag h3</h3>
  <h4>This is written in tag h4</h4>
  <h5>This is written in tag h5</h5>
  <h6>This is written in tag h6</h6>
   <p>This is written in tag p</p>
</div>


<div class="container">
  <div class="panel">
    <div class="element"><p>Rihand Dam (Hindi: रिहन्द बांध) is a concrete gravity dam located at Pipri in Sonbhadra District in Uttar Pradesh, India.  <p/> </div>
    <div class="element"><p>Its reservoir area is on the border of Madhya pradesh and Uttar Pradesh. This reservoir is known as Govind Ballabh Pant Sagar.</p></div>
    <div class="element">c</div>
  </div>
</div>

<div class="container">
  <div class="column">
    <div class="panel">
      <div class="element">a1</div>
      <div class="element">b</div>
      <div class="element">c</div>
    </div>
  </div>
  
  <div class="column">
    <div class="panel">
      <div class="element">a2</div>
      <div class="element">b</div>
      <div class="element">c</div>
    </div>
  </div>
  <div class="column">
    <div class="panel">
      <div class="element">a</div>
      <div class="element">b</div>
      <div class="element">c</div>
    </div>
  </div>
  
</div>

<div class="panel">
  <div class="element"><p>Rihand Dam (Hindi: रिहन्द बांध) is a concrete gravity dam located at Pipri in Sonbhadra District in Uttar Pradesh, India. </p></div>
</div>
<!-- partial -->
  
</body>
</html>



