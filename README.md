# KentonMacdonald.github.i
<!DOCTYPE html>
<html lang="en">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Style the header */
.header {
  padding: 140px;
  display: block;
  text-align: center;
  background-image: url('https://drive.google.com/uc?export=view&id=1IIY94zewCwJIeU4lJ5fbcJ1dQCajsZia');
  background-repeat: no-repeat;
  background-attachment: fixed; 
  background-size: 100% 100%;
  color: black;
}

/* Increase the font size of the h1 element */
.header h1 {
  font-size: 40px;
}

/* Style the top navigation bar */
.navbar {
  overflow: hidden;
  background-color: black;
}

/* Style the navigation bar links */
.navbar a {
  float: left;
  display: block;
  color: white;
  text-align: center;
  padding: 14px 20px;
  text-decoration: none;
}

/* Right-aligned link */
.navbar a.right {
  float: right;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #bf9cfb;
  color: whtie;
}

/* Column container */
.row {  
  display: flex;
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  flex: 30%;
  background-color: #e4d5fd;
  padding: 20px;
}

.main p, h1, h2, h5 {
  color: black;
  opacity: 1;
  display: block;
  text-align: left;
  padding: 14px 20px;
  text-decoration: none;
}

/* Main column */
.main {   
  flex: 70%;
  background-color: #f0e8fe;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 40px;
  text-align: center;
  background-image: url('./Dog.jpg');
  background-attachment: fixed; 
  background-size: 10% 10%;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row {   
    flex-direction: column;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .navbar a {
    float: none;
    width:100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>Kentie's Files</h1>
  <p>Store all your data here, we won't sell it to the CCP!</p>
</div>

<div class="navbar">
  <a href="C:\Users\19191\Documents\Project\Photos.html">Photos</a>
  <a href="C:\Users\19191\Documents\Project\Videos.html">Videos</a>

<!--a href="https://kentyfiles.w3spaces-preview.com/Files/Files.html">Files</a> -->

  <a href="C:\Users\19191\Documents\Project\Home" class="right">Home</a>
</div>

<div class="row">
  <div class="side">
    <h2>Quick Access</h2>
    <h5><a href="C:\Users\19191\Documents\Project\Photos">Photos</a></h5>
    <a href="C:\Users\19191\Documents\Project\Photo-Albums\Photo-Album-1.html">Photo album 1</a>
    <br>
    <a href="C:\Users\19191\Documents\Project\Photo-Albums\Photo-Album-2.html">Photo album 2.</a>

    <h5><a href="C:\Users\19191\Documents\Project\Videos">Videos</a></h5>
    <a href="C:\Users\19191\Documents\Project\Video-Albums\Video-Album-1.html">Video album 1.</a>
    <br>
    <a href="C:\Users\19191\Documents\Project\Video-Albums\Video-Album-2.html">Video album 2.</a>

<!--
    h5>a href="https://kentyfiles.w3spaces-preview.com/Files/Files.html">Files</a></h5>
    a href="https://kentyfiles.w3spaces-preview.com/Files/Folder-1/Folder-1.html">Folder 1.</a>
    br>
    a href="https://kentyfiles.w3spaces-preview.com/Files/Folder-2/Folder-2.html">Folder 2.</a>
-->

  </div>
  <div class="main">
    <h2>I MADE A WEBSITE</h2>
    <h5>Update 1, March 24, 2023</h5>
    <p>This is the website</p>
    <p>I made this whole goddamn website. This is mine! I can host images on this website! Sick!</p>
    <br>
    <h2>Early Version</h2>
    <h5>Website Updates</h5>
    <p>This is a very early version</p>
    <p>While the website is functional in so far as it displays images and can host media and files, it is still in it's infancy and is thus far from finished.</p>
  </div>
</div>

<div class="footer">
</div>

</body>
</html>
