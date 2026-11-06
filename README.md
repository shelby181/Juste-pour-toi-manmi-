# Juste-pour-toi-manmi-
Surprise
<!ma Reine>

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Juste pour toi ❤️</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    background: linear-gradient(160deg, #382033, #100b14 75%);
    color: white;
    font-family: Georgia, serif;
    text-align: center;
    padding: 30px 18px;
}

.container {
    width: 100%;
    max-width: 420px;
    margin: 50px auto 30px;
}

.subtitle {
    color: #dba8bd;
    letter-spacing: 4px;
    font-size: 11px;
    margin-bottom: 35px;
}

h1 {
    color: #ffabc5;
    font-size: 30px;
    font-weight: normal;
    margin-bottom: 20px;
}

.intro {
    color: #e2cbd7;
    line-height: 1.9;
    font-size: 15px;
    margin-bottom: 45px;
}

.envelope {
    width: 170px;
    height: 115px;
    background: linear-gradient(135deg, #ff9bb8, #d83d70);
    margin: 0 auto 35px;
    position: relative;
    border-radius: 8px;
    cursor: pointer;
    box-shadow: 0 10px 35px #ff477e45;
    transition: transform .3s;
}

.envelope:active {
    transform: scale(.94);
}

.envelope::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    border-left: 85px solid transparent;
    border-right: 85px solid transparent;
    border-top: 65px solid #ffbfd0;
}

.envelope::after {
    content: "♥";
    position: absolute;
    top: 43px;
    left: 0;
    right: 0;
    font-size: 30px;
    color: white;
}

.hint {
    color: #ffb6cb;
    font-size: 14px;
    animation: pulse 2s infinite;
}

@keyframes pulse {
    50% { opacity: .4; }
}

.message {
    background: #241729;
    border: 1px solid #a95778;
    border-radius: 20px;
    padding: 28px 22px;
    margin: 30px auto;
    box-shadow: 0 0 30px #ff477e25;
    animation: apparition 1s ease;
}

@keyframes apparition {
    from {
        opacity: 0;
        transform: translateY(20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.message h2 {
    color: #ffabc5;
    font-size: 25px;
    font-weight: normal;
    margin-bottom: 25px;
}

.message p {
    color: #f1dce6;
    font-size: 15px;
    line-height: 2;
}

.signature {
    color: #ffabc5;
    font-style: italic;
    font-size: 18px;
    margin-top: 25px;
}

footer {
    color: #96798b;
    font-size: 11px;
    letter-spacing: 2px;
    margin-top: 45px;
    padding-bottom: 20px;
}

[hidden] {
    display: none !important;
}
</style>
</head>

<body>

<div class="container">

    <div class="subtitle">UNE ATTENTION PARTICULIÈRE</div>

    <h1>Juste pour toi ❤️</h1>

    <p class="intro">
        Il y a quelque chose qui t'attend ici...
        <br>
        Prends un petit instant pour le découvrir.
    </p>

    <button id="ouvrir" class="envelope"
    type="button" aria-label="Ouvrir l'enveloppe">
    </button>

    <p id="indication" class="hint">
        Touche l'enveloppe pour l'ouvrir ✨
    </p>

    <div id="message" class="message" hidden>

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
        </div>

    </div>

    <footer>
        10 NOVEMBRE · JUSTE POUR TOI
    </footer>

</div>

<script>
const bouton = document.getElementById("ouvrir");
const message = document.getElementById("message");
const indication = document.getElementById("indication");

bouton.addEventListener("click", function() {

    message.hidden = false;
    bouton.hidden = true;
    indication.hidden = true;

    setTimeout(function() {
        message.scrollIntoView({
            behavior: "smooth",
            block: "center"
        });
    }, 100);

});
</script>

</body>
</html>

Enpòtan: Apre ou fin fè Commit changes, teste lyen an ankò. Si ansyen vèsyon an parèt, fè yon rafrechisman paj la.

Mwen ta renmen konnen yon sèl bagay: èske se anvlòp la ki pa ouvri lè ou klike, oswa se mesaj la ki pa parèt? ❤️
                
