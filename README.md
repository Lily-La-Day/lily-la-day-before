# My First Webpage 

**Created in April/May 2019 (before I knew things!)**


This was my very first attempt at coding a webpage. It is (the beginnings of at least) a personal website and was created  before I was comfortable using GitHub and definitely before I was comfortable using JavaScript.

Having said that, looking back (as much as the JavaScript is hilarious) I am quite proud of what I managed to achieve here as I really was totally making it up as I went along and had no idea what I was doing. Which, let's face it - I still am and to a certain extent, and probably still will be in five years time when (touch wood, fingers crossed etc) I am a fully fledged professional web developer. 


**Overview** 

This site is made up of a homepage that displays links to further pages each of which shows (or was intended to show) information/further links to things that are in some way relevant to me or things that I do. 

**The Homepage**

Link to hosted site: https://lily-la-day.github.io/lily-la-day-before/

Looking back, the creation of this homepage was quite an ambitious "first code challenge", I am very lucky that I started coding in the age of CSS Grid as implementing this using floats or even flexbox would have been no where near as simple for a proper beginner. It obviously was a bit backward of me to learn Grid before any other positioning techniques though as I am aware that is not universally supported so I am very thankful to have been introduced to the full range of old school (and not so old school) alternative methods during bootcamp. 

Even with Grid this was quite a lot of work, not only because ever single step neccessitated a full google and a lot of trial and error but also just in the set-up. Getting all those images the right size and in exactly the right place in the right pair etc etc.

As a bit of background, the images are (evidently maybe?) images of me, the photos taken that I used to work from and then the self-portrait created from a year long one-a-day series of 365 self-portraits I did back when I was more of an artist than a coder (now it's like, 20-80 with coder on the right, though maybe coding is art right?!). 

<img src="https://i.ibb.co/L6mX2tm/home.png" width="700">

The photo display becomes 'none' and the portrait image is revealed on mouseover.


**The Crossword**

I bloody love this crossword I do, partly because I am very proud of myself for managing to make it all on my lonesome in the first place but mostly because looking at the code and remembering the experience of writing it compared to that of the crossword that I have very recently made for my actual, proper portfolio I am just amazed at how far I have come and how much I have learned in such as short space of time. It's a great feeling! I think I might have to make another one in six months and then every 6 months forever so that I may track my career and progression via the standard of my crossword output. 

I have no idea why it is so large and the JavaScript could not be less DRY if it were an actual deep sea fish but hey! I did my best. 

The crossword: <th><p align="center"><img src="https://i.ibb.co/tKp7HWS/crossword-old.png" width="700"></p></th>


  And a link : 

https://lily-la-day.github.io/lily-la-day-before/crossword.html


  And the new one (for comparison):
 
 <th><p align="center"><img src="https://i.ibb.co/8DWQKGT/crossword-new.png" width="700"></p></th>
 
 http://lily-la-day.com/

  Just a snapshot of the (hilarious) JavaScript code that fills in the words when the clues are clicked: 

```js
function answerAppear4a() {
    document.getElementById("painter").style.opacity = 1;
    document.getElementById("ainter").style.opacity = 1
    document.getElementById("ainter").style.opacity = 1
    document.getElementById("inter").style.opacity = 1
    document.getElementById("nter").style.opacity = 1
    document.getElementById("ter").style.opacity = 1
    document.getElementById("er").style.opacity = 1
    document.getElementById("r").style.opacity = 1

};

function answerAppear9() {
    document.getElementById("signs").style.opacity = 1
    document.getElementById("amaritan").style.opacity = 1
    document.getElementById("maritan").style.opacity = 1
    document.getElementById("aritan").style.opacity = 1
      document.getElementById("rwinism").style.opacity = 1
        document.getElementById("itan").style.opacity = 1
    document.getElementById("tan").style.opacity = 1
    document.getElementById("an").style.opacity = 1
    document.getElementById("n").style.opacity = 1
};

function answerAppear10() {
    document.getElementById("muser").style.opacity = 1;
    document.getElementById("user").style.opacity = 1
    document.getElementById("ser").style.opacity = 1
    document.getElementById("er2").style.opacity = 1
    document.getElementById("r2").style.opacity = 1

};

function answerAppear11() {
    document.getElementById("gns").style.opacity = 1;
    document.getElementById("enii").style.opacity = 1
    document.getElementById("nii").style.opacity = 1
    document.getElementById("ni").style.opacity = 1
    document.getElementById("inism").style.opacity = 1

};

function answerAppear12() {
    document.getElementById("utilisers").style.opacity = 1;
    document.getElementById("tilisers").style.opacity = 1
    document.getElementById("ilisers").style.opacity = 1
    document.getElementById("lisers").style.opacity = 1
    document.getElementById("isers").style.opacity = 1
    document.getElementById("sers").style.opacity = 1
    document.getElementById("ers").style.opacity = 1
    document.getElementById("rs").style.opacity = 1
    document.getElementById("s2").style.opacity = 1

};

function answerAppear13() {
    document.getElementById("s").style.opacity = 1;
    document.getElementById("panish").style.opacity = 1
    document.getElementById("anish").style.opacity = 1
    document.getElementById("nish").style.opacity = 1
    document.getElementById("ism").style.opacity = 1
    document.getElementById("sh").style.opacity = 1
    document.getElementById("h").style.opacity = 1

};

function answerAppear15() {
    document.getElementById("drum").style.opacity = 1;
    document.getElementById("rum").style.opacity = 1
    document.getElementById("um").style.opacity = 1
    document.getElementById("m2").style.opacity = 1


};

function answerAppear17() {
    document.getElementById("salmon").style.opacity = 1;
    document.getElementById("almon").style.opacity = 1
    document.getElementById("lmon").style.opacity = 1
    document.getElementById("m").style.opacity = 1
    document.getElementById("on").style.opacity = 1
    document.getElementById("n3").style.opacity = 1


};

function answerAppear18() {
    document.getElementById("raves").style.opacity = 1;
    document.getElementById("aves").style.opacity = 1
    document.getElementById("ves").style.opacity = 1
    document.getElementById("es2").style.opacity = 1
    document.getElementById("s3").style.opacity = 1;
  };
  ```
  
  (And that really is just a tiny snippet of it!!)
  
  So, in conclusion:

  I have learned a lot!
  
  





