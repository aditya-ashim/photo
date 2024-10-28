<!DOCTYPE html>
<html>
  <head>
    <title>Calcutta Public School > Photogallery</title>
<link rel="stylesheet" href="photogallery.css">
  </head>
  <body>

<!------------Header section Start------------------->

<div id="fullpage">
<header>
<div class="ANNUAL FUNCTION"><img src="images/top.jpg" alt="ANNUAL FUNCTION"></div>
</header>
<!------------Main section Start------------------->

<div class="parent">
    <div class="div1"><nav id="nav" >
 <ul class="nav-links">
                                            <li><a href="index.html">Home</a></li>
                                            <li><a href="vision.html">Vision</a></li>
                                            <li><a href="history.html">History</a></li>
                                            <li><a href="location.html">Location</a></li>
                                            <li><a href="organisation.html">Organisation</a></li>
                                            <li><a href="curriculum.html">Curriculum</a></li>
                                            <li><a href="school_uniform.html">School Uniform</a></li>
                                            <li><a href="teaching_staff.html">Teaching Staff</a></li>
                                            <li><a href="facilities.html">Facilities</a></li>
                                            <li><a href="activities.html">Activities</a></li>
                                            <li><a href="rules.html">Rules</a></li>
                                            <li><a href="register_online.html">Register online</a></li>
                                            <li><a href="photogallery.html">Photogallery</a></li>
                                            <li><a href="contact_us.html">Contact Us</a></li>
                                            <li><a href="site_map.html">Site Map</a></li>
</ul>
</nav>
</div>
    <div class="div2"><p><font><strong class="vision">Photogallery</font></strong><div class="vision-border"></div></p>
</div>
    <div class="div3">
<p class="txtContainer">
<b>ANNUAL FUNCTION</b>
</p>

<p class="imgContainer">
<img src="images/stage.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
<img src="images/drama_4.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
</p><br>
<p class="imgContainer">
<img src="images/drama_3.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
<img src="images/dance.gif" alt="ANNUAL FUNCTION" class="facImg image-popup">
</p><br>
<p class="imgContainer1">
<img src="images/drama2.gif" alt="ANNUAL FUNCTION" class="facImg d2 image-popup">
<img src="images/boy.gif" alt="ANNUAL FUNCTION" class="boy image-popup">
</p>
<p class="txtContainer">
<b>LABS</b>
</p>

<p class="imgContainer">
<img src="images/lab_3.gif" alt="BIOLOGY LAB" class="facImg image-popup">
<img src="images/lab_6.gif" alt="PHYSICS LAB" class="facImg image-popup">
</p>
<p class="txtContainer">
<b>BIOLOGY LAB</b>
<b>PHYSICS LAB</b>
</p>
<p class="txtContainer">
<b>RECTOR</b>
</p>
<p class="imgContainer">
<img src="images/pricipal.gif" alt="RECTOR" class="facImg image-popup">
</p>

</div>
    <div class="div4"><footer class="footer">
<p>Powered by&nbsp<a href="https://www.google.com" target="_blank" class="afoot">Google.com</a></p>
</footer></div>
</div>
</div>

 <!-------------------------------------------------- Modal Structure Start ------------------------------------------>

<section>
    <div id="myModal" class="modal-div">
                <span class="close" title="Close">&times;</span>
                <div class="modal-content">
<img id="modalImg" src=""></div>
                <div class="caption-container" style="width: 100%; text-align: center;">
<p id="caption"></p>
                </div>
                <a class="prev" title="Previous">&#10094;</a>
                <a class="next" title="Next">&#10095;</a>
           
    </div>
</section>



<script src="photogallery.js"></script>
  </body>
</html>
# photo

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html, body {
    font-family: Verdana, sans-serif;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    overflow-x: hidden;
overflow-y:scroll;
}

body {
    overflow: hidden;
}

.logo img {
    width: 780px;
    height: 108px;
}

#fullpage {
    background: url('images/bg_watermark.jpg') repeat-y;
    width: 780px;
}

img{
display:block;
width:100%;
}

a {
    text-decoration: none;
    color: #f8cf44;
    font-size: 10px;
    font-weight: 700;
    transition: color 0.3s ease;
}

a:hover {
    color: #fff;
}

.afoot {
    color: #000;
}

.afoot:hover {
    color: red;
}

.vision {
    position: absolute;
    width: 100%;
    height: 34px;
    color: #FFD700;
    padding: 12px 10px 0;
    font-weight: 900;
    letter-spacing: 1.6px;
    font-size: 13.9px;
    overflow: hidden;
margin-top:-2px;
}

.vision-border {
    margin-top:29.2px;
margin-left: -10px;
display: inline-block;
background: rgb(7,13,86);
background: linear-gradient(131deg, rgba(7,13,86,1) 1%, rgba(45,68,136,1) 8%, rgba(46,60,135,1) 90%, rgba(7,13,86,1) 94%);
height:1px;
padding-left:210px;
}

p {
    font-size: 13px;
    color: #fff;
    line-height: 20px;
    word-spacing: 1px;
}

ul {
    margin-top: -3px;
}

ul li {
    list-style-type: none;
}

#nav {
    background: url('images/extra.jpg') repeat-y;
    min-width: 159px;
    height: 100%;
    padding: 14px 14.2px;
}

.nav-links {
    position: sticky;
}

.main {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}

.strong {
    color: #f8cf44;
    font-weight: 800;
    font-size: 20px;
}

.footer {
    background: url('images/bottom_img.jpg') no-repeat;
    width: 780px;
    height: 27px;
}

.footer p {
    color: #000;
    font-weight: 900;
    font-size: 10px;
    padding: 5px 12px;
    display: flex;
    align-items: center;
}

.para1, .para2{
    padding-bottom: 17px;
    font-size: 13px;
}
.para3{
padding-top:17px;
padding-bottom: 17px;
}
.para4{
padding-bottom: 17px;
}
.para4:last-child{
padding-bottom: 25px;
}

.image-popup{
transition: transform .2s ease-in-out;
}
.image-popup:hover{
cursor:pointer;
transform: scale(1.1);
}

.imgContainer, .txtContainer{
display:flex;
justify-content:center;
align-items:center;
gap:30px;
}


.txtContainer b{
text-align:center;
width: 250px;
padding-top:5px;
margin-bottom:20px;
}
.facImg {
    width: 250px;
    height: 164px;
}

.boy{
width: 164px;
    height: 250px;
margin-right:30px;
}

.imgContainer1{
display:flex;
justify-content:space-evenly;
align-items:center;
}

.d2{
margin-right:60px;
}

.imgContainer:last-child{
margin-bottom:30px;
}


.parent {
    display: grid;
    grid-template-columns: 169px 1fr;
    grid-template-rows: auto;
    gap: 0;
}

.div1 {
    grid-column: 1 / 2;
    grid-row: 1 / span 5;
}

.div2 {
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    height: 40px;
}

.div3 {
    padding: 10px;
margin-right:15px;
    grid-column: 2 / 3;
    grid-row: 2 / span 3;
}

.div4 {
    margin-top: -5px;
    grid-column: 1 / -1;
    grid-row: 6 / 7;
}















/*-----------------------------------------Modal CSS Start---------------------------------------- */



.modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 60.4%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}





/* Media query for higher zoom level */
        @media (resolution: 120dpi) {
            .modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 75.6%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}
        }


.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 

}

.modal-content img {
margin-left: auto;
  margin-right: auto;
object-fit:contain;
display:block;
  width: 515px;
  height: 338px;
    margin-bottom: 30px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
position:relative;
bottom:25px;
}
.caption-container p {
color:#000;
font-size:14px;
font-weight:900;
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: 30px;
}

.prev, .next {
    position: absolute;
    top: 40%;
    padding: 16px;
position:fixed;
    color: white;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color:rgba(0, 0, 0, 0.4);
transition:all 0.2s ease-in-out;
-webkit-user-select: none; 
    -moz-user-select: none;
}
.prev:hover, .next:hover {
background-color: rgba(0, 0, 0, 0.7);
color:#fff;
border-radius:50%;
margin:0px 0.5px;
}

.prev {
    left: 0;
}

.next {
    right: 0;
}

.close {
    position: absolute;
    top: 5px;
    right: 10px;
    color: white;
    font-size: 30px;
    font-weight: bold;
    cursor: pointer;
    transition: color 0.3s ease-in-out;
}

.close:hover{
color: #000;

}
.modal-content img.boy-gif {
width:246px;
height:375px;
margin-left: auto;
  margin-right: auto;
display:block;
}


.image-popup{
-webkit-user-select: none; 
    -moz-user-select: none;
filter:contrast(115%);
}
.image-popup:hover{
cursor:pointer;
filter:contrast(100%);
}
.special{ 
width:246px;
height:375px;
}

 /* Modal CSS for Firefox */

@-moz-document url-prefix() {
.modal-div {
    display: none;
    position: fixed;
    z-index: 1000;
    left: 50%;
    top: 60.4%;
transform:translate(-50%,-50%);
    width: 780px;
    height: 450px;
max-width:90%;
max-height:90%;
    background-color: gray ;
    table-layout: fixed;
border:1px solid #949494;
}

.modal-content {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%; 
}

.modal-content img {
margin-left: auto;
  margin-right: auto;
object-fit:contain;
display:block;
  width: 515px;
  height: 338px;
    margin-top: 30px;
border-radius:5px;
}


.caption-container {
    width: 100%;
    text-align: center;
position:relative;
bottom:25px;
}
.caption-container p {
color:#000;
font-size:14px;
font-weight:900;
    text-align: center; 
    font-size: 16px; 
    margin-top: -15px; 
    margin-bottom: 0px;
}

#caption{
margin-top:50px;

}

.modal-content img.boy-gif {
width:245px;
height:375px;
margin-bottom:-8px;
margin-left: auto;
  margin-right: auto;
display:block;
}

.prev, .next {
    position: absolute;
    top: 40%;
    padding: 15.5px;
position:fixed;
    color: white;
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color:rgba(0, 0, 0, 0.4);
transition:all 0.2s ease-in-out;
-webkit-user-select: none; 
    -moz-user-select: none;
}
.prev:hover, .next:hover {
background-color: rgba(0, 0, 0, 0.7);
color:#fff;
border-radius:50%;
margin:0px 0.5px;
}

.prev {
    left: 0;
}

.next {
    right: 0;
}

}









const modal = document.getElementById("myModal");
const modalImg = document.getElementById("modalImg");
const captionText = document.getElementById("caption");
const closeModal = document.getElementsByClassName("close")[0];
const images = document.querySelectorAll(".image-popup");

let currentIndex = 0;

images.forEach((img, index) => {
    img.addEventListener("click", function () {
        currentIndex = index; 
        showModal();
    });
});

closeModal.addEventListener("click", function () {
    modal.style.display = "none";
});

function showModal() {
    modal.style.display = "table";
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif


    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

function updateModal() {
    modalImg.src = images[currentIndex].src;
    captionText.innerHTML = images[currentIndex].alt;

    // Set specific class for boy.gif
    if (images[currentIndex].src.includes('boy.gif')) {
        modalImg.classList.add('boy-gif'); 
    } else {
        modalImg.classList.remove('boy-gif'); 
    }
toggleButtons();
}

document.addEventListener("keydown", function (event) {
    if (event.key === "Escape") {
        modal.style.display = "none"; 
    }
});

/*window.addEventListener('keydown', event => {
  if (event.key == "ArrowLeft") {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();

  }else if (event.key == "ArrowRight") {
   currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
  }
}); */

// Next and Previous functionality
document.querySelector(".prev").addEventListener("click", function () {
    currentIndex = (currentIndex === 0) ? images.length - 1 : currentIndex - 1;
    updateModal();
});

document.querySelector(".next").addEventListener("click", function () {
    currentIndex = (currentIndex === images.length - 1) ? 0 : currentIndex + 1;
    updateModal();
});

function toggleButtons(){

//document.querySelector(".prev").style.display="inline-block";
//document.querySelector(".next").style.display="inline-block";

if(currentIndex===0){
document.querySelector(".prev").style.display="none";	
}else{
document.querySelector(".prev").style.display="inline-block";
}

if(currentIndex===images.length - 1){
document.querySelector(".next").style.display="none";
}else{
document.querySelector(".next").style.display="inline-block";
}
}
