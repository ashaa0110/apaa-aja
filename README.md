body{
margin:0;
padding:0;
font-family:Arial,sans-serif;
background:linear-gradient(135deg,#0f172a,#1e3a8a,#60a5fa);
color:white;
text-align:center;
overflow-x:hidden;
}

#loading,#giftPage,#surprise,#lovePage{
min-height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
padding:20px;
}

.hidden{
display:none !important;
}

h1{
font-size:38px;
margin-bottom:10px;
}

h2{
font-size:28px;
}

p{
font-size:20px;
max-width:700px;
line-height:1.8;
}

.gift{
font-size:120px;
cursor:pointer;
transition:.4s;
animation:shake 1s infinite;
}

.gift:hover{
transform:scale(1.2);
}

@keyframes shake{
0%{transform:rotate(0deg);}
25%{transform:rotate(-8deg);}
50%{transform:rotate(8deg);}
75%{transform:rotate(-8deg);}
100%{transform:rotate(0deg);}
}

img{
width:300px;
height:400px;
object-fit:cover;
border-radius:20px;
margin:20px;
box-shadow:0 0 30px rgba(255,255,255,.4);
}

.message{
background:rgba(255,255,255,.12);
padding:25px;
border-radius:20px;
backdrop-filter:blur(10px);
max-width:800px;
}

button{
margin-top:20px;
padding:15px 35px;
font-size:20px;
border:none;
border-radius:50px;
background:#3b82f6;
color:white;
cursor:pointer;
transition:.3s;
}

button:hover{
transform:scale(1.08);
background:#2563eb;
}

#music{
position:fixed;
bottom:15px;
right:15px;
}

.heart{
position:fixed;
top:-30px;
font-size:24px;
animation:fall 6s linear infinite;
pointer-events:none;
}

@keyframes fall{
to{
transform:translateY(110vh);
}
}

@media(max-width:768px){

h1{
font-size:28px;
}

p{
font-size:17px;
}

img{
width:90%;
height:auto;
}

.gift{
font-size:90px;
}

}
