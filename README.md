<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>UntoldCoding</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="discontinued"></div>
    <div class="main">
      <p>I have Something <a href="new.html">Click Here</a></p>
    </div>
  </body>
</html>
div,
div:before,
div:after {
  display: block;
  content: "";
  position: absolute;
  box-sizing: border-box;
}

body {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url(https://i.postimg.cc/RFvH4Fk2/chocolate-183543-1280.jpg);
  background-size: cover;
  background-repeat: no-repeat;
}

div.discontinued {
  width: 100vmin;
  height: 100vmin;
  display: flex;
  transform: scale(1.2);
  position: relative;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
  background: radial-gradient(
        ellipse at 50% 120%,
        transparent 2.6vmin,
        #7a311e 2.6vmin,
        #7a311e 3vmin,
        transparent 3vmin
      )
      calc(-5vmin + 34vmin) calc(-10vmin + 38vmin) / 20vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 50% 120%,
        transparent 2.6vmin,
        #7a311e 2.6vmin,
        #7a311e 3vmin,
        transparent 3vmin
      )
      calc(-5vmin + 54vmin) calc(-10vmin + 38vmin) / 20vmin 10vmin no-repeat,
    radial-gradient(ellipse, #512014 2vmin, transparent 2vmin)
      calc(-5vmin + 38vmin) calc(-10vmin + 45vmin) / 12vmin 12vmin no-repeat,
    radial-gradient(ellipse, #512014 2vmin, transparent 2vmin)
      calc(-5vmin + 58vmin) calc(-10vmin + 45vmin) / 12vmin 12vmin no-repeat,
    radial-gradient(ellipse, #d9aa82 2.5vmin, transparent 2.5vmin)
      calc(-5vmin + 31vmin) calc(-10vmin + 50vmin) / 20vmin 12vmin no-repeat,
    radial-gradient(ellipse, #d9aa82 2.5vmin, transparent 2.5vmin)
      calc(-5vmin + 57vmin) calc(-10vmin + 50vmin) / 20vmin 12vmin no-repeat,
    radial-gradient(ellipse, #f8c2bb 2.5vmin, transparent 2.5vmin)
      calc(-5vmin + 44vmin) calc(-10vmin + 53vmin) / 20vmin 10vmin no-repeat,
    radial-gradient(ellipse, #512014 4vmin, transparent 2.5vmin)
      calc(-5vmin + 44vmin) calc(-10vmin + 46vmin) / 20vmin 20vmin no-repeat,
    linear-gradient(25deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 27.5vmin) calc(-10vmin + 41vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 32.5vmin) calc(-10vmin + 46vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(25deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 57.5vmin) calc(-10vmin + 31vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 82.5vmin) calc(-10vmin + 46vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(25deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 74vmin) calc(-10vmin + 41vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 82.5vmin) calc(-10vmin + 54vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(25deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 34vmin) calc(-10vmin + 39vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 62.5vmin) calc(-10vmin + 34vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(25deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 54vmin) calc(-10vmin + 36vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(95deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 42.5vmin) calc(-10vmin + 34vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(35deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 37vmin) calc(-10vmin + 35vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 40vmin) calc(-10vmin + 40vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(15deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 47vmin) calc(-10vmin + 35vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 50vmin) calc(-10vmin + 32vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(15deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 67vmin) calc(-10vmin + 35vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 72vmin) calc(-10vmin + 36vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(15deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 78vmin) calc(-10vmin + 50vmin) / 1.5vmin 1vmin no-repeat,
    linear-gradient(75deg, #bda293 1vmin, transparent 0.5vmin)
      calc(-5vmin + 84vmin) calc(-10vmin + 60vmin) / 1.5vmin 1vmin no-repeat,
    radial-gradient(
        ellipse at 90% 110%,
        transparent 1.8vmin,
        #c78f74 1.8vmin,
        #c78f74 2vmin,
        transparent 1vmin
      )
      calc(-5vmin + 20.5vmin) calc(-10vmin + 42.5vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 90% 110%,
        transparent 1.8vmin,
        #865036 1.8vmin,
        #865036 2vmin,
        transparent 1vmin
      )
      calc(-5vmin + 16vmin) calc(-10vmin + 48vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 10% 10%,
        transparent 1.8vmin,
        #865036 1.8vmin,
        #c78f74 2vmin,
        transparent 1vmin
      )
      calc(-5vmin + 24vmin) calc(-10vmin + 54vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 90% 10%,
        transparent 1.8vmin,
        #865036 1.8vmin,
        #865036 2vmin,
        transparent 1vmin
      )
      calc(-5vmin + 19vmin) calc(-10vmin + 51vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 20% -20%,
        transparent 1.5vmin,
        #c78f74 1.5vmin,
        #c78f74 1.7vmin,
        transparent 1.7vmin
      )
      calc(-5vmin + 21vmin) calc(-10vmin + 59vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 20% -20%,
        transparent 1.5vmin,
        #865036 1.5vmin,
        #865036 1.7vmin,
        transparent 1.7vmin
      )
      calc(-5vmin + 26vmin) calc(-10vmin + 52vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(
        ellipse at 20% 110%,
        transparent 1.8vmin,
        #865036 1.8vmin,
        #865036 2vmin,
        transparent 1vmin
      )
      calc(-5vmin + 25vmin) calc(-10vmin + 41vmin) / 6vmin 10vmin no-repeat,
    radial-gradient(ellipse, #fdfdf9 3.2vmin, transparent 1vmin)
      calc(-5vmin + 22vmin) calc(-10vmin + 44vmin) / 8vmin 15vmin no-repeat,
    radial-gradient(ellipse, #fdfdf9 4vmin, transparent 1vmin)
      calc(-5vmin + 19.75vmin) calc(-10vmin + 46.75vmin) / 9vmin 14vmin
      no-repeat,
    radial-gradient(ellipse, #fdfdf9 3.25vmin, transparent 1vmin)
      calc(-5vmin + 17.5vmin) calc(-10vmin + 51vmin) / 9vmin 14vmin no-repeat,
    radial-gradient(ellipse at 0% 0%, #fdfdf9 4.5vmin, transparent 1vmin)
      calc(-5vmin + 22vmin) calc(-10vmin + 53vmin) / 5vmin 10vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 78.75vmin) calc(-10vmin + 51.5vmin) / 12vmin 14vmin
      no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 73.5vmin) calc(-10vmin + 41.5vmin) / 13vmin 15vmin no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 78vmin) calc(-10vmin + 44.5vmin) / 9vmin 15vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 73vmin) calc(-10vmin + 40vmin) / 12vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 5vmin, transparent 1vmin)
      calc(-5vmin + 69vmin) calc(-10vmin + 37.5vmin) / 12vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 3vmin, transparent 1vmin)
      calc(-5vmin + 71vmin) calc(-10vmin + 35vmin) / 9vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 67vmin) calc(-10vmin + 33.5vmin) / 9vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 60vmin) calc(-10vmin + 31vmin) / 15vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 7vmin, transparent 1vmin)
      calc(-5vmin + 44vmin) calc(-10vmin + 31vmin) / 15vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 6vmin, transparent 1vmin)
      calc(-5vmin + 54vmin) calc(-10vmin + 30vmin) / 15vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 47vmin) calc(-10vmin + 29vmin) / 15vmin 9vmin no-repeat,
    radial-gradient(ellipse, #865036 3.75vmin, transparent 1vmin)
      calc(-5vmin + 52vmin) calc(-10vmin + 29.25vmin) / 12vmin 6vmin no-repeat,
    radial-gradient(ellipse, #865036 3.75vmin, transparent 1vmin)
      calc(-5vmin + 47vmin) calc(-10vmin + 30vmin) / 11vmin 4vmin no-repeat,
    radial-gradient(ellipse, #865036 3.75vmin, transparent 1vmin)
      calc(-5vmin + 43vmin) calc(-10vmin + 31vmin) / 8vmin 4vmin no-repeat,
    radial-gradient(ellipse at left top, #865036 3.75vmin, transparent 1vmin)
      calc(-5vmin + 29vmin) calc(-10vmin + 43vmin) / 8vmin 11vmin no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 35vmin) calc(-10vmin + 32vmin) / 10vmin 8vmin no-repeat,
    radial-gradient(ellipse, #865036 3.5vmin, transparent 1vmin)
      calc(-5vmin + 38vmin) calc(-10vmin + 31.5vmin) / 10vmin 8vmin no-repeat,
    radial-gradient(ellipse, #865036 4.5vmin, transparent 1vmin)
      calc(-5vmin + 34vmin) calc(-10vmin + 36vmin) / 10vmin 8vmin no-repeat,
    radial-gradient(ellipse, #865036 3.5vmin, transparent 1vmin)
      calc(-5vmin + 35vmin) calc(-10vmin + 33vmin) / 10vmin 8vmin no-repeat,
    radial-gradient(ellipse, #865036 3vmin, transparent 1vmin)
      calc(-5vmin + 32vmin) calc(-10vmin + 36vmin) / 8vmin 10vmin no-repeat,
    radial-gradient(ellipse at bottom right, #865036 5vmin, transparent 1vmin)
      calc(-5vmin + 21vmin) calc(-10vmin + 34vmin) / 8vmin 14vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 27vmin) calc(-10vmin + 38vmin) / 8vmin 14vmin no-repeat,
    radial-gradient(ellipse at left top, #865036 3vmin, transparent 1vmin)
      calc(-5vmin + 27vmin) calc(-10vmin + 48vmin) / 6vmin 14vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 17.5vmin) calc(-10vmin + 44vmin) / 12vmin 18vmin no-repeat,
    radial-gradient(ellipse at left, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 27vmin) calc(-10vmin + 44vmin) / 6vmin 18vmin no-repeat,
    radial-gradient(ellipse, #865036 4vmin, transparent 1vmin)
      calc(-5vmin + 16vmin) calc(-10vmin + 49vmin) / 12vmin 18vmin no-repeat,
    radial-gradient(ellipse at left, #865036 3vmin, transparent 1vmin)
      calc(-5vmin + 25vmin) calc(-10vmin + 48.5vmin) / 6vmin 18vmin no-repeat,
    repeating-linear-gradient(
        80deg,
        #c78347 0vmin,
        #c78347 0.5vmin,
        transparent 0.5vmin,
        transparent 3vmin
      )
      calc(-5vmin + 30vmin) calc(-10vmin + 40vmin) / 17vmin 22vmin no-repeat,
    repeating-linear-gradient(
        80deg,
        #c78347 0vmin,
        #c78347 0.5vmin,
        transparent 0.5vmin,
        transparent 3vmin
      )
      calc(-5vmin + 45.25vmin) calc(-10vmin + 36vmin) / 26vmin 26vmin no-repeat,
    repeating-linear-gradient(
        -10deg,
        #c78347 0vmin,
        #c78347 0.5vmin,
        transparent 0.5vmin,
        transparent 3vmin
      )
      calc(-5vmin + 30vmin) calc(-10vmin + 40vmin) / 47vmin 22vmin no-repeat,
    radial-gradient(ellipse at 50% 100%, #cd905b 30vmin, transparent 1vmin)
      calc(-5vmin + 16vmin) calc(-10vmin + 22vmin) / 80vmin 40vmin no-repeat,
    radial-gradient(ellipse at 46% 100%, #865036 34vmin, transparent 1vmin)
      calc(-5vmin + 16vmin) calc(-10vmin + 22vmin) / 80vmin 40vmin no-repeat;
}

div.discontinued:after {
  width: 100vmin;
  height: 100vmin;
  left: -1vmin;
  text-align: center;
  z-index: 99;
  padding-top: 55vmin;
  font-size: 12vmin;
  font-weight: 900;
  transform: scale(1);
  z-index: 999;
  color: #74452f;
  text-shadow: 0 2px 2px #fae385;
  line-height: 0.9;
  text-transform: uppercase;
  white-space: pre-wrap;
  font-family: "Oswald", sans-serif;
  content: "FOr My ";
}

div.discontinued:before {
  width: 100vmin;
  height: 100vmin;
  left: -1vmin;
  text-align: center;
  z-index: 99;
  padding-top: 67vmin;
  font-size: 7.15vmin;
  font-weight: 400;
  transform: scale(1);
  z-index: 999;
  color: #a86a33;
  line-height: 0.9;
  text-transform: uppercase;
  white-space: pre-wrap;
  font-family: "Oswald", sans-serif;
  content: "Chocolate";
  text-shadow: 0 2px 2px #ffffff;
}

.main {
  color: #ffffff;
  position: absolute;
  bottom: 5%;
  font-weight: 600;
  font-size: 35px;
  font-family: "Oswald", sans-serif;
  text-shadow: 0 2px 2px #512014;
}
.main a {
  color: white;
  text-shadow: 0 2px 2px #512014;
}
.main a:hover {
  color: rgb(230, 47, 47);
  text-shadow: 0 2px 2px #ffffff;
}
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>UntoldCoding</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="discontinued"></div>
    <div class="main">
      <p>I have Something <a href="new.html">Click Here</a></p>
    </div>
  </body>
</html>
 @import url("https://fonts.googleapis.com/css?family=Bitter:700&display=swap");
*,
*:before,
*:after {
  position: relative;
  box-sizing: border-box;
}

html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  background: #502d24;
  transform-style: preserve-3d;
  perspective: 1000px;
}

.instructions {
  position: absolute;
  bottom: 10%;

  left: 0;
  right: 0;
  padding: 0.5rem;
  text-align: center;
  font-family: Bitter, sans-serif;
  color: white;
}

:root {
  --brown: #754c28;
  --brown-light: #bcaea1a4;
  --brown-dark: #a9a8a8;
  --brown-darker: #2c241c;
  --brown-darkz: #000000;
}

.chocolate-button {
  /* Reset button styles */
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  border: none;
  background: none;
  padding: 0;
  margin: 0;
  font-size: 10vmin;
  font-family: Bitter, cursive;
  cursor: pointer;
  transform: rotateX(10deg) rotateZ(10deg);
}
@media (min-width: 600px) {
  .chocolate-button {
    font-size: 60px;
  }
}
.chocolate-button .bar {
  border-radius: 0.3em;
  display: block;
  transition: transform 0.1s ease;
}
.chocolate-button .bar:hover,
.chocolate-button .bar:focus,
.chocolate-button .bar:active {
  transform: translateY(0.05em);
}
.chocolate-button .bar:before,
.chocolate-button .bar:after {
  content: "";
  position: absolute;
  left: 0;
  width: 100%;
  height: 100%;
  z-index: -1;
  border-radius: inherit;
}
.chocolate-button .bar:before {
  background-color: var(--brown);
  border: 0.35em rgba(117, 76, 40, 0.6) ridge;
  top: 0;
  z-index: 0;
}
.chocolate-button .bar:after {
  top: 0.3em;
  left: 0.3em;
  background: var(--brown-dark);
  box-shadow: inset 0 -0.05em var(--brown-darker);
}
.chocolate-button .text,
.chocolate-button .bar:before,
.chocolate-button .bar:after {
  transition: -webkit-clip-path 0.15s steps(3, start);
  transition: clip-path 0.15s steps(3, start);
  transition: clip-path 0.15s steps(3, start),
    -webkit-clip-path 0.15s steps(3, start);
  -webkit-clip-path: polygon(
    100% 0,
    100% 100%,
    calc(30% + var(--x, 0) * 1px) 100%,
    calc(24% + var(--x, 0) * 1px) 100%,
    calc(7% + var(--x, 0) * 1px) 100%,
    calc(0% + var(--x, 0) * 1px) 100%,
    calc(-6% + var(--x, 0) * 1px) 100%,
    calc(-20% + var(--x, 0) * 1px) 100%,
    calc(-30% + var(--x, 0) * 1px) 100%,
    0 100%,
    0 0
  );
  clip-path: polygon(
    100% 0,
    100% 100%,
    calc(30% + var(--x, 0) * 1px) 100%,
    calc(24% + var(--x, 0) * 1px) 100%,
    calc(7% + var(--x, 0) * 1px) 100%,
    calc(0% + var(--x, 0) * 1px) 100%,
    calc(-6% + var(--x, 0) * 1px) 100%,
    calc(-20% + var(--x, 0) * 1px) 100%,
    calc(-30% + var(--x, 0) * 1px) 100%,
    0 100%,
    0 0
  );
}
.chocolate-button .text {
  display: block;
  padding: 1em 0.5em;
  color: var(--brown-darkz);
  opacity: 0.8;
  text-shadow: 1px 2px var(--brown-light), -1px -2px black;
}

/* ---------------------------------- */
.crumbs {
  position: absolute;
  width: 0.3em;
  height: 0.3em;
  border-radius: 50%;
  top: 0;
  left: calc(var(--x, 0) * 1px);
  pointer-events: none;
  opacity: 0;
}
.crumbs:before,
.crumbs:after {
  content: "";
  position: absolute;
  height: 100%;
  width: 100%;
  border-radius: inherit;
  box-shadow: -1.7547952103em 1.6770189606em var(--brown),
    -1.7547952103em 1.6770189606em var(--brown),
    -2.3011845128em 2.8794398227em var(--brown),
    -2.3011845128em 2.8794398227em var(--brown),
    -0.4217394874em 0.0705320589em var(--brown),
    -0.4217394874em 0.0705320589em var(--brown),
    -0.1159591693em 0.7704363452em var(--brown),
    -0.1159591693em 0.7704363452em var(--brown),
    -2.1492040765em 2.1268170697em var(--brown),
    -2.1492040765em 2.1268170697em var(--brown),
    2.4411882244em 0.9208513046em var(--brown),
    2.4411882244em 0.9208513046em var(--brown),
    2.1550483899em 1.5017137668em var(--brown),
    2.1550483899em 1.5017137668em var(--brown),
    -1.9464615267em 1.4567134934em var(--brown),
    -1.9464615267em 1.4567134934em var(--brown),
    -2.8690082426em 2.7340134596em var(--brown),
    -2.8690082426em 2.7340134596em var(--brown),
    -1.6327566611em 1.5461441639em var(--brown),
    -1.6327566611em 1.5461441639em var(--brown),
    -1.7259157274em 2.7136771803em var(--brown),
    -1.7259157274em 2.7136771803em var(--brown),
    -0.9947450354em 2.2508840811em var(--brown),
    -0.9947450354em 2.2508840811em var(--brown),
    1.6174468599em 0.1411684513em var(--brown),
    1.6174468599em 0.1411684513em var(--brown),
    -1.3639903681em 2.24584453em var(--brown),
    -1.3639903681em 2.24584453em var(--brown),
    -1.6694185722em 2.5090191985em var(--brown),
    -1.6694185722em 2.5090191985em var(--brown),
    0.3857759081em 1.2122188346em var(--brown),
    0.3857759081em 1.2122188346em var(--brown),
    -1.1774451283em 2.1662207765em var(--brown),
    -1.1774451283em 2.1662207765em var(--brown),
    -2.1704305823em 1.3741380577em var(--brown),
    -2.1704305823em 1.3741380577em var(--brown),
    0.5921977864em 0.6783236635em var(--brown),
    0.5921977864em 0.6783236635em var(--brown),
    1.0593329551em 2.6875484967em var(--brown),
    1.0593329551em 2.6875484967em var(--brown);
}
.crumbs:before {
  height: 70%;
  width: 70%;
}

/* ---------------------------------- */
.chocolate-button:focus,
.chocolate-button:active {
  outline: none;
  -webkit-animation: chomp 0.3s cubic-bezier(0.72, 0.12, 0.32, 0.96);
  animation: chomp 0.3s cubic-bezier(0.72, 0.12, 0.32, 0.96);
}
@-webkit-keyframes chomp {
  30% {
    transform: translateZ(-6vmin) rotateX(15deg) rotateZ(12deg);
  }
  70% {
    transform: translateZ(-10vmin) rotateX(0deg) rotateZ(8deg);
  }
}
@keyframes chomp {
  30% {
    transform: translateZ(-6vmin) rotateX(15deg) rotateZ(12deg);
  }
  70% {
    transform: translateZ(-10vmin) rotateX(0deg) rotateZ(8deg);
  }
}
.chocolate-button:focus .text,
.chocolate-button:focus .bar:before,
.chocolate-button:focus .bar:after,
.chocolate-button:active .text,
.chocolate-button:active .bar:before,
.chocolate-button:active .bar:after {
  transition: none;
  -webkit-clip-path: polygon(
    100% 0,
    100% 100%,
    calc(30% + var(--x, 0) * 1px) 100%,
    calc(24% + var(--x, 0) * 1px) 75%,
    calc(7% + var(--x, 0) * 1px) 58%,
    calc(0% + var(--x, 0) * 1px) 65%,
    calc(-6% + var(--x, 0) * 1px) 45%,
    calc(-20% + var(--x, 0) * 1px) 51%,
    calc(-30% + var(--x, 0) * 1px) 100%,
    0 100%,
    0 0
  );
  clip-path: polygon(
    100% 0,
    100% 100%,
    calc(30% + var(--x, 0) * 1px) 100%,
    calc(24% + var(--x, 0) * 1px) 75%,
    calc(7% + var(--x, 0) * 1px) 58%,
    calc(0% + var(--x, 0) * 1px) 65%,
    calc(-6% + var(--x, 0) * 1px) 45%,
    calc(-20% + var(--x, 0) * 1px) 51%,
    calc(-30% + var(--x, 0) * 1px) 100%,
    0 100%,
    0 0
  );
}
.chocolate-button:focus .crumbs,
.chocolate-button:active .crumbs {
  opacity: 1;
  -webkit-animation: crumbs 1.5s ease-out both;
  animation: crumbs 1.5s ease-out both;
}
@-webkit-keyframes crumbs {
  to {
    transform: translateY(100vh);
  }
}
@keyframes crumbs {
  to {
    transform: translateY(100vh);
  }
}
.chocolate-button:focus .crumbs:before,
.chocolate-button:active .crumbs:before {
  -webkit-animation: inherit;
  animation: inherit;
  -webkit-animation-name: crumbs-left;
  animation-name: crumbs-left;
  -webkit-animation-duration: 1.2s;
  animation-duration: 1.2s;
}
@-webkit-keyframes crumbs-left {
  to {
    transform: translateX(-15vw) rotate(-5deg);
  }
}
@keyframes crumbs-left {
  to {
    transform: translateX(-15vw) rotate(-5deg);
  }
}
.chocolate-button:focus .crumbs:after,
.chocolate-button:active .crumbs:after {
  -webkit-animation: inherit;
  animation: inherit;
  -webkit-animation-name: crumbs-right;
  animation-name: crumbs-right;
}
@-webkit-keyframes crumbs-right {
  to {
    transform: translateX(15vw) rotate(5deg);
  }
}
@keyframes crumbs-right {
  to {
    transform: translateX(15vw) rotate(5deg);
  }
}
