<html lang="hy">
    <head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Karen web studio/Կայքեր բիզնեսների համար</title>
<link rel="stylesheet" href="style.css">
    </head>
<body>
<header>
<div class="logo">Karen web studio</div>
<nav>
    <a href="#home">Գլխավոր</a>
    <a href="#services">Ծառայություններ</a>
    <a href="#portfolio">Աշխատանքներ</a>
    <a href="contact">կապ</a>
</nav>
</header>
<section id="home" class="hero">
<div class="hero-text">
<p class="small-title">WEB DEVELOPMENT</p>
<h1>Կայք ձեր բիզմեսի համար </h1>
<p>Պատրաստում եմ ժամանակակից, արագ և գեռախոսին հարմար կայքեր փոքր և միջին բիզնեսների համար</p>
<a href="#contact" class="main-botton">Պատվիրել կայք</a>
</div>
</section>
<section id="services" class="section">
<h2>Իմ ծառայությունները</h2>
<div class="card">
<h3>Landing Page</h3>
<p>Մեկ էջանոց ժամանակակից կայք ձեր ծառայության կամ բիզմեսի համար։
</p>
<strong>40,000 Դ-ից</strong>
</div>
<div class="card">
<h3>Բիզնես կայք</h3>
<p>Բազմաբաժին կայք ձեր Բիզնեսը ինտերնետում ներկայացնելու համար։</p>
<strong>70,000դ-ից</strong>
</div>
<div class="card">
<h3>Կայքի փոփոխություններ</h3>
<p> Պատրաստի կայքի դիզայնի,HTML/CSS JavaScript փոփոխություններ։</p>
<strong>15,000 դ-ից</strong>
</div>
</div>
</section>
<section id="portfolio" class="section portfolio">
<h2>Իմ ապրանքները</h2>
<div class="portfolio-grid">
<div class="project">
<div class="project-image">
    Demo 01
</div>
<h3>Բիզնես կայք</h3>
<p>HTML / CSS/ JavaScript</p>
</div>
<div class="project">
<div class="project-image">
    Demo 02
</div>
<h3>Ավտոարվեստի կայք</h3>
<p>Responsive Desing</p>
</div>
<div class="project">
<div class="project-image">
    Demo 3
</div>
<h3>Landing Page</h3>
<p>HTML / CSS</p>
</div>
</div>
</section>
<section class="section">
<h2></h2>
<div class="advantages">
<div>
<span>⚡</span>
<h3>Արագ Ապրանք</h3>
<p>Կայքը Պատրաստվում է պայմանավորբած ժամկետում</p>
</div>
<div>
<span>📲</span>
<h3>Հեռախոսին հարմար</h3>
<p>Կայքը աշխատում է Հեռախոսների և համակարգիչների վրա</p>
</div>
<div>
<span>🎨</span>
<h3>ժամանակակից դիզայն</h3>
<p>Պարզ և գեղեցիկ տեսք ձեր բիզնեսի համար</p>
</div>
</div>
</section>
<section id="contact" class="section contact">
<h2>Պատվիրել կայք</h2>
<p>Լրացրեք ձևը, և ես կկապնվեմ ձեզ հետ</p>
<form id="orderForm">
<input 
type="text"
id="name"
placeholder="ձեր անունը"
required
>
</br>
<input
type="tel"
id="phone"
placeholder="հեռխոսահամար"
required
>
</br>
<input
type="text"
id="business"
placeholder="ձեր բիզնեսի տեսակը"
required
>
</br>
<select id="service">
<option value="">Ընտրեք ծառայություն</option></br>
<option>Landing page</option></br>
<option>Բիզնես կայք</option></br>
<option>Կայքի փոփոխություն</br>
</option></br>
</select></br>
<textarea id="message" placeholder="նկարագրեք ինչ կայք եք ցանկանում"></textarea></br>
<button type="submit">Ուղարկեք պատվերը</button>
</form>
</section>
<footer>
<h3>Karen web studio</h3>
<p>web կայքեր փոքր և միջին բիզնեսների համար</p>
<p>@ 2026 Karen web studio</p>
<p>Էջ պատվիրելու համար զանգահարիր093257923 հեռախոսահամարին կամ գրիր նուըն հոռախոսահամարի Watsapp-ին։</p>
</footer>
<script src="script.js">
const form=document.getElementById("orderForm");
const BOT_TOKEN ="ՔՈ_BOT_TOKENԸ";
const CHAT_ID ="ՔՈ_CHAT_IDՆ"
form.addEventListener("submit" ,async function(event){event.preventDefault();
    const name=document.getElementById("name").vaule;
const phone=document.getElementById("business").vaule;
const service =document.getElementById("service").vaule;
const message=document.getElementById("massage").vaule;
const text='
'🔔Նոր պատվեր"

 '👨 Անուն ${name}'
'📲 Հեռախոս${phone}'
'🏙️Բիզնես ${business}'
'🧑‍💻 Ծառայություններ ${service}'
'💾 Պատվերի նկարագրություն ${message} ;'
try{
    const response=await fetch(https://api.telegram.org/bot ${BOT_TOKEN}/sendMessage',
    {
        method:"POST",
        headers:{
            "content-type":
            "application/json"
        },
        body:
        JSON.stringify({
            chat_id:CHAT_ID,
            text:text
    })
}
    );
if (response.ok) {
    alert("Պատվերը հաջողությամբ ուղարկվեց։");
    form.reset();
} else{
    alert("Չհաջողվեց ուղարկել պատվերը։" );
}
}catch (error){
    alert("Սխալ տեղի ունեցավ ");
    console.error(error);
}
});


</script>
</body>
</html>