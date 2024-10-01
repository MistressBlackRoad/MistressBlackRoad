- 👋 Hi, I’m @MistressBlackRoad
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: #000;
    color: #fff;
    font-family: Arial, sans-serif;
}

header {
    background-color: #1a1a1a;
    padding: 1em;
}

nav ul {
    display: flex;
    justify-content: space-around;
    list-style-type: none;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 2em;
    margin: 1em 0;
}

#contacto form {
    display: flex;
    flex-direction: column;
}

#contacto input, #contacto textarea {
    padding: 0.5em;
    margin-bottom: 1em;
    background-color: #333;
    color: #fff;
    border: 1px solid #444;
}

button {
    padding: 0.7em;
    background-color: #444;
    color: #fff;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

footer {
    text-align: center;
    padding: 1em;
    background-color: #1a1a1a;
}
document.querySelector("form").addEventListener("submit", function(event) {
    event.preventDefault();
    alert("Gracias por tu mensaje. Te contactaremos pronto.");
});

<!---
MistressBlackRoad/MistressBlackRoad is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
