*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}

body{background:#f4f6f9;color:#222;}

.hero{
height:100vh;
background:url('../images/hero.jpg') center/cover no-repeat;
position:relative;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.overlay{
position:absolute;
top:0;left:0;
width:100%;height:100%;
background:rgba(0,30,60,0.7);
}

.hero-content{
position:relative;
z-index:2;
max-width:800px;
}

.logo{width:150px;margin-bottom:20px;}

.btn-primary{
display:inline-block;
padding:12px 25px;
background:#e30613;
color:white;
text-decoration:none;
border-radius:30px;
margin-top:20px;
transition:0.3s;
}

.btn-primary:hover{background:#b0040f;}

.services, .gallery, .devis{
padding:80px 20px;
text-align:center;
}

.cards{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin-top:40px;
}

.card{
background:white;
padding:30px;
border-radius:12px;
width:220px;
box-shadow:0 5px 20px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:translateY(-10px);
border-bottom:4px solid #e30613;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:15px;
margin-top:40px;
}

.grid img{
width:100%;
border-radius:10px;
transition:0.3s;
}

.grid img:hover{
transform:scale(1.05);
}

.stats{
display:flex;
justify-content:space-around;
padding:50px;
background:#002244;
color:white;
font-weight:600;
}

.devis form{
display:flex;
flex-direction:column;
max-width:400px;
margin:auto;
gap:15px;
}

.devis input, .devis textarea{
padding:10px;
border-radius:6px;
border:1px solid #ccc;
}

.devis button{
background:#e30613;
color:white;
border:none;
padding:10px;
border-radius:6px;
cursor:pointer;
}

footer{
background:#111;
color:white;
text-align:center;
padding:20px;
}
