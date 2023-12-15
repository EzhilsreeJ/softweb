# Ex.07 Software Product Company Website
## Date:15.12.2023

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```html
<!DOCTYPE html>
<html>
  <head>
    <meta name="view" content="with=device-width, initial-scale=1.0">
    <title>Ezhil Sree :)</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;400;600;700&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.1/css/fontawesome.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
  <body>
    <section class="header">
      <nav>
        <a href="index.html"> <img src="profile.jpg" class="profile"></a>
        <h3 class="com-name">Ezhil Sree :)</h3>
       
        <div class="nav-links" id="navLinks">
          <i class="fa fa-times" onclick="hideMenu()"></i>
          <ul>
            <li><a href="index.html">HOME</a></li>
            <li><a href="About.html">ABOUT</a></li>
            <li><a href="course.html">COURSE</a></li>
            <li><a href="blog.html">BLOG</a></li>
            <li><a href="contact.html">CONTACT</a></li>
            <li><a href="login.html">LOGIN</a></li>
          </ul>
        </div>
        
        <i class="fa fa-bars" aria-hidden="true" onclick="showMenu()"></i>
      </nav>
      
    <div class="text-box">
      <h1>Way to Success</h1>
      <p>Success is the result of perfection, hard work, learning from failure, loyalty, and persistence.<br> Ready to Success
      </p>
      <a href="About.html" class="hero-btn">Visit us to know More</a>
    </div>
    </section>
<!--COURSE-->
<section class="course">
  <h1>Course We Offer</h1>
  <p>Lorem ipsum dolor sit amet,conswctetur adipiscing elit.</p>

  <div class="row">
    <div class="course-col">
      <h3>Internship</h3>
      <p>we are offering internship for college students,who are studying the department of computers.Topics are Web Development,UX/UI animation design,Data Analyst,Cyber Security and other technical course</p>

    </div>
    <div class="course-col">
      <h3>Inplant Training</h3>
      <p>we are offering inplant Training for college students,who are the final year of Engineering Students.Topics are Web Development,UX/UI animation design,Data Analyst,Cyber Security and other technical course</p>
      
    </div>
    <div class="course-col">
      <h3>Technical Course</h3>
      <p>we are offering technical course for students and also for teaching faculties.We are taking all Technical Courses </p>
      
    </div>
  </div>
</section>
<!--CAMPUS-->

<section class="campus">
<h1>Our Global Campus</h1>
<p>Lorem ipsum dolor sit amet,conswctetur adipiscing elit.</p>
<div class="row">
  <div class="campus-col">
    <img src="campus.jfif">
    <div class="layer">
      <h3>INDIA</h3>
    </div>
  </div>
  <div class="campus-col">
    <img src="campus1.png">
    <div class="layer">
      <h3>AMERICA</h3>
    </div>
  </div>
  <div class="campus-col">
    <img src="campus2.jfif">
    <div class="layer">
      <h3>LONDON</h3>
    </div>
  </div>
</div>
</section>

<!--Facilities-->

<section class="facilities">
<h1>Our Faculties</h1>
<p>Lorem ipsum dolor sit amet,conswctetur adipiscing elit.</p>


<div class="row">
  <div class="facilities-col">
    <img src="profile.jpg"  class="profile-1">

  </div>
  <div class="facilities-col">
    <img src="image.png">
 
  </div>
  <div class="facilities-col">
    <img src="https://cdn.pixabay.com/photo/2023/10/16/03/44/daughter-8318355_640.jpg" >
  
  </div>
</div>
</section>




<!-------------Testimonials---------->


<section class="testimonials">
<h1>What Our Students Says</h1>
<div class="row">
  <div class="testimonial-col">
    <img src="user1.jpg" >
    <div>
      <p>Around 100% of students get placed in our course.
        The highest salary package offered is 17.5 LPA, 
        the lowest salary package is 4 LPA, 
        and the average salary package is 4.5 LPA. 
        The top recruiting company is Virtusa. 
        Around 95% of students get internships in our course.</p>
      <h3>Frankly</h3>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star-o"></i>
    </div>
  </div>
  <div class="testimonial-col">
    <img src="user2.jpg" >
    <div>
      <p> Facilities and infrastructure available for our course are high-speed Wi-Fi. There are different labs like ML lab, VR lab, and robotics lab. Classrooms are the best. Library is great with all kinds of books.</p>
      <h3>Harina</h3>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star"></i>
      <i class="fa fa-star-half-o"></i>
    </div>
  </div>
</div>
</section>
  </body>
</html>

```
```css
{
  margin: 0;
  padding:0;
  font-family: 'Poppins', sans-serif;
}
.header{
  min-height: 100vh;
  width: 100%;
  
  background-image: linear-gradient(rgb(4,9,30,0.7),rgba(4,9,30,0.7)),url("bg0.jpg");
  background-position: center;
  background-size: cover;

  position: relative;

}

.profile{
  height: 100px;
  width: 100px;
}
.com-name{
  font-size: 30px;
  color: #fff;
 
}

nav{
  display: flex;
  padding:2% 6%;
  justify-content: space-between;
  align-items: center;
}
nav img{
  width: 150px;
}
.nav-links{
  flex: 1;
  text-align: right;
}
.text-box{
  width: 90%;
  color: #fff;
  position: absolute;
  top: 50%;
  left:50%;
  transform: translate(-50%,-50%);
  text-align: center;
}
.text-box h1{
  font-size: 50px;
}
.text-box p{
  margin: 10px 0 40px;
  font-size: 14px;
  color: #fff;
}
.hero-btn{
  display: inline;
  text-decoration: none;
  color: #fff;
  border: 1px solid #fff;
  padding: 12px 34px;
  font-size: 13px;
  background: transparent;
  position: relative;
  cursor: pointer;
}

@media(max-width: 700px){
  .text-box h1{
    font-size: 18px;
  }
  .nav-links {
    position: fixed;
    background: #d46464;
    height: 100vh;
    width: 200px;
    top: 0;
    right: -200px;
    text-align: left;
    z-index: 2;
    transition: 1s;
  }
  nav .fa{
    display: block;
    color: #fff;
    margin: 10px;
    font-size: 22px;
    cursor: pointer;
  }
  .nav-links ul{
    padding: 30px;

  }
}

/*----Course-----*/


p{
  color: #777;
  font-size: 14px;
  font-weight: 300;
  line-height: 22px;
  padding: 10px;
}
.row{
  margin-top: 5%;
  display: flex;
  justify-content: space-between;
}
.course-col{
  flex-basis: 31%;
  background: #d46464;
  border-radius: 10px;
  margin-bottom: 5%;
  padding:20px 12px;
  box-sizing: border-box;
}
h3{
  text-align: center;
  font-weight: 600;
  margin: 10px 0;
}
.course-col:hover{
  box-shadow: 0 0 20px 0px rgba(0, 0, 0, 0.2);
}
@media(max-width: 700px){
  .row{
    flex-direction: column;
  }
}

/*-------CAMPUS-------*/

.campus{
  width:80%;
  margin: auto;
  text-align: center;
  padding-top: 50px;
}
.campus-col{
  flex-basis: 32%;
  border-radius: 10px;
  margin-bottom: 30px;
  position: relative;
  overflow: hidden;
}
.campus-col img{
  width:100%;
  height: 630px;
  display: block;
}

.layer:hover{
  background: #d46464;
}

.layer:hover h3{
  bottom: 49%;
  opacity: 1;
}

/*--------Facilities-------*/

.facilities{
  width: 80%;
  margin: auto;
  text-align: center;
  padding-top: 100px;
}
.facilities-col{
  flex-basis: 31%;
  border-radius: 10px;
  margin-bottom: 5%;
  text-align: left;
  
}

.facilities-col h3{
  margin-top: 16px;
  margin-bottom: 15px;
  text-align: left;
}


/*--------------testimonials---------------*/

.testimonials{
  width:80%;
  margin: auto;
  padding-top: 100px;
  text-align: center;

}
.testimonial-col{
  flex-basis: 44%;
  border-radius: 10px;
  margin-bottom: 5%;
  text-align: left;
  background: #d46464;
 
  cursor: pointer;
  display: flex;
  transition: 0.5s;
}

@media(max-width: 700px){
  .testimonial-col img{
    margin-left: 0;
    margin-right: 15px;
 
  }
}
```

## OUTPUT:
![Alt text](image.png)
![Alt text](image-1.png)
![Alt text](image-2.png)
![Alt text](image-3.png)
![Alt text](image-4.png)
![Alt text](image-5.png)
![Alt text](image-6.png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
