# unsere-Ahnen/* -----------------------------------------
   ARCHIVKLASSIK – Grundlayout
------------------------------------------*/

body {
    font-family: "Source Sans Pro", Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f2eee6; /* warmes Archiv-Beige */
    color: #2a2a2a;
    line-height: 1.7;
}

main {
    max-width: 900px;
    margin: 50px auto;
    padding: 0 20px;
}

/* -----------------------------------------
   Header & Navigation
------------------------------------------*/

header {
    background: #d8d2c4; /* helles Pergament */
    padding: 25px 0;
    text-align: center;
    border-bottom: 2px solid #b8b2a6;
}

header h1 {
    margin: 0;
    font-family: "Merriweather", serif;
    font-size: 32px;
    letter-spacing: 0.5px;
    color: #3a3a3a;
}

nav {
    margin-top: 12px;
}

nav a {
    color: #4a4a4a;
    margin: 0 12px;
    text-decoration: none;
    font-weight: 600;
}

nav a:hover {
    text-decoration: underline;
}

/* -----------------------------------------
   Footer
------------------------------------------*/

footer {
    text-align: center;
    padding: 20px;
    background: #d8d2c4;
    color: #4a4a4a;
    margin-top: 60px;
    border-top: 2px solid #b8b2a6;
}

/* -----------------------------------------
   Überschriften
------------------------------------------*/

h1, h2, h3 {
    font-family: "Merriweather", serif;
    color: #3a3a3a;
    margin-top: 40px;
}

h1 {
    font-size: 30px;
}

h2 {
    font-size: 24px;
}

h3 {
    font-size: 20px;
}

/* -----------------------------------------
   Karten, Boxen, Container
------------------------------------------*/

.box, .card, .objekt-card {
    background: #ffffff;
    padding: 20px;
    border-radius: 6px;
    border: 1px solid #cfc8bb;
    margin-bottom: 25px;
}

/* -----------------------------------------
   Listen
------------------------------------------*/

ul {
    padding-left: 20px;
}

li {
    margin-bottom: 8px;
}

/* -----------------------------------------
   Bilder
------------------------------------------*/

img {
    border-radius: 4px;
    border: 1px solid #cfc8bb;
    margin-bottom: 20px;
}

/* -----------------------------------------
   Filterleiste
------------------------------------------*/

form {
    background: #faf7f2;
    padding: 15px;
    border: 1px solid #cfc8bb;
    border-radius: 6px;
    margin-bottom: 30px;
}

form label {
    margin-right: 10px;
    font-weight: bold;
    font-family: "Merriweather", serif;
}

form input, form select {
    margin-right: 15px;
    padding: 6px 10px;
    border: 1px solid #b8b2a6;
    border-radius: 4px;
    background: #fff;
}

form button {
    padding: 7px 14px;
    background: #b8b2a6;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

form button:hover {
    background: #9c9587;
}

/* -----------------------------------------
   Startseite – Highlights
------------------------------------------*/

.highlights {
    display: flex;
    gap: 20px;
    margin-top: 40px;
}

.card {
    flex: 1;
    text-align: center;
}

.card a {
    display: inline-block;
    margin-top: 10px;
    color: #6b665c;
    text-decoration: none;
    font-weight: bold;
}

.card a:hover {
    text-decoration: underline;
}

/* -----------------------------------------
   Hero-Bereich
------------------------------------------*/

.hero {
    background: url('/static/img/hero.jpg') center/cover no-repeat;
    padding: 120px 20px;
    color: white;
    text-align: center;
    border-bottom: 2px solid #b8b2a6;
}

.hero-text {
    max-width: 700px;
    margin: 0 auto;
    background: rgba(0,0,0,0.45);
    padding: 20px;
    border-radius: 6px;
}

.hero-button {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 18px;
    background: #b8b2a6;
    color: white;
    text-decoration: none;
    border-radius: 4px;
}

.hero-button:hover {
    background: #9c9587;
}
