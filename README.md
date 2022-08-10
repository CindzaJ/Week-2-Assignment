# Week-2-Assignment
Week2 Assignment - Self Intro 

WEBPAGE 1:
<!DOCTYPE html>
<html lang="en-US">
    <!-- TODO: Write Your Code Below-->
  <head>
    <meta charset="UTF-8">
    <title>Welcome to my Student Bio!</title>
    <header>
    <h1>Student Bio: Cindy J.</h1>
    </header>
  </head>
  <style>
    body{
        background-image: url("Ace.png");
      }
      footer{
      position: fixed;
      left:0;
      bottom:0;
      width: 100%;
      text-align: center;
    }
  </style>
  <link rel="stylesheet" href="styles.css">
  <body>
  <div class="row">
    <div class="column">
      <h2>ABOUT THIS PAGE<br>
        <br>So, you have finally arrived here at my Utopia for now…<br><br>This is just a quick snapshot of myself Intro, just to allow you to get to know a little bit about me.
      We don’t necessarily have to be the same.
      In fact, the beauty of it is that we are uniquely different in our own ways.</h2>
      </div>
    <div class="column">
      <p><br><br><br>Welcome & Enjoy your stay!</p>
      </div>
    <div class="column">
    <h2>WHAT I REALLY LIKE:<br>
      <br>Learning news things about Coding.</br>
      <br>Writing for fun!</br> 
      <br>Arts & Crafts - Just to practice in my own time.</br>
      <br>Reading Books in Life & about People in general:  My preferred genres would be either Fiction & Autobiography.</br>
    </h2>
  </div>
  <footer>
    <h2><u><a href="Webpage2.html">Please Click Here</a></u></h2>
    <h3>Trilogy July 2022</h3>
  </footer>
  </body>
</html>

CSS for Webpage 1
body,html,link{
    height: 120%;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-style: bold;
    color:aliceblue
}
header{
    padding: 20px;
    text-align: right;
    font-size: 30px;
    justify-content: space-between;
    margin: 30px
}
div{
    flex-wrap: fixed;
        float: left;
        width: 100%;
        padding: 5px;
        justify-content: left;
      }
h1{font-size: 70px;
    text-align: center;
    justify-content: space-evenly;
} 
h2{font-size: 32px;
    text-align: center;
    justify-content: space-between
} 
div{
    text-align:center;
    font-size: medium;
    display: flex;
    justify-content: center;
}
bg{
background-image: url("Ace.png");
height: 60%;
background-position:center;
background-repeat: no-repeat;
background-size:auto;
}
p{
    font-size: 36px;
    font-style: italic;
    text-align: left;
    justify-content: left;
    text-decoration: dashed;
}
a:link{
color:aliceblue
}
a:visited{
color: aliceblue;
}
footer{
padding: 50px;
text-align: center;
font-style: italic;
}

WEBPAGE 2 
<!DOCTYPE html>
<html lang="en-US">
  <header>
    <meta charset="UTF-8">
    <title>Fun Facts About Me</title>
    <link rel="stylesheet" href="Webpage2 CSS.css">
  </header>
  <body>
      <div class="column"><h1>FAVOURITE FOODS</h1><br>
      <li>I think I am grateful to have the ability to appreciate all cuisines if it either <strong><i>Vegetarian  + Gluten Free.</i></strong>
        Just because it is my preferred life-style, due to my family religion.</li><br>
      <li>As <strong><u>Buddism & Taosim</strong></u> had always been an important part of my family culture, I was able to learn and understand how things could work a bit in a spiritual manner, which I personally find it very healing.</li>
      </div>
      <div class="column">
     <h1>PILOT & KNIGHT</h1><br><br>
        <li>For some of you might or might not know, I have  2 cats at Home, namely <strong>Pilot & Knight.</strong> And they are the best Cats I could ever ask for.</li><br>
        <li>Pilot is 7yrs old Persian Ragdoll who likes to pick his favourites.<strong><br></li>
        <li>You can view his photo here: </strong><a href="P2.jpeg"><strong>PILOT</strong></a></li>
        <br><li>Knight on the other hand, is a 3yrs old <i>Blue Mitten Ragdoll</i> who have a characteristics of a Puppy.</li><br>
        <li>Comparatively, he is super cheerful and pretty much does not share any associations with your typical Ragdoll Cats which are traditionally known to be more demure and quiet.</li><br>
        <li>I gave Knight his name just because he like to protect & patrol.</li><br>
        <li>You can view his photo here: <a href="K1.jpeg"><strong>KNIGHT</strong></a></li>
      </div>
    <div class="column">
    <h1>DO YOU WANT TO CONNECT? <br>THEN CONTACT US:</h1><br>
        <h2><strong>EMAIL US:</strong> <a href= "mailto:Aimingforhd@gmail.com?subject=subject text">Aimingforhd@gmail.com</a></h2>
        <h2><strong>MOBILE:</strong>123 123 124 5</h2>
        <h2><strong>INSTAGRAM:</strong> LOL :)</h2>
        <h2><a href="index.html"><u><i>Back Home</i></u></a></h2>
    </div>
    <style>
      body{
        background-image: url("Ace2.png");
      }
    </style>
  </body>
<footer><strong><i>Triology July 2022</strong></i></footer>

CSS for Webpage 2: 
Webpage2 CSS
body,html,link{
    height: 100%;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    color: aliceblue
    
}
h1{font-size: 65px;
   text-align: center;
   text-shadow: 60px;
   margin: 20px;
   color:greenyellow;
   text-shadow: 10%;
} 
h2{font-size: 30px;
} 
a{
color:greenyellow;
font-style: italic;
}
li{
    font-size: 30px;
    color: aliceblue;
    column-gap: 20px;
    justify-content: center;
}
div{
    flex-wrap: fixed;
    justify-content: right;
    margin: 50px;
        float: none;
        width: 60%;
        padding: 150px;
        /* Source: From https://css.glass */
        background: rgba(244, 231, 231, 0.12);
        border-radius: 30px;
        grid-row: 20px;
        box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
        backdrop-filter: blur(15.5px);
        -webkit-backdrop-filter: blur(15.5px);
        border: 5px solid rgba(244, 231, 231, 0.644);
        display: flex;
        flex-direction: column;
        flex: 200px
     }
p{
font-size: 20px;
columns: 50px;
}
footer{
    justify-content: center;
    text-align: center;
    font-size: 30px;
    margin-top: 20px;
}
