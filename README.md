Hello there! I'm Cale, currently diving deep into the world of web development as a student at the Northern Alberta Institute of Technology (NAIT). 
With a keen interest in all things web, I am on a journey to transform my passion for technology and design into a career as a web developer.



- 👋 Hi, I’m Cale
- 👀 I’m interested in Web Design/Development and video games
- 🌱 I’m currently learning Responsive fluid Web Design and back end code.
- 📫 How to reach me via email at cale.candelora5@gmail.com
- 😄 Pronouns: he/him
- ⚡ Fun fact: I broke each leg once in the same year 6 months apart 

<!---
CaleC99/CaleC99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes blink-caret {
  50% { border-color: transparent; }
}

.typing {
  overflow: hidden; /* Ensures the content doesn't overflow its container */
  border-right: .15em solid orange; /* The caret */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Centers the content */
  letter-spacing: .15em; /* Adjusts letter spacing for aesthetics */
  animation: 
    typing 3.5s steps(40, end),
    blink-caret .75s step-end infinite;
}
