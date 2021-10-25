# Profilemaincomponent
UI for responsive profile main component using HTML and CSS only.
# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents



  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview



### Links

- Solution URL: https://github.com/srish-creator
- Live Site URL: https://srish-creator.github.io/Profilemaincomponent/



### Built with

- Semantic HTML5 markup
- CSS custom properties




### What I learned

Used the theoritical knowledge into practice and made the webpage looks identical to given design.

To see how you can add code snippets, see below:

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card Component</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Kumbh+Sans:wght@400;700&display=swap" rel="stylesheet">
    
</head>
<body>
    <main>
<div class="profile">
    <div class="profile-bg"><div>
      <img src="images/image-victor.jpg" class="pic">
    </div>
    </div>
<div class="middle">
    <h3 class="name">Victor Crest<span class="age">26</span> </h3>
    <p class="location">London</p>

</div>
  <div class="lower">
      <table>
        <tr>
            <th class="status_card">
               <h3>80K</h3>
               <small>Followers</small>
            </th>
            <th class="status_card">
                <h3>803K</h3>
                <small>Likes</small>
            </th>
            <th class="status_card">
                <h3>1.4k</h3>
                <small>Photos</small>
            </th>
        </tr>
      </table>
  </div>
    
</div>
</main>
<footer class="copyright"><p>copyright @Srishti 2021</p></footer>
</body>
</html>

```
```css

body{

    text-align: center;
    font-family: 'Kumbh Sans', sans-serif;
  background-color:   hsl(185, 75%, 39%);
    background-image: url( "images/bg-pattern-top.svg"), url("images/bg-pattern-bottom.svg");
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: 700px, 930px;
    background-position: bottom 350px left -25px, top 400px right -200px;
}
.profile{
    margin: auto;
    margin-top: 150px;
    height: 400px;
    width: 380px;
    background-color: white;
    border-radius: 15px;
    text-align: center;
}
.profile-bg{

background-image: url(images/bg-pattern-card.svg);
height: 150px;
border-radius: 15px 15px 0px 0px;
}
.pic{
   
margin-top: 90px;
width: 110px;
height: 110px;
border-radius: 50%;
border-style: solid;
border-color: white;
border-width: 5px;

}
.middle{
    
    margin-top:70px;
 position: relative;
 border-bottom-style:solid;
 border-width: 0.5px;
 border-color:  hsl(0, 0%, 59%);

}
.name,.age{
   padding-top: 15px;
   line-height: 0.5rem;
}
.name{
   
    font-weight: 700;
}
.age,.location{
   color: hsl(0, 0%, 59%);
   font-weight:400;
    padding-left: 10px;
    
}
.location{
    padding-top: 2%;
    padding-bottom: 20px;
    font-size: small; 
   
}
.tag,small{
    color: hsl(0, 0%, 59%);
    font-weight: 400;
    font-size: small;
}

h2,h3{
    margin: 0;
    font-size: 1.25rem;
}

table{
    width: 80%;
    margin: auto;
    margin-top: 5px;
}
.status_card{
position: relative;
padding-left: 15px;
padding-right: 15px;

}
h3,p{
    margin: 10px;
}




@media (max-width:450px) {
    body{
        
    background-size:600px, 700px;
    background-position: bottom 31.25rem left -27rem, top 28rem right -29rem;
}
.profile{
    
    width:  95%;
}
.copy-right{
    margin-top: 10rem;
}

}




### Continued development

After the designing part , I would like to focus on functionality of website and use my js knowledge to be in use.


### Useful resources

- https://stackoverflow.com/ Stack overflow community helped me learn better and whenever i was stuck , it was easy to find people who would explain .

## Author

- Website - [Srishti](https://www.your-site.com)
- Frontend Mentor - [@srish-creator] https://www.frontendmentor.io/profile/srish-creator





