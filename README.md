# Juste-pour-toi-manmi-
Surprise
<!ma Reine>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Juste pour toi ❤️</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    min-height: 100vh;
    background: radial-gradient(circle at top, #382033, #100b14 70%);
    font-family: Georgia, serif;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow-x: hidden;
    overflow-y: auto;
    padding: 20px;
}

.stars {
    position: fixed;
    inset: 0;
    pointer-events: none;
}

.star {
    position: absolute;
    color: #ffc4d6;
    animation: sparkle 3s infinite alternate;
}

@keyframes sparkle {
    from { opacity: .2; transform: scale(.7); }
    to { opacity: 1; transform: scale(1.3); }
}

.container {
    width: 100%;
    max-width: 430px;
    text-align: center;
    position: relative;
    z-index: 2;
}

.small-title {
    color: #e9b3c8;
    letter-spacing: 4px;
    font-size: 11px;
    margin-bottom: 35px;
    text-transform: uppercase;
}

h1 {
    color: #ffc1d4;
    font-size: 29px;
    margin-bottom: 15px;
    font-weight: normal;
}

.intro {
    color: #d9c5d1;
    font-size: 15px;
    line-height: 1.8;
    margin-bottom: 45px;
}

.envelope {
    width: 180px;
    height: 125px;
    margin: 0 auto 35px;
    position: relative;
    cursor: pointer;
    transition: transform .4s;
    filter: drop-shadow(0 10px 20px #ff6b9140);
}

.envelope:hover {
    transform: translateY(-8px);
}

.envelope-body {
    position: absolute;
    inset: 0;
    background: #e85d86;
    border-radius: 5px;
    overflow: hidden;
}

.envelope-body::before {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(135deg, #ff9db8, #d83d70);
    clip-path: polygon(0 0, 50% 60%, 100% 0);
    z-index: 2;
}

.envelope-body::after {
    content: "";
    position: absolute;
    inset: 0;
    background: linear-gradient(45deg, #d83d70, #f77e9f);
    clip-path: polygon(0 100%, 50% 45%, 100% 100%);
    z-index: 3;
}

.heart {
    position: absolute;
    z-index: 4;
    top: 43%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 29px;
}

.hint {
    color: #ffb5ca;
    font-size: 14px;
    letter-spacing: 1px;
    animation: pulse 1.8s infinite;
}

@keyframes pulse {
    50% { opacity: .45; }
}

.message {
    display: none;
    background: linear-gradient(145deg, #291a2c, #1c1220);
    border: 1px solid #a95778;
    border-radius: 20px;
    padding: 30px 23px;
    margin-top: 25px;
    box-shadow: 0 0 35px #ff477e25;
    animation: appear 1.5s ease forwards;
}

@keyframes appear {
    from {
        opacity: 0;
        transform: translateY(25px) scale(.95);
    }
    to {
        opacity: 1;
        transform: translateY(0) scale(1);
    }
}

.message h2 {
    color: #ffabc4;
    font-weight: normal;
    font-size: 24px;
    margin-bottom: 20px;
}

.message p {
    color: #f0dce6;
    font-size: 15px;
    line-height: 2;
}

.signature {
    margin-top: 22px;
    color: #ffabc4;
    font-style: italic;
    font-size: 17px;
}

footer {
    margin-top: 45px;
    color: #96798b;
    font-size: 11px;
    letter-spacing: 2px;
}

.opened .envelope {
    transform: scale(.8);
    opacity: 0;
    pointer-events: none;
    height: 0;
    margin-bottom: 0;
}

.opened .hint {
    display: none;
}

</style>
</head>

<body>

<div class="stars" id="stars"></div>

<div class="container" id="container">

    <div class="small-title">Une attention particulière</div>

    <h1>Juste pour toi ❤️</h1>

    <p class="intro">
        Il y a quelque chose qui t'attend ici...
        <br>
        Prends un petit instant pour le découvrir.
    </p>

    <div class="envelope" id="envelope">
        <div class="envelope-body"></div>
        <div class="heart">❤</div>
    </div>

    <p class="hint" id="hint">Touche l'enveloppe pour l'ouvrir ✨</p>

    <div class="message" id="message">
        <h2>À toi, Manmi ❤️</h2>

        <p>
            Je voulais simplement t'offrir quelque chose
            de différent aujourd'hui.
            <br><br>
            Pas besoin d'une grande occasion pour rappeler
            à une personne combien elle est précieuse.
            <br><br>
            Alors, voici ce petit quelque chose,
            juste pour toi.
            <br><br>
            N'oublie jamais que tu occupes
            une place spéciale dans mon cœur.
        </p>

        <div class="signature">
            Avec tendresse, Papi ❤️
            Nèg dous ou a 😇
        </div>
    </div>

    <footer> 5 NOVEMBRE · JUSTE POUR TOI</footer>

</div>

<script>
const stars = document.getElementById("stars");

for (let i = 0; i < 45; i++) {
    const star = document.createElement("span");
    star.className = "star";
    star.innerHTML = "✦";
    star.style.left = Math.random() * 100 + "%";
    star.style.top = Math.random() * 100 + "%";
    star.style.fontSize = (5 + Math.random() * 10) + "px";
    star.style.animationDelay = Math.random() * 3 + "s";
    stars.appendChild(star);
}

document.getElementById("envelope").addEventListener("click", function() {
    document.getElementById("container").classList.add("opened");

    setTimeout(function() {
        document.getElementById("message").style.display = "block";
    }, 450);
});
</script>

</body>
</html>
