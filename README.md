### Hi there 👋

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 100">
  <text x="50%" y="40%" dominant-baseline="middle" text-anchor="middle" font-size="24" fill="blue">
    Elie Maatouk
  </text>
  <text x="50%" y="80%" dominant-baseline="middle" text-anchor="middle" font-size="24" fill="#C139EC">
    <tspan id="text"></tspan>
  </text>
  <script>
<![CDATA[
  const textElement = document.getElementById("text");
  const texts = ["Full-Stack Developer", "Asp.net Core", "Reactjs","Angular", "Nextjs"];
  let currentTextIndex = 0;
  let isTyping = true;
  let typedText = "";

function changeText() {
const currentText = texts[currentTextIndex];
if (isTyping) {
typedText += currentText[typedText.length];
textElement.textContent = typedText;
if (typedText === currentText) {
isTyping = false;
setTimeout(() => {
isTyping = true;
typedText = "";
currentTextIndex = (currentTextIndex + 1) % texts.length;
}, 1000);
}
} else {
textElement.textContent = currentText;
}
setTimeout(changeText, 50);
}

changeText();
]]>
</script>
</svg>

<!--
**Egit90/Egit90** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
