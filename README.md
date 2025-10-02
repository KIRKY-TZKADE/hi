<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">		
<link rel="stylesheet" href="proposal.css">
<meta charset="UTF-8">
<title>proposal</title>
  
</head>
<body>
<div class="g1">
<div class="group1">
  				<button id="btt1">No</button>	
<button id="btt2">No</button>	
  		<button id="btt3">No</button>	
<button id="btt4">No</button>	
<button id="btt5">No</button>	
<button id="btt6">No</button>	
<button id="btt7">No</button>				
<button id="btt8">No</button>	
<button id="btt9">No</button>	
<button id="btt10">No</button>	
<button id="btt11">No</button>	
<button id="btt12">No</button>	

</div>		
<div class="images1">
<video controls autoplay class="sadcat" id="sadcat" src="coma.mp4" alt=""> </video>
<img class="crying" id="crying" src="https://c.tenor.com/36JFV8pDtXIAAAAd/sad-your-friends-are-togheter.gif" alt="">

<img class="sadboi" id="sadboi" src="https://c.tenor.com/6CujUsC1CIkAAAAM/crying-black-guy-meme50fps-interpolated-interpolated.gif" alt="">
<img id="sadsad" src="sadsad.jpeg" alt="">
</div>
 

<div class="ask">

<p> <span class="crush">HI MIKAELLA</span> <br>
I LIKE U, can i court you?</p>
<div class="btn">
<a href="yes.html"><button id="btn1">Yes</button>		</a>			    <button id="btn2">No</button>
</div>				
<img id="hands" src="image-removebg-preview.png "alt="">								
</div>					

<div class="g1">
<div class="images2">
<div class="group1">
  					<button id="bbtt1">No</button>	
<button id="bbtt2">No</button>	
  		<button id="bbtt3">No</button>	
<button id="bbtt4">No</button>	
<button id="bbtt5">No</button>	
<button id="bbtt6">No</button>	
<button id="bbtt7">No</button>				
<button id="bbtt8">No</button>	
<button id="bbtt9">No</button>	
<button id="bbtt10">No</button>	
<button id="bbtt11">NO</button>	
<button id="bbtt12">No</button>	
</div>

<div class="images1">

<img class="sadman" id="sadman" src="sadman.jpeg" alt="">

<img class="hahahuhu" id="hahahuhu" src="https://c.tenor.com/dpUQLSpLPzkAAAAd/sad-man-tik-tok-meme.gif" alt="">

<img id="hang" src="hang.jpeg" alt="">

<img id="frog" src="cryingcat.jpeg" alt="">

</div>																	
</div>

<div class="fff">
<p>Created by Kirk</p>
</div>

<script src="proposalv2.js"></script>
</body>
        </html>

 

const comeback = document.getElementById("btn2");
const yes = document.getElementById("btn1");
 
//group 1 of btts
 
const btt1 = document.getElementById('btt1');
const btt2 = document.getElementById('btt2');
const btt3 = document.getElementById('btt3');
const btt4 = document.getElementById('btt4');
const btt5 = document.getElementById('btt5');
const btt6 = document.getElementById('btt6');
const btt7 = document.getElementById('btt7');
const btt8 = document.getElementById('btt8');
const btt9 = document.getElementById('btt9');
const btt10 = document.getElementById('btt10');
const btt11 = document.getElementById('btt11');
const btt12 = document.getElementById('btt12'); 
 
//second group of btts
 
const bbtt1 = document.getElementById('bbtt1');
const bbtt2 = document.getElementById('bbtt2');
const bbtt3 = document.getElementById('bbtt3');
const bbtt4 = document.getElementById('bbtt4');
const bbtt5 = document.getElementById('bbtt5');
const bbtt6 = document.getElementById('bbtt6');
const bbtt7 = document.getElementById('bbtt7');
const bbtt8 = document.getElementById('bbtt8');
const bbtt9 = document.getElementById('bbtt9');
const bbtt10 = document.getElementById('bbtt10');
const bbtt11 = document.getElementById('bbtt11');
const bbtt12 = document.getElementById('bbtt12'); 
 
 
//IMAGESSSSSS///////
 
const hands = document.getElementById('hands');
const sadcat = document.getElementById('sadcat');
const crying = document.getElementById('crying');
const sadboi = document.getElementById('sadboi');
const sadman  = document.getElementById('sadman');
const hahahuhu = document.getElementById('hahahuhu');
const hang = document.getElementById('hang');
const sadsad = document.getElementById('sadsad');
 
 
 
comeback.addEventListener("click", function (){
btt12.style.opacity= "1";
comeback.style.opacity= "0";

});
 
btt12.addEventListener("click", function (){
btt12.style.opacity= "0";
bbtt3.style.opacity= "1";
hands.style.opacity= "1";

});
 
bbtt3.addEventListener("click", function (){
btt1.style.opacity= "1";
bbtt3.style.opacity= "0";
sadcat.style.opacity= "1";

});
 
btt1.addEventListener("click", function (){
btt1.style.opacity= "0";
btt4.style.opacity= "1";
hahahuhu.style.opacity= "1";

});
 
btt4.addEventListener("click", function (){
btt2.style.opacity= "1";
btt4.style.opacity= "0";
sadboi.style.opacity= "1";					
});
 
btt2.addEventListener("click", function (){
btt2.style.opacity= "0";
bbtt1.style.opacity= "1";
crying.style.opacity= "1";				
yes.style.padding= "50px";

});
 
bbtt1.addEventListener("click", function (){
bbtt8.style.opacity= "1";
bbtt1.style.opacity= "0";
sadman.style.opacity= "1";					
});
 
bbtt8.addEventListener("click", function (){
bbtt8.style.opacity= "0";
btt6.style.opacity= "1";
hang.style.opacity= "1";			



});
 
btt6.addEventListener("click", function (){
bbtt6.style.opacity= "0";
btt4.style.opacity= "0";	 
 btt3.style.opacity= "1";

});
 
btt3.addEventListener("click", function (){
bbtt6.style.opacity= "1";
btt1.style.opacity= "1";
btt4.style.opacity= "1";	 
 btt3.style.opacity= "1";
 btt2.style.opacity= "1";
 btt5.style.opacity= "1";
 btt6.style.opacity= "1";
 btt9.style.opacity= "1";
 btt11.style.opacity= "1";
 btt10.style.opacity= "1";
 bbtt1.style.opacity= "1";
 bbtt2.style.opacity= "1";
 bbtt3.style.opacity= "1";
 bbtt4.style.opacity= "1";
 bbtt5.style.opacity= "1";
 
 bbtt7.style.opacity= "1";
 
 bbtt9.style.opacity= "1";

});


<!DOCTYPE html>
<html lang="en">
<head>

<link rel="stylesheet" href="yes.css">	<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta charset="UTF-8">
<title>yey </title>
</head>
<body>
<div class="kilig">


<img src="https://c.tenor.com/zqm6WMNOXm0AAAAC/peachcute-peachhappy.gif" alt="">
<audio src="y2mate.com - Buddy Castle  Youre My Honey Bunch Lyrics.mp3"></audio>
<img src="https://c.tenor.com/s--312__jnoAAAAC/kermit-kermit-love.gif" alt="">
<p class="ay">hehe chat mo na q<3</p>
<audio id="sound" controls autoplay src="y2mate.com - Buddy Castle  Youre My Honey Bunch Lyrics.mp3"></audio>
<p class="ay">hehehehhehheheheh</p>
<img src="KILIG.jpg" alt="">
      
</div>

</body>
</html>
