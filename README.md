
<!DOCTYPE html>
<html>
<head>
<title>For Nancy ❤️</title>

<style>

body{
margin:0;
padding:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
font-family:Arial;
background:linear-gradient(45deg,#ff758c,#ff7eb3);
color:white;
overflow:hidden;
}

.box{
background:rgba(0,0,0,0.4);
padding:40px;
border-radius:20px;
width:80%;
max-width:600px;
z-index:2;
}

h1{
font-size:38px;
}

p{
font-size:20px;
line-height:1.6;
}

/* heart animation */

.heart{
position:absolute;
color:red;
font-size:20px;
animation:fall 6s linear infinite;
}

@keyframes fall{
0%{
transform:translateY(-10vh);
opacity:1;
}
100%{
transform:translateY(110vh);
opacity:0;
}
}

</style>

</head>

<body>

<div class="box">

<h1>❤️ Dear Nancy ❤️</h1>

<p>
Nancy, aap overthinking mat kara karo betu.  
Itna mat socha karo. Kisi ne kuch bola to uske baare me zyada mat socho.  

Aap bas khud par focus karo. Aapka test clear ho jayega, uski tension bhi mat liya karo.  

Aapne test ke liye bahut mehnat ki hai aur mujhe aap par pura bharosa hai.  
Sab achhe se ho jayega.  

Bas relax raho, time se khana khaya karo aur zyada stress mat liya karo.  

Aur ek baat yaad rakhna betu…  
Krishu tera hi hai aur tera hi rahega.  
Main hamesha tere paas hoon. ❤️
</p>

</div>

<script>

function createHeart(){
const heart=document.createElement("div");
heart.classList.add("heart");
heart.innerHTML="❤️";
heart.style.left=Math.random()*100+"vw";
heart.style.fontSize=(10+Math.random()*20)+"px";

document.body.appendChild(heart);

setTimeout(()=>{
heart.remove();
},6000);
}

setInterval(createHeart,300);

</script>

<iframe width="0" height="0"
src="https://www.youtube.com/embed/fVf5Q4p0R0g?autoplay=1&loop=1&playlist=fVf5Q4p0R0g"
frameborder="0"
allow="autoplay">
</iframe>

</body>
</html>