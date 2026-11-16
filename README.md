# World_music_day
My world music day website

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>World Music Day 🎵</title>

<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    font-family: Georgia, serif;
    background: linear-gradient(135deg, #100c2c, #30205b, #151333);
    color: white;
    text-align: center;
}

header {
    padding: 55px 15px 25px;
}

header h1 {
    font-size: 38px;
    color: #e5b5ff;
    text-shadow: 0 0 15px #b46cff;
}

header p {
    color: #d5c8ef;
    font-size: 18px;
}

.music-notes {
    font-size: 35px;
    margin: 20px;
    animation: float 2s infinite alternate;
}

@keyframes float {
    from { transform: translateY(0); }
    to { transform: translateY(-15px); }
}

.container {
    width: 90%;
    max-width: 750px;
    margin: 20px auto 50px;
    padding: 30px;
    background: rgba(255,255,255,0.09);
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 25px;
    box-shadow: 0 0 25px rgba(174,110,255,0.2);
}

h2 {
    color: #e5b5ff;
    font-size: 27px;
}

.speech {
    font-size: 17px;
    line-height: 2;
    text-align: left;
    color: #f3edff;
}

.speech p {
    margin-bottom: 18px;
}

button {
    background: #b66aff;
    color: white;
    border: none;
    padding: 13px 25px;
    border-radius: 30px;
    font-size: 16px;
    cursor: pointer;
    margin-top: 15px;
}

button:hover {
    background: #9145df;
    transform: scale(1.05);
}

footer {
    padding: 25px;
    color: #c8b8e8;
}
</style>
</head>

<body>

<header>
    <div class="music-notes">♫ ♪ ♬</div>
    <h1>World Music Day</h1>
    <p>June 21 · Let's celebrate the power of music!</p>
</header>

<div class="container">

    <h2>🎵 My Speech About World Music Day</h2>

    <div class="speech">

        <p>Hello everyone!</p>

        <p>Today, I want to talk about World Music Day.</p>

        <p>World Music Day is on June 21st every year.</p>

        <p>Music is a big part of our lives.
        People all around the world love music.</p>

        <p>There are many kinds of music, like pop,
        rock, and classical music.</p>

        <p>People can play music with different instruments,
        like the guitar, piano, and violin.</p>

        <p>Music makes us happy and helps us feel better.</p>

        <p>We can listen to music at home, at school,
        or with our friends.</p>

        <p>I love music because it makes my life
        more beautiful.</p>

        <p>Thank you for listening!</p>

    </div>

    <div class="music-notes">🎹 🎸 🎻</div>

    <button onclick="showMessage()">
        Celebrate Music! 🎶
    </button>

    <p id="message"></p>

</div>

<footer>
    <p>♪ Music makes the world more beautiful ♪</p>
    <p>Happy World Music Day! 💜</p>
</footer>

<script>
function showMessage() {
    document.getElementById("message").innerHTML =
    "Music is the language of the heart! 💜🎵";
}
</script>

</body>
</html>
