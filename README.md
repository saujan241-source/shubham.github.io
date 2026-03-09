> 🧠 "While others sleep, I build.  
> While others talk, I execute.  
> While others quit, I commit."

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Motivation</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">

<style>

body{
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    font-family:'Poppins', sans-serif;
    background: linear-gradient(135deg,#0f2027,#203a43,#2c5364);
    color:white;
}

.container{
    text-align:center;
    padding:40px;
}

.quote{
    font-size:40px;
    font-weight:600;
    animation: glow 2s ease-in-out infinite alternate;
}

.sub{
    margin-top:20px;
    font-size:20px;
    opacity:0.8;
}

button{
    margin-top:30px;
    padding:12px 30px;
    border:none;
    border-radius:30px;
    background:#ff4b2b;
    color:white;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.1);
    background:#ff416c;
}

@keyframes glow{
    from{
        text-shadow:0 0 10px #fff;
    }
    to{
        text-shadow:0 0 25px #00f7ff;
    }
}

</style>
</head>

<body>

<div class="container">

<div class="quote">
"While others sleep, I build."
</div>

<div class="sub">
Code. Break. Fix. Repeat.
</div>

<button onclick="newQuote()">New Motivation</button>

</div>

<script>

const quotes = [
"While others sleep, I build.",
"Discipline beats motivation.",
"Dreams don't work unless you do.",
"Legends are built in late night coding.",
"Commit. Push. Repeat."
]

function newQuote(){
let random = Math.floor(Math.random()*quotes.length);
document.querySelector(".quote").innerText = quotes[random];
}

</script>
<shubham>

