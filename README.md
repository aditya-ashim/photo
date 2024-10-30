<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Calcutta Public School</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="header">
      <img src="images/top.jpg" alt="Header Image" class="header-image">
    </div>

    <div class="content">
      <div class="sidebar">
        <a class="nav-link" href="home.htm">Home</a>
        <a class="nav-link" href="files/vision.htm">Vision</a>
        <a class="nav-link" href="files/history.htm">History</a>
        <a class="nav-link" href="files/location.htm">Location</a>
        <a class="nav-link" href="files/organisation.htm">Organisation</a>
        <a class="nav-link" href="files/curriculum.htm">Curriculum</a>
        <a class="nav-link" href="files/school.htm">School Uniform</a>
        <a class="nav-link" href="files/teaching.htm">Teaching Staff</a>
        <a class="nav-link" href="files/fac.htm">Facilities</a>
        <a class="nav-link" href="files/activities.htm">Activities</a>
        <a class="nav-link" href="files/rules.htm">Rules</a>
        <a class="nav-link" href="files/register.htm">Register online</a>
        <a class="nav-link" href="files/photo.htm">Photogallery</a>
        <a class="nav-link" href="files/contact.htm">Contact Us</a>
        <a class="nav-link" href="files/site.htm">Site Map</a>
      </div>

      <div class="main-content">
        <p><strong><span class="school-title">Calcutta Public School</span></strong>, well-entrenched in the profound faith of Vivekananda that "All expansion is life, all contraction is death," has been marching with robust optimism of its own. The school articulates this concept in blending the richness of our pristine culture of the past and steady strides in modern science and technology. Here, the children are inspired to learn something great and glorious from within and nothing is thrust upon them.</p>
        <p>The school is bred and braced by the dominant concept of "the divinity inherent in man and his concept for indefinite evolution." Here, the management, the teachers, and the children try to cultivate a wholesome work-culture to evolve an 'organic whole' to experience life slowly but steadily.</p>
      </div>

      <div class="right-image"></div>
    </div>

    <div class="footer">
      <p>Powered by <a href="http://www.catchcal.net" title="Catchcal.net">Catchcal.net</a></p>
    </div>
  </div>
</body>
</html>


/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  display: flex;
  justify-content: center;
  background-color: #FFFFFF;
  font-family: Verdana, sans-serif;
}

.container {
  width: 780px;
}

.header .header-image {
  width: 100%;
  height: 108px;
  display: block;
}

.content {
  display: flex;
  background: #FFFFFF;
}

.sidebar {
  width: 159px;
  background: url('images/left_link.jpg') no-repeat center center;
  padding: 20px 0;
  text-align: center;
}

.nav-link {
  display: block;
  color: #F8CF44;
  font-size: 10px;
  font-weight: bold;
  text-decoration: none;
  margin: 5px 0;
}

.nav-link:hover {
  color: #FFFFFF;
}

.main-content {
  width: 374px;
  padding: 0 10px;
  background: url('images/bg_watermark.jpg') no-repeat center center;
  color: #FFFFFF;
}

.school-title {
  color: #F8D448;
  font-size: 24px;
}

.right-image {
  width: 247px;
  background: url('images/right_img.jpg') no-repeat center center;
}

.footer {
  background: url('images/bottom_img.jpg') no-repeat center center;
  height: 27px;
  text-align: left;
  padding: 5px;
  margin: 0;
}

.footer p {
  font-size: 10px;
  color: #000;
  margin: 0;
}

.footer a {
  color: #000;
  text-decoration: none;
}
