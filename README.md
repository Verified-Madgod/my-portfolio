# my-portfolio

###A repository for my web based portfolio and resume.
This portfolio site only utilizes HTML and CSS but later on will implement some java script as well. Portfolio includes sections on *Game Development*, *Animation*, *2D Art*, *3D Modeling*, as well as a *script repository*.

####TODO:
1. Work on the formatting for the *Game Development* section of my portfolio.
2. Work on the formatting for the *Script Repository* section of my portfolio.
3. Allow the user to add items to their portfolio.
4. Improve Functionality
5. Improve Design

####Completed:
1. Base design of site is completed.
2. Formatting of *2D Art* and *3D Modeling pages* complete 
3. *2D Art* and *3D Modeling* pages of the section formatted are populated with examples

####Notes:
If you plan on using this design for your own purposes here are some things too note.

1. To display objects to the screen you need to create a unordered list (with an id of list) inside of a div (with an id of table). 
```
<div id='table'>
  <ul id='list'>
    <!-- Put your list items (<li>) here -->
  </ul>
</div>
```

2. To display 5 objects to the screen, assign the .five class to the list items (`<li>`) in your unordered list (`<ul>`).
3. To display 3 objects to the screen, assign the .three class to the list items (`<li>`) in your unordered list (`<ul>`).

```
<div id='table'>
  <ul id='list'>
    <li class='five'>Object One</li>
    <li class='five'>Object Two</li>
    <li class='five'>Object Three</li>
    <li class='five'>Object Four</li>
    <li class='five'>Object Five</li>
  </ul>
  
<div id='table'>
  <ul id='list'>
    <li class='three'>Object One</li>
    <li class='three'>Object Two</li>
    <li class='three'>Object Three</li>
  </ul>
</div>
```
