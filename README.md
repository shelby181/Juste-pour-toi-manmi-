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
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    min-height: 100%;
    overflow-x: hidden;
    scroll-behavior: smooth;
}

body {
    min-height: 100vh;
    width: 100%;
    background: radial-gradient(circle at top, #382033, #100b14 75%);
    font-family: Georgia, serif;
    color: white;
    overflow-x: hidden;
    overflow-y: auto;
    padding: 35px 18px 45px;
}

.stars {
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 0;
}

.star {
    position: absolute;
    color: #ffc4d6;
    animation: sparkle 3s infinite alternate;
}

@keyframes sparkle {
    from {
        opacity: .2;
        transform: scale(.7);
    }
    to {
        opacity: 1;
        transform: scale(1.3);
    }
}

.container {
    width: 100%;
    max-width: 430px;
    margin: 0 auto;
    text-align: center;
    position: relative;
    z-index: 2;
}

.small-title {
    color: #e9b3c8;
    letter-spacing: 4px;
    font-size: 11px;
    margin: 20px 0 35px;
    text-transform: uppercase;
}

h1 {
    color: #ffc1d4;
    font-size: 30px;
    margin-bottom: 18px;
    font-weight: normal;
}

.intro {
    color: #d9c5d1;
    font-size: 15px;
    line-height: 1.9;
    margin-bottom: 45px;
}

.envelope {
    width: 180px;
    height: 125px;
    margin: 0 auto 35px;
    position: relative;
    cursor: pointer;
    transition: transform .4s, opacity .4s;
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
    clip-path: polygon(0 0
                
